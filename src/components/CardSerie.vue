<template>
	<div class="col">
		<img :src="serie.thumb" alt="" />
		<figcaption>{{ serie.series }}</figcaption>
	</div>
</template>

<script>
export default {
	name: "CardSerie",
	props: ["serie"],
};
</script>

<style scoped lang="scss">
figcaption {
	color: white;
	margin: 10px 0;
	text-align: center;
}

.col {
	flex-basis: calc(100% / 6);
	padding: 0 10px;
	display: flex;
	flex-direction: column;
	align-items: center;
	img {
		width: 60%;
	}
}
</style>
