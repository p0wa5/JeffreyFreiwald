
<script>
    import himage from "../../static/treetoppurple.png";
    import MyPicture from "../../static/mypic.jpg";
    import linkedIn from "../../static/linkedin-logo.png";
    import github from "../../static/GitHub-Mark-Light-120px-plus.png";
</script>

<div class="w-full md:w-10/12 mx-auto">
    <div class="w-full h-72 my-16 flex items-center">
        <img class="animate-pulse sm:h-72 w-72 mx-auto" src={himage} alt="treeImageddd" />
    </div>

    <div class="bg-gray-800 bg-opacity-25 w-full rounded-lg flex md: bg-gray-800 bg-opacity-25  h-16  rounded-lg flex items-center">
        <p class="text-sm text-center text-white mx-auto sm:text-xl xl:text-2xl">Hello, I am an apprentice in software development based in Germany</p>
    </div>

    <div class="mt-12 md:flex w-full h-28 mt-6">
        <div class="w-10/12 text-white flex items-center">
            <div>
                <h1 class="mt-10 text-xl font-bold md:text-2xl font-bold xl:text-3xl xl:mt-20">Jeffrey Freiwald</h1>
                <p class="mt-3 text-sm sm:text-xl xl:text-2xl">Software development apprentice</p>
            </div>
            <div>
                <!-- selfie or something -->
            </div>
        </div>
    </div>

   
    <div class="text-white mt-20 xl:mt-36">
        <span class="font-bold text-xl md:text-2xl border-b-2 xl:text-3xl">Skills</span>
        <p class="text-sm mt-3 sm:text-xl xl:text-2xl">As an junior frontend developer, I started by learning the basic concepts of JavaScript followed by TypeScript, HTML, and CSS. I also use Frameworks like SvelteKit, Angular, Bootstrap and Tailwind CSS to build applications or websites.</p>
    </div>

    <div class="h-20 mt-20 flex">
        <div class="w-10 h-10 flex items-center">
            <div class="w-8 h-8 mx-auto">
                <a href="https://github.com/p0wa5" target="_blank">
                    <img src={github} alt="github">
                </a>
            </div>
        </div>
        <div class="ml-2 w-10 h-10">
            <a href="https://www.linkedin.com/in/jeffrey-freiwald-576055233/" target="_blank">
                <img class="object-cover" src={linkedIn} alt="linked-in">
            </a>
        </div>
    </div>
</div>
