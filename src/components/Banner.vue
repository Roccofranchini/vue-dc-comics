<template>
	<section id="banner">
		<div class="container">
			<div class="row">
				<div class="col-2">
					<img src="../assets/img/buy-comics-digital-comics.png" alt="" />
					<span>DIGITAL COMICS</span>
				</div>
				<div class="col-2">
					<img src="../assets\img\buy-comics-merchandise.png" />
					<span>DC MERCHANDISE</span>
				</div>
				<div class="col-2">
					<img src="../assets/img/buy-comics-subscriptions.png" alt="" />
					<span>SUBSCRIPTION</span>
				</div>
				<div class="col-2">
					<img src="../assets/img/buy-comics-shop-locator.png" alt="" />
					<span>COMIC SHOP LOCATOR</span>
				</div>
				<div class="col-2">
					<img src="../assets/img/buy-dc-power-visa.svg" alt="" />
					<span>DC POWER VISA</span>
				</div>
			</div>
		</div>
	</section>
</template>

<script>
export default {
	name: "Banner",
};
</script>

<style scoped lang="scss">
#banner {
	height: 120px;
	background-color: #0282f9;
	position: relative;
	z-index: 1;
}

.container {
	height: 100%;
}

.row {
	height: 100%;
}

.col-2 {
	width: 20%;
	height: 100%;
	display: flex;
	justify-content: center;
	align-items: center;
	img {
		height: 60px;
		max-width: 60px;
	}
	span {
		color: white;
		margin-left: 20px;
	}
}
</style>
