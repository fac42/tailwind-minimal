<template>
	<main class="h-screen w-full bg-[coral]">
		<div class="container mx-auto h-full flex justify-center items-center">
			<HelloWorld msg="Hello World"/>
		</div>
	</main>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
	name: "App",
	components: {
		HelloWorld
	}
}
</script>

<style lang="postcss" scoped>
</style>
