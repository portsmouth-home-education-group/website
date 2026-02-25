<svelte:head>
	<title>PHEG — Portsmouth Home Education Group</title>
	<meta name="description" content="Portsmouth Home Education Group supports home-educating families in Portsmouth with resources, community connections, events, and advocacy." />
	<meta property="og:type" content="website" />
	<meta property="og:url" content="https://pheg.org.uk/" />
	<meta property="og:title" content="PHEG — Portsmouth Home Education Group" />
	<meta property="og:description" content="Supporting home-educating families in Portsmouth with resources, community connections, events, and advocacy." />
	<meta property="og:image" content="https://pheg.org.uk/logo.jpg" />
	<meta property="og:locale" content="en_GB" />
	<meta property="og:site_name" content="Portsmouth Home Education Group" />

	<meta name="twitter:card" content="summary" />
	<meta name="twitter:title" content="PHEG — Portsmouth Home Education Group" />
	<meta name="twitter:description" content="Supporting home-educating families in Portsmouth with resources, community connections, events, and advocacy." />
	<meta name="twitter:image" content="https://pheg.org.uk/logo.jpg" />

	{@html `<script type="application/ld+json">${JSON.stringify({
		"@context": "https://schema.org",
		"@type": "Organization",
		"name": "Portsmouth Home Education Group",
		"alternateName": "PHEG",
		"url": "https://pheg.org.uk",
		"logo": "https://pheg.org.uk/logo.jpg",
		"email": "info@pheg.org.uk",
		"address": {
			"@type": "PostalAddress",
			"streetAddress": "The HIVE Portsmouth Hub, 22 Edinburgh Road",
			"addressLocality": "Portsmouth",
			"postalCode": "PO1 1DH",
			"addressCountry": "GB"
		},
		"areaServed": {
			"@type": "City",
			"name": "Portsmouth",
			"containedInPlace": {
				"@type": "Country",
				"name": "United Kingdom"
			}
		},
		"description": "Portsmouth Home Education Group exists to promote, maintain, improve and advance the education of children in Portsmouth and surrounding communities who are educated outside of full-time state or private institutions."
	})}</script>`}
</svelte:head>

<section id="home" class="hero texture-overlay">
	<div class="container hero-content">
		<div class="hero-badge animate-fade-in-up">
			<span class="hero-badge-dot"></span>
			Supporting families in Portsmouth
		</div>
		<h1 class="hero-title animate-fade-in-up animate-delay-1">
			Supporting home education in Portsmouth
		</h1>
		<p class="hero-subtitle animate-fade-in-up animate-delay-2">
			Connecting families, sharing resources, and building community
		</p>
		<div class="hero-actions animate-fade-in-up animate-delay-3">
			<a href="#contact" class="btn btn-primary">Get in touch</a>
			<a href="#about" class="btn btn-secondary">Learn more</a>
		</div>

		<div class="hero-decoration" aria-hidden="true">
			<div class="hero-circle hero-circle-1"></div>
			<div class="hero-circle hero-circle-2"></div>
			<div class="hero-circle hero-circle-3"></div>
		</div>
	</div>
</section>

<section id="about" class="section about-section">
	<div class="container">
		<h2 class="section-heading">About PHEG</h2>
		<div class="about-content">
			<p class="section-intro">
				Home educating in Portsmouth? You’re not on your own.
			</p>
			<p class="section-intro">
				Portsmouth Home Education Group exists to support families in Portsmouth and the surrounding areas who educate their children outside of full-time school. Our aim is to promote and strengthen home education locally by helping families access opportunities, share knowledge, and feel part of a wider community.
			</p>
			<p class="section-intro">
				We are a parent-led group, and much of what happens through PHEG grows from families themselves — their experience, their skills, and their willingness to organise things together. By connecting families, we help reduce isolation and make it easier to find practical support, shared activities, and people who understand the journey.
			</p>
			<p class="section-intro">
				Home education looks different in every household. Some families prefer structure; others take a more flexible or interest-led approach. We respect that diversity and aim to provide a space where families can find support that fits their own way of doing things.
			</p>
			<p class="section-intro">
				When families feel connected and supported, young people benefit too, through shared learning opportunities, social connection, and the confidence that comes from being part of a wider community.
			</p>
		</div>
	</div>
