<template>
	<header>
		<div class="container">
			<div class="row">
				<div class="col-50">
					<img src="../assets/img/dc-logo.png" alt="" />
				</div>
				<div class="col-50">
					<ul>
						<li v-for="(nav, index) in navs" :key="index">
							<a href="" :class="isActive(nav)">{{ nav.text }}</a>
						</li>
					</ul>
				</div>
			</div>
		</div>
	</header>
</template>

<script>
export default {
	name: "Header",
	props: {},
	data() {
		return {
			navs: [
				{
					text: "Characters",
					url: "#",
					current: false,
				},
				{
					text: "Comics",
					url: "#",
					current: true,
				},
				{
					text: "Movies",
					url: "#",
					current: false,
				},
				{
					text: "TV",
					url: "#",
					current: false,
				},
				{
					text: "Games",
					url: "#",
					current: false,
				},
				{
					text: "Collectibles",
					url: "#",
					current: false,
				},
				{
					text: "Videos",
					url: "#",
					current: false,
				},
				{
					text: "Fans",
					url: "#",
					current: false,
				},
				{
					text: "News",
					url: "#",
					current: false,
				},
				{
					text: "Shop",
					url: "#",
					current: false,
				},
			],
		};
	},
	computed: {},
	methods: {
		isActive(nav) {
			return nav.current === true ? "active" : "";
		},
	},
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
header {
	height: 100px;
}

.container {
	height: 100%;
}

.row {
	align-items: center;
	height: 100%;
}

img {
	height: 60px;
}

ul {
	display: flex;
	font-weight: 600;
}

li {
	padding: 0 10px;
	font-size: 12px;
}

li a {
	padding: 35px 0;
}

li a:hover {
	color: #0282f9;
}

.active {
	color: #0282f9;
	border-bottom: 8px solid #0282f9;
}
</style>
