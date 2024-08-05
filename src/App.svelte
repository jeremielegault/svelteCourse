<script>
	// export let name;
	// export let age;
	let age = 5
	let name = 'Jeremie'

	function incrementAge() {
		age += 5
	}
</script>

<style>
	h1 {
		color: purple;
	}
</style>

<h1>Hello my name is {name} and I am {age} years old!</h1>
<button on:click="{incrementAge}">Change Age</button>
