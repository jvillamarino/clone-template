<script>
import AboutInfo from "../components/AboutInfo.svelte";
import Contact from "../components/Contact.svelte";

import Header from "../components/Header.svelte";
import Portafolio from "../components/Portafolio.svelte";
import Services from "../components/Services.svelte";
import About from "./about.svelte";

</script>

<svelte:head>
	<title>Sapper project template</title>
	<script src="https://use.fontawesome.com/releases/v5.15.1/js/all.js" crossorigin="anonymous"></script>
</svelte:head>


<Header />
<AboutInfo/>
<Services />
<Portafolio />
<Contact />



