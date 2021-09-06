<template>
	<header>
		<div class="container">
			<div class="row">
				<div class="col-50">
					<img src="../assets/img/dc-logo.png" alt="" />
				</div>
				<div class="col-50">
					<ul>
						<li><a href="">CHARACTERS</a></li>
						<li><a href="" class="active">COMICS</a></li>
						<li><a href="">MOVIES</a></li>
						<li><a href="">TV</a></li>
						<li><a href="">GAMES</a></li>
						<li><a href="">COLLECTIBLES</a></li>
						<li><a href="">VIDEOS</a></li>
						<li><a href="">FANS</a></li>
						<li><a href="">NEWS</a></li>
						<li><a href="">SHOP</a></li>
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
