<template>
	<div class="hello">
		<h1>{{ msg }}</h1>
		<button @click="hello">Alert me</button>
	</div>
</template>

<script>

export default 
{
	name: "HelloWorld",

	props: {
		msg: String
	},

	methods: {
		hello: () => {
			alert("Hello guys its Allan")
		},
	}
};

</script>

<style scoped>
h1 { color: red;}
</style>
