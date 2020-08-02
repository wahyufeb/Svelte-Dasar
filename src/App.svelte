<script>
	import Name from "./Name.svelte"
</script>

<style>
	header{
		background-color: red;
		padding: 10px;
	}

	ul {
		list-style: none;
	}

	li{
		display: inline-block
	}

</style>

<header>
	<ul>
		<li>Home</li>
		<li>Product</li>
	</ul>
</header>
<main>
	<Name/>
</main>