</section>

<section id="activities" class="section activities-section">
	<div class="container">
		<h2 class="section-heading">What we do</h2>
		<div class="about-content">
			<p class="section-intro">
				PHEG supports families in practical, straightforward ways. We signpost educational resources and local opportunities that families may wish to explore, and we support parents in organising workshops, group sessions and meetups so young people can learn alongside others and build friendships.
			</p>
			<p class="section-intro">
				We facilitate opportunities for families to connect, share experiences and learn from one another. For those navigating additional needs, we aim to offer guidance and help families find others with similar experiences.
			</p>
			<p class="section-intro">
				Where appropriate, we also advocate for home-educating families and seek to ensure their voices are heard in local conversations that affect them.
			</p>
		</div>
	</div>
</section>

<section id="faq" class="section faq-section">
	<div class="container">
		<h2 class="section-heading">Frequently Asked Questions</h2>
		<p class="section-intro faq-intro">
			Common questions from new home educators and their families.
		</p>

		<div class="faq-list">
			<details class="faq-item">
				<summary class="faq-question">What is home education?</summary>
				<div class="faq-answer">
					<p>Home education is where parents exercise their responsibility to provide their child with an education suitable for their "age, aptitude and ability" themselves, rather than outsource that responsibility to an alternative institution — commonly a state or private school. This responsibility is enshrined in law as Section 7 of the Education Act 1996.</p>
					<p>In a home education environment, learning can be viewed as being a continual, natural process, which is strongly connected with everyday life and real experiences, and does not have to be restricted by school hours.</p>
				</div>
			</details>

			<details class="faq-item">
				<summary class="faq-question">What's the difference between home education and home schooling?</summary>
				<div class="faq-answer">
					<p>The term 'home schooling' originated in the United States — and is still used widely in the US, as well as places like Australia and Canada. When home education began to become popular in the UK (in the 1980s and 1990s), the term 'home schooling' was adopted because it was already established.</p>
					<p>However, by the mid-1990s, there was discussion amongst the community about whether the term 'home schooling' really reflected the realities of what families were doing. At that point, the term 'home education' began to be more widely used. This acknowledged the idea that home education did not involve replicating 'school at home' and that home educators seek to provide an appropriate education for their children in all kinds of ways. It is an inclusive term of the whole home education community in the UK, and therefore is more widely accepted.</p>
				</div>
			</details>

			<details class="faq-item">
				<summary class="faq-question">Is home education like the experiences we had during the pandemic?</summary>
				<div class="faq-answer">
					<p>No! During the pandemic, home educators were confined to their homes like everyone else and weren't able to undertake their usual activities and social groups outside of the home. As a home educator, you also don't receive elements like educational material provided by school.</p>
				</div>
			</details>

			<details class="faq-item">
				<summary class="faq-question">How do parents come to home education?</summary>
				<div class="faq-answer">
					<p>There are a variety of reasons, ranging from a desire to continue the natural learning process that families began in the early years, to dissatisfaction with the current education system — and therefore wanting to find a better way to support the child's wellbeing and learning. The rise of social media and press coverage has allowed parents to find and connect with the national and local home education groups.</p>
				</div>
			</details>

			<details class="faq-item">
				<summary class="faq-question">Do I have to follow set hours?</summary>
				<div class="faq-answer">
					<p>No. Home education can happen any time of the day, week or year — including 6pm at night, on weekends, and even on Christmas Day!</p>
					<p>The legal requirement is to provide your child with a full-time education that is suitable for their "age, aptitude and ability", but full-time does not mean that you need to follow any specific timetable, it just means that the education should form a significant part of your child's life. Since home education is flexible and highly tailored to your child, it is typically a lot more time-efficient than a school education.</p>
				</div>
			</details>

			<details class="faq-item">
				<summary class="faq-question">Do I have to follow a curriculum?</summary>
				<div class="faq-answer">
					<p>No. As a home educator, you have the freedom to facilitate your child's interests in any way that you deem to be appropriate. You are not restricted to following any curriculum.</p>
					<p>If you do wish to follow a curriculum, then you are able to do that as well. You might follow the English National Curriculum, but you may prefer to follow a state curriculum from another country, or purchase an alternative curriculum that fits in with your family's needs and wishes.</p>
				</div>
			</details>

			<details class="faq-item">
				<summary class="faq-question">Do I have to teach my child everything?</summary>
				<div class="faq-answer">
					<p>No. Home educators often refer to themselves as facilitators, rather than teachers. The aim is to support a child's learning and this can happen in many different ways.</p>
					<p>In addition to any areas of expertise that a parent may have, there are lots of resources available to support learning, both locally and online. The availability of resources have increased massively since the pandemic, as there is more awareness around home education. A great resource can be a local or national home education Facebook group. If you have a question about home education, that's usually a good place to start.</p>
				</div>
			</details>

			<details class="faq-item">
				<summary class="faq-question">Can my child sit exams?</summary>
				<div class="faq-answer">
					<p>Yes. However, this can be more challenging to arrange than by accessing exams through a school. As a home educator, the cost of exams — and any expert tuition leading up to them — has to be met by the parent. Occasionally, a local authority will provide some funding towards exams, but this is unusual. Home educators will also need to find an exam centre where their child can sit their exams.</p>
					<p>Despite this, taking exams is possible and can involve some benefits — for example, home educated young people can have more input into which exams they study for and when. There is also no requirement to take lots of GCSEs at age 16. Exams could be taken earlier or later than in school, and alternative qualifications can be accessed as well.</p>
				</div>
			</details>

			<details class="faq-item">
				<summary class="faq-question">What does a typical home ed day look like?</summary>
				<div class="faq-answer">
					<p>This is a really common question — and is almost impossible to answer! If you asked any number of home educating families, they would give you any number of responses.</p>
					<p>Many home educators have some sort of structure to their week: this is often provided by the regular groups that they attend (perhaps focused on particular subjects, like French or Maths); or by regular tasks that they choose to complete at home (perhaps undertaking project work; preparing for formal examinations; completing a task in an education app; attending an online class; or simply having regular opportunities for play and investigation).</p>
					<p>But many will also tell you that there is no such thing as a 'typical' home ed day! The regular activities are often supplemented by additional events: perhaps a group trip to a museum; or a play-meet in a woodland or the trampoline centre; or taking part in a film festival.</p>
					<p>Since home ed is focused on your child, you have the opportunity to tailor it to their particular interests or educational goals. Home ed can look however you and your family want it to look. It is a very personal and flexible journey — and will change as you become more experienced and your child becomes older.</p>
				</div>
			</details>

			<details class="faq-item">
				<summary class="faq-question">How do home educated children socialise?</summary>
				<div class="faq-answer">
					<p>Whilst this is one of society's most common concerns, it's usually one of the least for the home education community!</p>
					<p>In and around Portsmouth, we have regular play-meets and activities for children aged 0–16. Through these, children have the opportunity to meet and interact with one another. Due to the nature of home ed, the opportunities to meet aren't restricted to what is currently available. Many parents will organise their own meet-ups between families. Or, if a parent spots a gap in the provision, they are able to create new groups and new opportunities to socialise, learn and have fun.</p>
				</div>
			</details>

			<details class="faq-item">
				<summary class="faq-question">What activity opportunities are there for children in the Portsmouth Home Education Group?</summary>
				<div class="faq-answer">
					<p>Our group is run by parents who will actively create opportunities for regular and one-off activities for their children. These are the opportunities that have been offered in the last year (most groups run term-time only):</p>
					<ul>
						<li>Playground meets in Portsmouth</li>
						<li>STEM group</li>
						<li>Art group</li>
						<li>Sports group</li>
						<li>Lego social group</li>
						<li>Horse riding sessions</li>
						<li>Roller skating sessions</li>
						<li>Ice skating in Gosport</li>
						<li>Bouldering sessions at Red Spider in Fareham</li>
						<li>Home ed sessions available at Flip Out</li>
						<li>Home ed rates for Marwell Zoological Park</li>
						<li>Arts Award sessions at the Aspex Gallery</li>
						<li>Regular workshops at Swanwick Lakes</li>
						<li>Trips to local museums, such as the Historic Dockyard, Dickens' Birthplace and Seacity Museum</li>
						<li>Trips to London for workshops at the Science Museum, Physic Garden and Houses of Parliament</li>
						<li>Trips to Paultons Park and Legoland</li>
						<li>Attending children's music concerts in Portsmouth Guildhall and Chichester Festival Theatre</li>
						<li>Theatre trips to see a range of productions, like The Wizard of Oz, The Sound of Music, Life of Pi, The Jungle Book and the annual panto production at the King's Theatre</li>
						<li>Community events like summer Sports Day, Christmas Party and Not Back To School picnic</li>
						<li>And more…</li>
					</ul>
				</div>
			</details>

			<details class="faq-item">
				<summary class="faq-question">What about SEN?</summary>
				<div class="faq-answer">
					<p>There are many children with specific learning difficulties in the home education group. As you meet new people — both online and in the 'real' world — you will find support from other parents who are home educating their children with SEN.</p>
					<p>Home education is often particularly valuable for children with SEN because of the ability to precisely tailor your provision to your specific child's needs. It also allows children who find the demands of a busy classroom overwhelming to achieve an education in a calmer, more familiar environment.</p>
				</div>
			</details>

			<details class="faq-item">
				<summary class="faq-question">How much money does it cost to home educate?</summary>
				<div class="faq-answer">
					<p>As with other aspects of parenting, it's up to you how much you choose to spend on home education. When you're calculating the cost, it's important to remember that not even state education is totally free: there's the cost of things like uniform, trips and charity fundraising events. This can add up to a significant amount of money.</p>
					<p>In all likelihood, you will want to spend some money on resources and trips at some point, but what you purchase, and therefore how much you spend, is completely up to you. As a national and local home education community, we also have access to reduced rate online and physical resources, as well as reduced rates on trips to a huge variety of attractions offering educational experiences.</p>
					<p>Home educators are also free to go on holiday during the cheaper, term times — these experiences can offer a wealth of educational opportunities. In essence, home education can cost as much or as little as you like.</p>
				</div>
			</details>

			<details class="faq-item">
				<summary class="faq-question">Am I good enough to educate my children at home?</summary>
				<div class="faq-answer">
					<p>As your child's parent, you know them best of all — and you will want to support them to be the best they can be. This immediately gives you an advantage as a home educator.</p>
					<p>It's important to remember that your role as a home educator is not that of a teacher; you will be a facilitator for your child's learning. It's likely that you already 'home ed' when you're with your child anyway. Any time you had a conversation in response to those "Why?" questions; any time you got out the art materials; any time you read together; and any time you noticed the changing seasons when you were out for a walk — home ed is all around us, and you are one of the best placed people to support your child in their education.</p>
				</div>
			</details>

			<details class="faq-item">
				<summary class="faq-question">Do people work and home educate?</summary>
				<div class="faq-answer">
					<p>Home educating families manage their work and finances in a variety of ways. Working is definitely possible, but does often involve the usual juggling act of parenting. Sometimes it's a case of being imaginative and resourceful — as you may well have been when your child was younger.</p>
				</div>
			</details>

			<details class="faq-item">
				<summary class="faq-question">What role do Local Authorities have with regards to home education?</summary>
				<div class="faq-answer">
					<p>Local Authorities do not have an obligation in law to provide children with an education; that duty lies with parents. However, they do have a duty to identify any children in their area who are missing education. To do this, they are able to contact home educating parents and ask for information about the educational provision that they provide to their child.</p>
					<p>Some Local Authorities make contact with parents very infrequently and, when they do, they don't require much information to conclude that a child isn't in their remit. However, some Local Authorities can be very suspicious of home educators, which can lead to them demanding lots of information and evidence on an annual basis.</p>
					<p>Your local Facebook support group will be able to advise which category your Local Authority falls into, as well as support you in dealing with them, if necessary.</p>
				</div>
			</details>

			<details class="faq-item">
				<summary class="faq-question">Should I home educate?</summary>
				<div class="faq-answer">
					<p>The only person who can make that decision is you and your family. We suggest that you research home education — find out about the different ethoses and what the legal position is in England — and come to meet existing home educators at a local group.</p>
					<p>But, ultimately, it's much the same as preparing to welcome a child into your life: at some point you just need to dive in and see what happens! Home educating — like parenting — can be extremely rewarding, but can also be hard work. Having said that, the vast majority of people who find home education feel it's a better way of living and learning, so why not find out more?</p>
				</div>
			</details>

			<details class="faq-item">
				<summary class="faq-question">What do I need to do if I've decided to home educate?</summary>
				<div class="faq-answer">
					<p>There are different procedures for different current education settings:</p>

					<h4>If your child is in a mainstream school</h4>
					<p>You need to write to the Headteacher to inform them of your decision to home educate, and request that your child's name is removed from the school roll. You can find templates for deregistration letters on the internet, as it's important that you include the correct legal wording. You are not required to tell them your reasons for home educating, but you can if that's what you wish. The school is required to remove your child's name from the roll on the date they are informed of deregistration, and it is the school's duty to inform the Local Authority (so you do not need to do that).</p>
					<p>You will be contacted by the Local Authority once they have been informed of the deregistration. If you reside in Portsmouth, Portsmouth City Council have a system in place where the school will request to meet with the parent and a representative from the Local Authority. You are not obliged to attend the meeting and can decline their offer should you wish to. However, if you feel that this meeting would be useful to repair your family's relationship with school or to discuss options regarding home education, then you can accept the offer. Where you live (in Portsmouth, Hampshire, or elsewhere), will determine what kind of contact you will receive from the Local Authority. It is best to seek advice about how to respond in your local Facebook support group.</p>

					<h4>If your child is in a Special School</h4>
					<p>You will need consent from the Local Authority for your child to be deregistered. However, this consent cannot be reasonably refused. There are specialist groups available online for support in deregistering from a special school.</p>

					<h4>If your child is not yet of school age</h4>
					<p>You do not need to do anything. Parents are not currently required to inform the Local Authority of an intention to home educate. However, it is sometimes the case that if your child has attended nursery or preschool, then that establishment may inform the Local Authority of your intention to home educate.</p>
					<p>Should the Local Authority get in contact with you when your child has never attended school, then we still recommend that you contact your local Facebook support group for advice about the best way to respond.</p>
				</div>
			</details>
		</div>
	</div>
