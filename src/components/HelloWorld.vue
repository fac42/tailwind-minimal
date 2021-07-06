<template>
  <div class="">
    <h1 class="text-4xl text-white">{{ msg }} 👋🏼</h1>
  </div>
</template>

<script>
export default {
	name: "HelloWorld",
	props: {
		msg: String
	}
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="postcss" scoped>
</style>
