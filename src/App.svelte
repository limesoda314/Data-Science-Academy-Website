<script>

	// Constant throughout all pages
	import Navigation from "./Components/Navigation.svelte";

	// Import pages necessary to route our links (i.e. /home, /about, etc)
	import HomePage from "./routes/HomePage.svelte";
	import AboutPage from "./routes/AboutPage.svelte";
	import ContactPage from "./routes/ContactPage.svelte";
	import PeoplePage from "./routes/PeoplePage.svelte";
	import ShowCasePage from "./routes/ShowCasePage.svelte";

	// Takes care of the routing
	import { Router, Route } from "svelte-routing";

</script>

<svelte:head> 
	<title>DSA at UCR</title>
</svelte:head>

<Router>
	<Navigation/>
	<div>
		<Route path="/"><HomePage /></Route>
		<Route path="/home"><HomePage /></Route>
		<Route paht="/about"><AboutPage /></Route>
		<Route path="/contact"><ContactPage /></Route>
		<Route path="/people"><PeoplePage /></Route>
		<Route path="/showcase"><ShowCasePage /></Route>
	</div>
</Router>