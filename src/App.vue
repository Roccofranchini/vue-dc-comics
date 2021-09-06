<template>
	<div id="app">
		<Header />
		<Jumbo />
		<Banner />
		<Links />
		<Footer />
	</div>
</template>

<script>
import Header from "./components/Header.vue";
import Jumbo from "./components/Jumbo.vue";
import Banner from "./components/Banner.vue";
import Links from "./components/Links.vue";
import Footer from "./components/Footer.vue";

export default {
	name: "App",
	components: {
		Header,
		Jumbo,
		Banner,
		Links,
		Footer,
	},
};
</script>

<style lang="scss">
@import "@/assets/scss/style.scss";
</style>
