<script>
	import '../app.pcss'
</script>

<!-- <div class="container border-2 border-blue-100"> -->
<!-- <slot name="sidebar" /> -->
<!-- <slot name="main" /> -->
<!-- </div> -->

<slot name="navigation">hi from nav</slot>

<!-- default -->
<slot />

<!-- <style>
	.container {
		@apply flex flex-col;
	}

	@media (min-width: 600px) {
		.container {
			@apply flex-row;
		}
	}
</style> -->
