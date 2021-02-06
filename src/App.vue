<template>
	<h1>discord image maker</h1>
	<form action="https://python357-image-generator.herokuapp.com/create?" method='get'>
		<input 
			type="text"
			name="username"
			id="username"
			placeholder='discord username'
			>
		<br>
		<input type='radio' id='nickname' name='type' value='nickname'>
		<label for="nickname">nickname</label>
		<input type='radio' id='status' name='type' value='status'>
		<label for="status">status</label>
		<input type="radio" name="type" id="both" value='both'>
		<label for="both">both</label>
		<br>
		<input type="submit" value="submit">
	</form>
</template>

<script>

export default {
  name: 'App',
}
</script>

<style>

</style>
