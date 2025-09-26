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
		}
	]}
/>

<Features
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
		}
	]}
/>
<AboutTeaser generating />
<CallToAction generating />
