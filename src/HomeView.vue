<template>

	<!-- Main section start -->
	<main-section></main-section>
	<!-- Main section end -->

	<!-- About section start -->
	<about-section></about-section>
	<!-- About section end -->

	<!-- Services section start -->
	<service-section></service-section>
	<!-- Services section end -->

	<!-- Pelife section start -->
	<pelife-section></pelife-section>
	<!-- Pelife section end -->

	<!-- Portfolio section start -->
	<portfolio-section></portfolio-section>
	<!-- Portfolio section end -->


	<!-- Contact section start -->
	<contact-section></contact-section>
	<!-- Contact section end -->

</template>

<script>
import 'animate.css';

import MainSection from '@/sections/MainSection.vue';
import AboutSection from '@/sections/AboutSection.vue';
import ServiceSection from '@/sections/ServiceSection.vue';
import PelifeSection from '@/sections/PelifeSection.vue';
import PortfolioSection from '@/sections/PortfolioSection.vue';
import ContactSection from '@/sections/ContactSection.vue';

export default {
	components: {
		MainSection,
		AboutSection,
		ServiceSection,
		PelifeSection,
		PortfolioSection,
		ContactSection,
	}
}
</script>

<style scoped></style>