</section>

<section id="contact" class="section contact-section texture-overlay">
	<div class="container">
		<h2 class="section-heading">Get in touch</h2>
		<p class="section-intro contact-intro">
			Whether you are new to home education or simply looking to connect with other families in the area, we would be pleased to hear from you. You don’t need to have everything figured out before getting in touch — sometimes the first step is simply starting a conversation.
		</p>

		<div class="contact-grid">
			<div class="contact-card">
				<div class="contact-icon" aria-hidden="true">
					<svg viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg" width="32" height="32">
						<rect x="3" y="7" width="26" height="18" rx="3" stroke="currentColor" stroke-width="2" fill="none"/>
						<path d="M3 10l13 8 13-8" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" fill="none"/>
					</svg>
				</div>
				<h3 class="contact-label">Email</h3>
				<a href="mailto:info@pheg.org.uk" class="contact-value">info@pheg.org.uk</a>
			</div>


			<div class="contact-card">
				<div class="contact-icon" aria-hidden="true">
					<svg viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg" width="32" height="32">
						<path d="M16 3C11 3 7 7 7 12c0 7 9 17 9 17s9-10 9-17c0-5-4-9-9-9z" stroke="currentColor" stroke-width="2" fill="none"/>
						<circle cx="16" cy="12" r="3" stroke="currentColor" stroke-width="2" fill="none"/>
					</svg>
				</div>
				<h3 class="contact-label">Address</h3>
				<address class="contact-value" style="font-style: normal;">
					The HIVE Portsmouth Hub<br>
					22 Edinburgh Road<br>
					Portsmouth, PO1 1DH
				</address>
			</div>

			<div class="contact-card">
				<div class="contact-icon" aria-hidden="true">
					<svg viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg" width="32" height="32">
						<circle cx="16" cy="16" r="12" stroke="currentColor" stroke-width="2" fill="none"/>
						<path d="M12 16c0-2 2-4 4-4s4 2 4 4-2 4-4 4" stroke="currentColor" stroke-width="2" stroke-linecap="round" fill="none"/>
						<circle cx="22" cy="10" r="2" fill="currentColor"/>
					</svg>
				</div>
				<h3 class="contact-label">Social</h3>
				<a href="https://www.facebook.com/PortsmouthHEGroup" class="contact-value" target="_blank" rel="noopener noreferrer">Follow us on Facebook for updates and upcoming activities</a>
			</div>
		</div>
	</div>
