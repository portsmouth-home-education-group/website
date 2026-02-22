<script lang="ts">
	import '../app.css';

	let { children } = $props();

	let mobileMenuOpen = $state(false);

	const navLinks = [
		{ href: '#home', label: 'Home' },
		{ href: '#about', label: 'About' },
		{ href: '#activities', label: 'What we do' },
		{ href: '#contact', label: 'Contact' }
	];

	function closeMenu() {
		mobileMenuOpen = false;
	}
</script>

<a href="#main-content" class="skip-link">Skip to content</a>

<header class="site-header">
	<div class="container header-inner">
		<a href="#home" class="logo" onclick={closeMenu}>
			<img src="/logo.jpg" alt="PHEG — Portsmouth Home Education Group" class="logo-img" />
		</a>

		<nav class="nav-desktop hide-mobile" aria-label="Main navigation">
			{#each navLinks as link}
				<a href={link.href} class="nav-link">{link.label}</a>
			{/each}
		</nav>

		<button
			class="hamburger hide-desktop"
			onclick={() => mobileMenuOpen = !mobileMenuOpen}
			aria-expanded={mobileMenuOpen}
			aria-controls="mobile-nav"
			aria-label={mobileMenuOpen ? 'Close menu' : 'Open menu'}
		>
			<span class="hamburger-line" class:open={mobileMenuOpen}></span>
			<span class="hamburger-line" class:open={mobileMenuOpen}></span>
			<span class="hamburger-line" class:open={mobileMenuOpen}></span>
		</button>
	</div>

	{#if mobileMenuOpen}
		<nav class="nav-mobile hide-desktop" id="mobile-nav" aria-label="Mobile navigation">
			{#each navLinks as link, i}
				<a
					href={link.href}
					class="nav-link-mobile animate-fade-in-up"
					style="animation-delay: {i * 0.06}s"
					onclick={closeMenu}
				>
					{link.label}
				</a>
			{/each}
		</nav>
	{/if}
</header>

<main id="main-content">
	{@render children()}
</main>

<footer class="site-footer texture-overlay">
	<div class="container footer-inner">
		<div class="footer-brand">
			<a href="#home" class="footer-logo">
				<img src="/logo.jpg" alt="PHEG" class="footer-logo-img" />
			</a>
			<p class="footer-tagline">Portsmouth Home Education Group</p>
		</div>

		<div class="footer-contact">
			<address class="footer-address">
				The HIVE Portsmouth Hub<br>
				22 Edinburgh Road<br>
				Portsmouth, PO1 1DH
			</address>
			<p class="footer-links-contact">
				<a href="mailto:info@pheg.org.uk">info@pheg.org.uk</a>
			</p>
		</div>

		<div class="footer-legal">
			<p>Portsmouth Home Education Group is a charitable organisation dedicated to supporting home-educating families in Portsmouth and surrounding communities.</p>
			<p class="footer-charity-number">Charity registration pending</p>
		</div>
	</div>
</footer>

<style>
	.site-header {
		position: sticky;
		top: 0;
		z-index: 100;
		background: rgba(245, 237, 198, 0.92);
		backdrop-filter: blur(12px);
		-webkit-backdrop-filter: blur(12px);
		border-bottom: 1px solid var(--color-sand);
		height: var(--header-height);
		display: flex;
		flex-direction: column;
		justify-content: center;
	}

	.header-inner {
		display: flex;
		align-items: center;
		justify-content: space-between;
		height: var(--header-height);
	}

	.logo,
	.footer-logo {
		display: flex;
		align-items: center;
		text-decoration: none;
	}

	.logo-img {
		height: 44px;
		width: 44px;
		border-radius: 50%;
		object-fit: cover;
	}

	.footer-logo-img {
		height: 40px;
		width: 40px;
		border-radius: 50%;
		object-fit: cover;
		box-shadow: 0 0 0 3px rgba(255, 255, 255, 0.25);
		opacity: 0.9;
	}

	.footer-logo:hover .footer-logo-img {
		opacity: 1;
	}

	.nav-desktop {
		display: flex;
		align-items: center;
		gap: var(--space-xl);
	}

	.nav-link {
		font-family: var(--font-heading);
		font-weight: 600;
		font-size: var(--text-sm);
		color: var(--color-text-muted);
		text-decoration: none;
		text-transform: uppercase;
		letter-spacing: 0.05em;
		padding: var(--space-xs) 0;
		position: relative;
	}

	.nav-link::after {
		content: '';
		position: absolute;
		bottom: -2px;
		left: 0;
		width: 0;
		height: 2px;
		background: var(--color-turquoise);
		border-radius: var(--radius-full);
		transition: width var(--duration-normal) var(--ease-out);
	}

	.nav-link:hover {
		color: var(--color-forest);
	}

	.nav-link:hover::after {
		width: 100%;
	}

	/* Hamburger */
	.hamburger {
		display: flex;
		flex-direction: column;
		justify-content: center;
		gap: 5px;
		width: 36px;
		height: 36px;
		background: none;
		border: none;
		cursor: pointer;
		padding: 4px;
	}

	.hamburger-line {
		display: block;
		width: 100%;
		height: 2.5px;
		background: var(--color-forest-deep);
		border-radius: var(--radius-full);
		transition: all var(--duration-normal) var(--ease-out);
		transform-origin: center;
	}

	.hamburger-line.open:nth-child(1) {
		transform: translateY(7.5px) rotate(45deg);
	}

	.hamburger-line.open:nth-child(2) {
		opacity: 0;
		transform: scaleX(0);
	}

	.hamburger-line.open:nth-child(3) {
		transform: translateY(-7.5px) rotate(-45deg);
	}

	/* Mobile nav */
	.nav-mobile {
		display: flex;
		flex-direction: column;
		background: var(--color-cream);
		border-bottom: 1px solid var(--color-sand);
		padding: var(--space-md) var(--space-lg) var(--space-xl);
	}

	.nav-link-mobile {
		font-family: var(--font-heading);
		font-weight: 700;
		font-size: var(--text-xl);
		color: var(--color-forest-deep);
		text-decoration: none;
		padding: var(--space-md) 0;
		border-bottom: 1px solid var(--color-sand);
	}

	.nav-link-mobile:last-child {
		border-bottom: none;
	}

	.nav-link-mobile:hover {
		color: var(--color-turquoise);
	}

	/* Footer */
	.site-footer {
		background: var(--color-forest-deep);
		color: var(--color-sage-light);
		padding-block: var(--space-3xl);
	}

	.footer-inner {
		display: grid;
		gap: var(--space-2xl);
	}

	@media (min-width: 768px) {
		.footer-inner {
			grid-template-columns: 1fr 1fr 1fr;
			gap: var(--space-3xl);
		}
	}

	.footer-brand {
		display: flex;
		flex-direction: column;
		gap: var(--space-sm);
	}

	.footer-tagline {
		font-size: var(--text-sm);
		color: var(--color-sage);
	}

	.footer-contact {
		display: flex;
		flex-direction: column;
		gap: var(--space-md);
		font-size: var(--text-sm);
		line-height: var(--leading-relaxed);
	}

	.footer-contact a {
		color: var(--color-sage-light);
		text-decoration-color: rgba(141, 217, 214, 0.3);
	}

	.footer-contact a:hover {
		color: var(--color-warm-white);
	}

	.footer-legal {
		font-size: var(--text-xs);
		color: var(--color-sage);
		line-height: var(--leading-relaxed);
	}

	.footer-address {
		font-style: normal;
	}

	.footer-charity-number {
		font-size: var(--text-xs);
		margin-top: var(--space-xs);
		opacity: 0.7;
		font-style: italic;
	}
</style>
