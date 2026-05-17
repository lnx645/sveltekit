<script lang="ts">
	import axios from "axios";
	import { onMount } from "svelte";

	onMount(()=>{
		axios.get("/login")
	})
</script>

<h2>Selamat datang di invitnesia.com</h2>
