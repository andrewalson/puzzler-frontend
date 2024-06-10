<script lang="ts">
	const addUser = () => {
		window.fetch('http://localhost:8080/user', {
			method: 'POST'
		});
		alert('User added');
	};
</script>

<button on:click={addUser}>Create Account</button>
