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
	title="What we do"
	text="WebAbility.io helps e-commerce sites become accessible to everyone — including users with disabilities — while reducing legal risk and increasing your reach. Our lightweight, AI-driven widget handles accessibility so you don't have to."
/>

<Testimonials
	testimonials={[
		{
<<<<<<< HEAD
			name: "Priya Mehta",
			position: "Digital Marketing Manager",
			company: "StyleCraft E-commerce",
			quote:
				"WebAbility saved us $45,000 in potential legal fees and 3 months of development time.\nWe went from 127 accessibility violations to full WCAG compliance in just 2 weeks.",
			image: "/generated/image-professional-headshot-of-a-confident-ind.webp"
		},
		{
			name: "Marcus Thompson",
			position: "E-commerce Director",
			company: "Urban Threads",
			quote:
				"Our conversion rate increased 23% after implementing WebAbility.\nThe risk of ADA lawsuits was keeping me up at night - now I sleep soundly knowing we're protected.",
			image: "/generated/image-professional-headshot-of-a-confident-bla.webp"
		},
		{
			name: "Carmen Rodriguez",
			position: "Website Operations Director",
			company: "Artisan Marketplace",
			quote:
				"Installation took 15 minutes, not 15 weeks like our previous solution.\nWe're reaching 12% more customers and avoiding the $150,000 compliance audit we were dreading.",
			image: "/generated/image-professional-headshot-of-a-confident-his.webp"
=======
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
>>>>>>> 3c0abd047b6fc1673ef2b2948d82c6d3639debe6
		}
	]}
/>

<Features
<<<<<<< HEAD
	title="Why choose WebAbility.io"
	subtitle="Built for small businesses who need compliance without complexity"
	features={[
		{
			title: "Automated compliance monitoring",
			description: "Get continuous ADA/WCAG scanning and instant alerts when issues arise. Never worry about missing accessibility problems that could lead to legal trouble.",
			imageSrc: "/generated/image-a-business-professional-in-a-modern-offi.webp"
		},
		{
			title: "Expand your customer reach",
			description: "Make your site accessible to 61 million Americans with disabilities and boost your SEO rankings. Inclusive design drives both revenue and brand reputation.",
			imageSrc: "/generated/image-a-group-of-diverse-customers-including-p.webp"
		},
		{
			title: "Legal protection you can trust",
			description: "Shield your business from costly ADA lawsuits with comprehensive compliance reports and documentation. Sleep better knowing you're protected.",
			imageSrc: "/generated/image-a-close-up-of-a-legal-document-on-a-tidy.webp"
		},
		{
			title: "Simple implementation, powerful results",
			description: "Get started in under 10 minutes with our one-line integration. No technical expertise required—just add our code and watch accessibility issues disappear.",
			imageSrc: "/generated/image-a-diverse-team-in-a-casual-meeting-room-.webp"
		},
		{
			title: "Cost-effective for small businesses",
			description: "Skip expensive accessibility audits and developer hours. Our automated solution costs 90% less than traditional compliance methods while delivering better results.",
			imageSrc: "/generated/image-a-small-business-owner-in-a-bright-works.webp"
		},
		{
			title: "Expert support when you need it",
			description: "Access real accessibility experts, not chatbots. Get personalized guidance and quick resolutions from our team who understands small business challenges.",
			imageSrc: "/generated/image-a-professional-support-team-in-a-cheerfu.webp"
=======
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
>>>>>>> 3c0abd047b6fc1673ef2b2948d82c6d3639debe6
		}
	]}
/>
<AboutTeaser generating />
<CallToAction 
	title="Don't wait for a lawsuit to find out you're not compliant"
	subtitle="Join 1,000+ businesses that chose protection over risk"
	description="ADA lawsuits have increased 320% since 2018, with average settlements of $75,000. While competitors charge thousands and take months, WebAbility gets your site compliant in under 24 hours for a fraction of the cost. Your business deserves better than expensive legal fees and lost customers."
	imageSrc="/generated/image-a-professional-e-commerce-manager-smilin.webp"
	callsToAction={[
		{
			href: "/get-started",
			label: "Start free compliance scan",
			variant: "primary"
		},
		{
			href: "/contact",
			label: "Talk to compliance expert",
			variant: "secondary"
		}
	]}
/>
