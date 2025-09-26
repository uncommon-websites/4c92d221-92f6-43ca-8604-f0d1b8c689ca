<script lang="ts">
	// Components
	import Summary from "$lib/components/layout/Summary.svelte";
	import Features from "$lib/components/layout/Features.svelte";
	import Testimonials from "$lib/components/layout/Testimonials.svelte";
	import CallToAction from "$lib/components/layout/CallToAction.svelte";
	import AboutTeaser from "$lib/components/layout/AboutTeaser.svelte";
	import LogoScroller from "$lib/components/layout/LogoScroller.svelte";
	import Hero from "$lib/components/layout/hero-sections/Hero.svelte";
</script>

<Hero
	title="Make your website accessible. Stay compliant."
	subtitle="Fix ADA issues fast without the complexity."
	imageSrc="/generated/image-a-professional-digital-marketing-manager.webp"
	centered={false}
/>
<LogoScroller 
	label="Trusted by industry leaders"
	logoUrls={[
		'https://cdn.brandfetch.io/shopify.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/squarespace.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/etsy.com/w/400/h/400/logo',
		'https://cdn.brandfetch.io/bigcommerce.com/w/400/h/400/logo'
	]}
/>

<Summary
	generating
	title="What we do"
	text="Our technology delivers measurable results through secure, adaptable solutions that directly increase productivity and drive growth."
/>

<Testimonials
	testimonials={[
		{
			name: "Maria Rodriguez",
			position: "Digital Marketing Manager",
			company: "Crafted Home Co.",
			quote:
				"WebAbility saved us $15,000 in legal consultation fees and got our site compliant in just 2 weeks.\nOur conversion rate actually increased 12% after implementing their accessibility features.",
			image: "/generated/image-professional-headshot-of-a-confident-his.webp"
		},
		{
			name: "Darius Thompson",
			position: "E-commerce Director",
			company: "Urban Athletic Gear",
			quote:
				"Before WebAbility, we were spending 40 hours per month on manual accessibility checks.\nNow it takes 2 hours, and we've avoided two potential ADA lawsuits that could have cost us $50,000 each.",
			image: "/generated/image-professional-headshot-of-a-confident-bla.webp"
		},
		{
			name: "Jenny Chen",
			position: "Website Owner",
			company: "Bloom Beauty Studio",
			quote:
				"The automated scanning caught 147 issues we never knew existed - issues that put us at serious legal risk.\nImplementing WebAbility was 80% cheaper than hiring an accessibility consultant and infinitely faster.",
			image: "/generated/image-professional-headshot-of-a-confident-asi.webp"
		}
	]}
/>

<Features
	title="Make your website accessible"
	subtitle="Comprehensive compliance solutions designed for your success"
	features={[
		{
			title: "Automated accessibility scanning",
			description: "Instantly identify and prioritize ADA/WCAG violations across your entire website. Our AI-powered scanner detects issues that manual reviews miss.",
			imageSrc: "/generated/image-1-a-group-of-professionals-gathered-arou.webp"
		},
		{
			title: "Expand your customer reach",
			description: "Unlock access to 61 million Americans with disabilities and improve SEO rankings. Accessible websites convert 23% better than non-compliant sites.",
			imageSrc: "/generated/image-2-a-diverse-group-of-people-in-a-cozy-ca.webp"
		},
		{
			title: "Legal protection guarantee",
			description: "Shield your business from ADA lawsuits with our compliance certification and legal support. We've helped 1,000+ businesses avoid costly litigation.",
			imageSrc: "/generated/image-3-two-business-professionals-shaking-han.webp"
		},
		{
			title: "5-minute setup process",
			description: "No complex integrations or developer knowledge required. Simply add our lightweight widget and start fixing accessibility issues immediately.",
			imageSrc: "/generated/image-4-a-person-in-a-home-office-setting-smil.webp"
		},
		{
			title: "Real-time monitoring",
			description: "Continuous compliance tracking with instant alerts when new issues arise. Maintain accessibility standards as your website evolves.",
			imageSrc: "/generated/image-5-a-team-of-colleagues-standing-together.webp"
		},
		{
			title: "Expert support team",
			description: "Get personalized guidance from accessibility specialists who understand e-commerce challenges. Available when you need us most.",
			imageSrc: "/generated/image-6-a-friendly-customer-support-team-at-a-.webp"
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