</section>

<style>
	.hero {
		min-height: calc(100vh - var(--header-height));
		display: flex;
		align-items: center;
		position: relative;
		overflow: hidden;
		background:
			radial-gradient(ellipse 80% 60% at 20% 80%, rgba(91, 196, 192, 0.15) 0%, transparent 70%),
			radial-gradient(ellipse 60% 50% at 80% 20%, rgba(245, 237, 198, 0.6) 0%, transparent 70%),
			radial-gradient(ellipse 50% 40% at 50% 50%, rgba(91, 196, 192, 0.06) 0%, transparent 60%),
			var(--color-cream);
	}

	.hero-content {
		padding-block: var(--space-4xl);
		position: relative;
		z-index: 1;
	}

	.hero-badge {
		display: inline-flex;
		align-items: center;
		gap: var(--space-sm);
		padding: var(--space-xs) var(--space-lg);
		background: var(--color-warm-white);
		border: 1px solid var(--color-sand);
		border-radius: var(--radius-full);
		font-family: var(--font-heading);
		font-size: var(--text-sm);
		font-weight: 600;
		color: var(--color-text-muted);
		margin-bottom: var(--space-xl);
	}

	.hero-badge-dot {
		width: 8px;
		height: 8px;
		background: var(--color-sage);
		border-radius: 50%;
		display: inline-block;
	}

	.hero-title {
		font-size: clamp(var(--text-3xl), 6vw, var(--text-6xl));
		font-weight: 800;
		color: var(--color-forest-deep);
		max-width: 14ch;
		margin-bottom: var(--space-lg);
		line-height: 1.1;
	}

	.hero-subtitle {
		font-size: clamp(var(--text-lg), 2.5vw, var(--text-2xl));
		color: var(--color-text-muted);
		max-width: 40ch;
		line-height: var(--leading-snug);
		margin-bottom: var(--space-2xl);
	}

	.hero-actions {
		display: flex;
		flex-wrap: wrap;
		gap: var(--space-md);
	}

	.hero-decoration {
		position: absolute;
		top: 0;
		right: 0;
		bottom: 0;
		left: 0;
		pointer-events: none;
	}

	.hero-circle {
		position: absolute;
		border-radius: 50%;
		border: 2px solid;
		opacity: 0.12;
	}

	.hero-circle-1 {
		width: 300px;
		height: 300px;
		top: -60px;
		right: -80px;
		border-color: var(--color-navy);
	}

	.hero-circle-2 {
		width: 200px;
		height: 200px;
		bottom: 10%;
		right: 15%;
		border-color: var(--color-turquoise);
	}

	.hero-circle-3 {
		width: 120px;
		height: 120px;
		top: 30%;
		right: 8%;
		border-color: var(--color-terracotta-light);
		background: rgba(184, 82, 42, 0.04);
	}

	@media (max-width: 767px) {
		.hero-circle-1 {
			width: 180px;
			height: 180px;
			top: -40px;
			right: -60px;
		}

		.hero-circle-2 {
			width: 120px;
			height: 120px;
			bottom: 5%;
			right: 5%;
		}

		.hero-circle-3 {
			width: 80px;
			height: 80px;
			top: 20%;
			right: -10px;
		}
	}

	.about-section {
		background: var(--color-warm-white);
	}

	.about-content {
		max-width: var(--max-width-narrow);
	}

	.about-content p {
		color: var(--color-text-muted);
		font-size: var(--text-lg);
		line-height: var(--leading-relaxed);
	}

	.about-content p + p {
		margin-top: var(--space-xl);
	}

	.activities-section {
		background: var(--color-cream);
	}

	/* FAQ Section */
	.faq-section {
		background: var(--color-warm-white);
	}

	.faq-intro {
		margin-bottom: var(--space-2xl);
	}

	.faq-list {
		max-width: var(--max-width-narrow);
		display: flex;
		flex-direction: column;
		gap: var(--space-sm);
	}

	.faq-item {
		border: 1px solid var(--color-sand);
		border-radius: var(--radius-md);
		background: var(--color-cream);
		transition: border-color var(--duration-fast) var(--ease-out);
	}

	.faq-item[open] {
		border-color: var(--color-turquoise-light);
	}

	.faq-question {
		display: flex;
		align-items: center;
		justify-content: space-between;
		gap: var(--space-md);
		padding: var(--space-lg) var(--space-xl);
		font-family: var(--font-heading);
		font-size: var(--text-lg);
		font-weight: 700;
		color: var(--color-forest-deep);
		cursor: pointer;
		list-style: none;
		transition: color var(--duration-fast) var(--ease-out);
	}

	.faq-question::-webkit-details-marker {
		display: none;
	}

	.faq-question::marker {
		display: none;
		content: '';
	}

	.faq-question::after {
		content: '';
		width: 10px;
		height: 10px;
		border-right: 2.5px solid currentColor;
		border-bottom: 2.5px solid currentColor;
		transform: rotate(45deg);
		transition: transform var(--duration-normal) var(--ease-out);
		flex-shrink: 0;
		opacity: 0.4;
		margin-top: -4px;
	}

	.faq-item[open] > .faq-question::after {
		transform: rotate(-135deg);
		margin-top: 4px;
	}

	.faq-question:hover {
		color: var(--color-navy);
	}

	.faq-answer {
		padding: 0 var(--space-xl) var(--space-xl);
		color: var(--color-text-muted);
		line-height: var(--leading-relaxed);
		font-size: var(--text-base);
	}

	.faq-answer p + p {
		margin-top: var(--space-md);
	}

	.faq-answer ul {
		margin-top: var(--space-sm);
		margin-bottom: var(--space-sm);
		padding-left: var(--space-xl);
		list-style: disc;
	}

	.faq-answer li {
		margin-top: var(--space-xs);
		line-height: var(--leading-relaxed);
		color: var(--color-text-muted);
	}

	.faq-answer h4 {
		font-family: var(--font-heading);
		font-size: var(--text-base);
		font-weight: 700;
		color: var(--color-forest-deep);
		margin-top: var(--space-lg);
		margin-bottom: var(--space-sm);
	}

	.faq-answer > h4:first-child {
		margin-top: 0;
	}

	/* Contact Section */
	.contact-section {
		background: var(--color-parchment);
	}

	.contact-intro {
		margin-bottom: var(--space-2xl);
	}

	.contact-grid {
		display: grid;
		gap: var(--space-lg);
		grid-template-columns: 1fr;
	}

	@media (min-width: 640px) {
		.contact-grid {
			grid-template-columns: repeat(2, 1fr);
		}
	}

	@media (min-width: 1024px) {
		.contact-grid {
			grid-template-columns: repeat(3, 1fr);
		}
	}

	.contact-card {
		background: var(--color-warm-white);
		border-radius: var(--radius-lg);
		padding: var(--space-xl);
		border: 1px solid var(--color-sand);
		display: flex;
		flex-direction: column;
		gap: var(--space-sm);
	}

	.contact-icon {
		width: 44px;
		height: 44px;
		display: flex;
		align-items: center;
		justify-content: center;
		color: var(--color-forest);
		margin-bottom: var(--space-xs);
	}

	.contact-label {
		font-family: var(--font-heading);
		font-size: var(--text-sm);
		font-weight: 700;
		text-transform: uppercase;
		letter-spacing: 0.05em;
		color: var(--color-text-light);
	}

	.contact-value {
		font-size: var(--text-base);
		color: var(--color-text);
		line-height: var(--leading-relaxed);
	}

	a.contact-value {
		color: var(--color-forest);
		font-weight: 600;
	}

	a.contact-value:hover {
		color: var(--color-amber);
	}
</style>
