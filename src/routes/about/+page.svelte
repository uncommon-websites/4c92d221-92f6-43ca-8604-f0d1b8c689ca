<script lang="ts">
	// Components
	import CallToAction from "$lib/components/layout/CallToAction.svelte";

	// Icons
	import StakeholderGrid from "$lib/components/layout/StakeholderGrid.svelte";
	import Story from "./Story.svelte";
	import SecondaryHero from "$lib/components/layout/hero-sections/SecondaryHero.svelte";
	import Culture from "$lib/components/layout/Culture.svelte";

	// Constants
	const values = [
		{
			title: "Inclusion first",
			description: "Every person deserves equal access to digital experiences. We build solutions that open doors, not create barriers."
		},
		{
			title: "Simplicity over complexity",
			description: "Accessibility shouldn't require a PhD. We make compliance straightforward so businesses can focus on what they do best."
		},
		{
			title: "Empowerment through access",
			description: "When websites work for everyone, businesses grow and communities thrive. We're here to make that happen."
		}
	];
</script>

<SecondaryHero
	title="Making the web accessible"
	subtitle="for everyone"
	imageSrc="/generated/image-a-diverse-group-of-professionals-gathere.webp"
/>

<!-- Story Section -->
<Story
	paragraphs={[
		"We founded WebAbility.io with a simple belief: every person deserves equal access to digital experiences. Too many businesses struggle with complex, expensive accessibility solutions that don't actually work.",
		"Traditional accessibility tools are overwhelming and costly. Small businesses get stuck choosing between compliance and growth. We knew there had to be a better way.",
		"That's why we built WebAbility.io—accessibility compliance that's simple, affordable, and actually effective. No PhD required, no developer needed, just real results that protect your business and serve your customers.",
		"When websites work for everyone, amazing things happen. Businesses reach new customers, avoid legal risks, and build stronger communities. We're here to make accessibility achievable for every business, no matter their size or technical expertise."
	]}
/>

<!-- Our Culture Section -->
<Culture {values} />

<!-- StakeholderGrid Section -->
<StakeholderGrid
	stakeholderType="team"
	title="Meet our founder."
	subtitle="Leading the mission for digital accessibility."
	stakeholders={[
		{
			name: "Sidharth Nayyar",
			position: "CTO & Founder",
			bio: "Technology leader passionate about making the web accessible to everyone.",
			image: "/generated/image-professional-headshot-of-an-indian-man-i.webp"
		}
	]}
/>

<!-- CTA Section -->
<CallToAction
	title="Ready to make your site accessible?"
	subtitle="Start your compliance journey today"
	description="Stop worrying about legal risks and start reaching more customers. With WebAbility.io, accessibility compliance is finally simple, affordable, and designed for businesses like yours."
	imageSrc="/generated/image-a-business-professional-with-a-friendly-.webp"
/>
