<script>
    import Nav from "../components/nav.svelte"
    import Project from "../components/projectContainer.svelte"
    import svelteKitImg from "../../static/sveltekitimg.png";
    import exampleImg from "../../static/placeholder.png";
    import svelteImg from "../../static/sveltekitimg.png";
    import threeJsImg from "../../static/threejs.png";
</script>


<div class="w-7/12 mx-auto">
    <Nav />
</div>

<div class="w-full sm:w-7/12 mx-auto mt-60">
    <div class="w-full mt-32 h-auto">
        <Project heading={"Portfolio with SvelteKit"} projdesc={"This project is about building a simple portfolio website with Sveltekit and Tailwind CSS"} repoLink={"https://www.google.com/"} imgPath={svelteKitImg}/>
        <Project heading={"Experimenting with threejs"} projdesc={"In this project I have created my first Scene with three.js."} repoLink={"https://www.google.com/"} imgPath={threeJsImg}/>
    </div>
</div>
