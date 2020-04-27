<template>
  <div>
    <h1>About DadJokes</h1>
    <p>This is an app that displays corny dad jokes</p>
  </div>
</template>

<script>
export default {
	head() {
		return {
			title: 'About the app',
			meta: [
				{
					hid: 'description',
					name: 'description',
					content: 'Best place for corny bad jokes'
				}
			]
		}
	}
};
</script>

<style>
</style>