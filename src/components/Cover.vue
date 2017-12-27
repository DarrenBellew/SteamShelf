
<template>
		<div class="cover-container">
			<div class="steam-icon"></div>
			<div class="cover">
			</div>
		</div>
</template>

<script>
	export default {
		name: 'cover',
		data() {
			return {};
		}
	}
</script>

<style scoped lang="scss">
		.cover-container {
			height: 13.2cm;
			width: 1.2cm;
			border-radius: 10px;

			.cover {
				height: 100%;
				width: 100%;
				background-image: url(http://cdn.edgecast.steamstatic.com/steam/apps/440/page_bg_generated_v6b.jpg);
				background-position-x: 50%;
				filter: contrast(160%) brightness(7) hue-rotate(180deg);

			}

			.steam-icon {
				background-color: black;
				background-size: contain;
				background-position: 50%;
				background-repeat: no-repeat;
				height: 1.2cm;
				width: 1.2cm;
				background-image: url(http://logo.kenh.net/logo/steam-icon.svg.png);
			}
		}

</style>
