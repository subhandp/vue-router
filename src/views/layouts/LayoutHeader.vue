<template>
      <div>
          <header class="w-full px-6 bg-blue-300">
			<div class="container mx-auto max-w-4xl md:flex justify-between items-center">
				<a href="/" class="block py-6 w-full text-center md:text-left md:w-auto text-gray-dark no-underline flex justify-center items-center">
					My Private Blog
				</a>
				<div class="w-full md:w-auto text-center md:text-right">
					<!-- Login / Register -->
				</div>
			</div>
		</header>
      </div>
</template>

<script>
export default {
  name: "LayoutHeader"
};
</script>

<style>

a:hover {
  @apply  text-red-600;
}

 a.router-link-active {
  @apply text-red-600;
}
</style>
