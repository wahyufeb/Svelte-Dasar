<script>
	import Name from "./Name.svelte"
	import Menu from "./Menu.svelte";

	let name = "Alex"

	const menu = {
		nama:"Mie Ayam",
		harga:10000
	}
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
		<li>Pricing</li>
	</ul>
</header>
<main>
	<Name {name}/>

	<h3>Nama Menu : {menu.nama}</h3>
	<h3>Harga : {menu.harga}</h3>

	<Menu {menu}/>
</main>

