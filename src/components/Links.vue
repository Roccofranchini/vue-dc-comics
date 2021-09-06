<template>
	<section id="links">
		<div class="container">
			<div class="row">
				<div class="col-50">
					<div class="col">
						<ul>
							<h4>DC GAMES</h4>
							<li>Characters</li>
							<li>Comics</li>
							<li>Movies</li>
							<li>TV</li>
							<li>Games</li>
							<li>Videos</li>
							<li>News</li>
						</ul>
						<ul>
							<h4>SHOP</h4>
							<li>Shop DC</li>
							<li>Shop DC Collectibles</li>
						</ul>
					</div>
					<div class="col">
						<ul>
							<h4>DC</h4>
							<li>Terms of use</li>
							<li>Privacy policy</li>
							<li>Ad choiches</li>
							<li>Advertising</li>
							<li>Jobs</li>
							<li>Subscription</li>
							<li>Talent Workshops</li>
							<li>CPSC Certificates</li>
							<li>Ratings</li>
							<li>Shop Help</li>
							<li>Contact Us</li>
						</ul>
					</div>
					<div class="col">
						<ul>
							<h4>SITES</h4>
							<li>DC</li>
							<li>MAD Magazine</li>
							<li>DC kids</li>
							<li>DC Universe</li>
							<li>DC Power Visa</li>
						</ul>
					</div>
				</div>
				<div class="col-50">
					<img src="../assets/img/dc-logo-bg.png" alt="" />
				</div>
			</div>
		</div>
	</section>
</template>

<script>
export default {
	name: "Links",
};
</script>

<style>
#links {
	background-image: url(../assets/img/footer-bg.jpg);
	padding: 50px 0;
	position: relative;
}
.row > .col-50 {
	display: flex;
}

.col-50 img {
	position: absolute;
	top: -100px;
}

.col {
	width: calc(100% / 3);
}

ul {
	color: white;
	font-weight: 600;
}

ul h4 {
	margin-top: 20px;
	margin-bottom: 15px;
}

li {
	color: gray;
	font-weight: 400;
	padding: 5px 0;
	font-size: 15px;
}
</style>
