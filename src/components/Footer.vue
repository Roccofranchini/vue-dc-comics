<template>
	<footer>
		<div class="container">
			<div class="row">
				<div class="sing-up">
					<a href="">SING-UP NOW!</a>
				</div>
				<div>
					<div class="social row">
						<a href=""> FOLLOW US</a>
						<img src="../assets/img/footer-facebook.png" alt="" />
						<img src="../assets/img/footer-twitter.png" alt="" />
						<img src="../assets/img/footer-youtube.png" alt="" />
						<img src="../assets/img/footer-pinterest.png" alt="" />
						<img src="../assets/img/footer-periscope.png" alt="" />
						<img src="" alt="" />
					</div>
				</div>
			</div>
		</div>
	</footer>
</template>

<script>
export default {
	name: "footer",
};
</script>

<style scoped lang="scss">
footer {
	height: 100px;
	background-color: #303030;
	position: relative;
	z-index: 1;
}

footer img {
	height: 30px;
	margin: 0 5px;
}

.container {
	height: 100%;
}

.row {
	justify-content: space-between;
	align-items: center;
	height: 100%;
}

.sing-up a {
	color: white;
	padding: 8px;
	border: 3px solid #0282f9;
	display: flex;
	align-items: center;
	font-size: 14px;
	font-weight: bold;
}

.social a {
	color: #0282f9;
	font-weight: bold;
	margin: 0 30px;
}
</style>
