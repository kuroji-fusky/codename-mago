<template>
	<footer>
		<div class="container">
			<span id="copyright">
				&copy; {{ new Date().getFullYear() }} Kuroji Fusky
			</span>
		</div>
	</footer>
</template>

<style lang="scss" scoped>
.container {
	@apply p-6 mx-auto max-w-screen-2xl;
}
</style>