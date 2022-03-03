<script>
    import himage from "../../static/placeholder.png"
    import svelteImg from "../../static/sveltekitimg.png"
    export let heading;
    export let projdesc;
    export let imgPath;


</script>

<div class="shadow-lg mt-40 w-82  mx-auto h-136 xl:flex xl:items-center xl:h-96 xl:w-10/12">

    <!-- Div two -->
    <div class="flex items-center w-2/3 mx-auto h-1/2 lg:w-1/3 xl:mr-10 xl:h-2/3">
       <img class="object-cover h-3/4 w-full xl:w-3/3 xl:mx-auto xl:h-4/4 xl:object-none" alt="lol" src={imgPath}>
    </div>

    <!-- Div One -->
    <div class="h-1/2 flex w-3/4 mx-auto items-center">
        <div class="">
            <h1 class="text-white text-3xl font-bold">{heading}</h1>
            <p class="text-base mt-2 text-blog text-white sm:text-xl md:text-xl lg:text-2xl">{projdesc}</p>
            <div class="w-20 h-10 rounded text-center mt-4 font-bold text-xl text-white bg-gray-700 bg-opacity-25 flex items-center hover:bg-gray-600 bg-opacity-25">
                <a class="mx-auto" href={repoLink} target="_blank">
                    <span class="">GitHub</span>
                </a>
            </div>
        </div>
    </div>
</div>
