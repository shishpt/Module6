<script setup>

</script>

<template>
	<header class="absolute inset-x-0 top-0 z-50 bg-black-800">
		<nav class="flex items-center justify-between p-6 lg:px-8">
			<div class="flex items-center flex-shrink-0 text-white mr-6 lg:flex-1">
				<NuxtLink to ="/">
					<span class="text-green-700 font-logo text-3x1">
						Vegan Voyage
					</span>
				</NuxtLink>
			</div>
			<div class="hidden lg:flex lg:gap-x-36 text-lg font-semibold leading-6 text-green-700">
				<nuxt-link to="/">Mission</nuxt-link>
			</div>
			<div class="hidden lg:flex lg:gap-x-36 text-lg font-semibold leading-6 text-green-700">
				<nuxt-link to="/">How It Works</nuxt-link>
			</div>
			<div class="hidden lg:flex lg:gap-x-12 text-lg font-semibold leading-6 text-green-700">
				<nuxt-link to="/restaurants">Restaurants</nuxt-link>
			</div>
			<div class="hidden lg:flex lg:gap-x-12 text-lg font-semibold leading-6 text-green-700 border rounded-t: border-spacing-4 border-green-500">
				Sign-In
			</div>
			<div class="hidden lg:mt-0 lg:flex lg:gap-x-12 text-lg font-semibold leading-6 text-green-700">
				Sign-Up
			</div>
		</nav>
	</header>
</template>

}
