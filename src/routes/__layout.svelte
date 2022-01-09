<script context="module">
	export async function load(data) {
		return {
			props: {
				data
			}
		};
	}
</script>

<script>
	export let data;
	console.log({ data });
</script>

<h2>1</h2>

<pre>
  {JSON.stringify(data, null, 2)}
</pre>

<slot />
