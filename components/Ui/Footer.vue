<template>
	<div>
		<!-- This example requires Tailwind CSS v2.0+ -->
		<footer class="bg-bgblue">
			<div class="max-w-7xl mx-auto py-12 px-4 overflow-hidden sm:px-6 lg:px-8">
				<nav class="-mx-5 -my-2 flex flex-wrap justify-center" aria-label="Footer">
					<div class="px-5 py-2">
						<nuxt-link to="privacy" class="text-base text-gray-500 hover:text-gray-900">
							Privacy policy
						</nuxt-link>
					</div>
					<!-- <div class="px-5 py-2">
						<a href="#" class="text-base text-gray-500 hover:text-gray-900">
							Terms and conditions
						</a>
					</div> -->
				</nav>
				<p class="mt-8 text-center text-base text-gray-400">&copy; {{ new Date().getFullYear() }} Welikedaily | Build in Munich Germany</p>
			</div>
		</footer>
	</div>
</template>

<script>
export default {}
</script>

<style lang="postcss" scoped></style>
