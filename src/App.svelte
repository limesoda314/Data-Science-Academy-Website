<script>

	// Constant throughout all pages
	import Navigation from "./Components/Navigation.svelte";

	// Import pages necessary to route our links (i.e. /home, /about, etc)
	import HomePage from "./routes/HomePage.svelte";
	import AboutPage from "./routes/AboutPage.svelte";
	import ContactPage from "./routes/ContactPage.svelte";
	import ShowCasePage from "./routes/ShowCasePage.svelte";
	import TeamPage from "./routes/TeamPage.svelte"; 
	import Footer from "./Components/Footer.svelte";

	// Takes care of the routing
	import { Router, Route } from "svelte-routing";

	export let url = "";

</script>

<svelte:head> 
	<title>DSA at UCR</title>
</svelte:head>

<Router url="{url}">
	<Navigation/>
	<div>
		<Route path="/home"><HomePage /></Route>
		<Route path="/about"><AboutPage /></Route>
		<Route path="/contact"><ContactPage /></Route>
		<Route path="/people"><TeamPage/></Route>
		<Route path="/showcase"><ShowCasePage /></Route>
		<Route path="/*"><HomePage /></Route>
		<Route path="/"><HomePage /></Route>
	</div>
	<Footer/>
</Router>