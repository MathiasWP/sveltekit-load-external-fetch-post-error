<script context="module" >
	export const load = async function ({ fetch }) {
		await fetch('https://example.com', {
			method: 'POST',
			body: JSON.stringify({
				foo: 'bar'
			}),
			headers: {
				'Content-Type': 'application/json'
			}
		});

        return {}
	};
</script>

Hi!
