<svelte:head>
	<title>James Vansteenkiste</title>
  <meta name="Description" content="Learn more about me. This is my resume in webpage format.">
</svelte:head>

<div class="relative" style="height: 500px">
  <img src="./computer_background.webp" class="w-full h-full object-cover absolute z-0" alt="">
  <div class="relative h-full flex items-end pb-10">
    <div class="flex-1 text-center">
      <h1 class="text-4xl text-white font-medium">James Vansteenkiste</h1>
      <h2 class="text-2xl text-white">Software Developer</h2>
    </div>
  </div>
</div>

<section class="py-10">
  <div class="text-center">
    <h1 class="text-3xl font-medium">About</h1>
  </div>
  <div class="container mx-auto max-w-3xl px-4 my-8">
    <p class="pb-3">
      From a young age, my parents knew I would have a future with technology. 
      This idea probably formed from their many groundings given from finding me past curfew on the computer. 
    </p>
     <p class="pb-3">
      I was fortunate with access to home computers and the support of my parents to build my own, while in elementary school. 
      My passion was first sparked by the world of video games, but quickly transformed into excitement around hosting and managing dedicated linux game servers. 
      After understanding the difficulties of managing servers from command line I began my journey into web development. 
      I created tools that would help friends manage server instances from a webpage. 
    </p>
    <p class="pb-3">
      It was junior year high school, I started to realize that software development was the career path I wanted to pursue. 
      With an interest in web development and server administration I was dead set to take computer science at university. 
      A background in computer science has primed me with tools and the knowledge to build web applications that exceed expectations. 
    </p>
    <p class="pb-3">
      Now in industry, this passion remains. I constantly push myself to understand new technologies to deliver the best experiences possible. 
      There is certainly a mountain more to learn, and more problems to solve; knowing this is what keeps me enthusiastic and drives me everyday. 
    </p>
    <div class="flex flex-wrap mt-3">
      <div class="w-full sm:w-1/2 text-center">
        <img src="./profile.jpeg" class="w-9/12 mx-auto my-8 rounded" alt="">
        <a href="./resume.pdf" class="bg-gray-300 hover:bg-gray-400 text-gray-800 font-bold py-2 px-4 rounded inline-flex items-center" download>
          <svg class="fill-current w-4 h-4 mr-2" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 20 20"><path d="M13 8V2H7v6H2l8 8 8-8h-5zM0 18h20v2H0v-2z"/></svg>
          <span>Download Resume</span>
        </a>
      </div>
      <div class="w-full sm:w-1/2">
        <ul class="mt-6 mx-5">
          <li>
            <div class="flex">
              <div class="flex-shrink mr-4 mt-2">
                <img src="./icons/vuejs.svg" class="w-8" alt="vuejs">
              </div>
              <div class="flex-none">
                <div class="text-lg">Vue.js, Svelte & React</div>
                <span class="text-sm text-gray-700">Frontend Technology</span>
              </div>
            </div>
          </li>
          <li>
            <div class="flex mt-3">
              <div class="flex-shrink mr-4 mt-2">
                <img src="./icons/nodejs.svg" class="w-8" alt="vuejs">
              </div>
              <div class="flex-none">
                <div class="text-lg">NodeJs & PHP</div>
                <span class="text-sm text-gray-700">Backend Technology</span>
              </div>
            </div>
          </li>
          <li>
            <div class="flex mt-3">
              <div class="flex-shrink mr-4 mt-2">
                <img src="./icons/api.svg" class="w-8" alt="vuejs">
              </div>
              <div class="flex-none">
                <div class="text-lg">RESTful JSON</div>
                <span class="text-sm text-gray-700">API Design</span>
              </div>
            </div>
          </li>
          <li>
            <div class="flex mt-3">
              <div class="flex-shrink mr-4 mt-2">
                <img src="./icons/database.svg" class="w-8" alt="vuejs">
              </div>
              <div class="flex-none">
                <div class="text-lg">MySQL</div>
                <span class="text-sm text-gray-700">Database</span>
              </div>
            </div>
          </li>
          <li>
            <div class="flex mt-3">
              <div class="flex-shrink mr-4 mt-2">
                <img src="./icons/kubernetes.svg" class="w-8" alt="vuejs">
              </div>
              <div class="flex-none">
                <div class="text-lg">Kubernetes & Docker</div>
                <span class="text-sm text-gray-700">Devops</span>
              </div>
            </div>
          </li>
          <li>
            <div class="flex mt-3">
              <div class="flex-shrink mr-4 mt-2">
                <img src="./icons/git.svg" class="w-8" alt="vuejs">
              </div>
              <div class="flex-none">
                <div class="text-lg">Git & Github</div>
                <span class="text-sm text-gray-700">Version control</span>
              </div>
            </div>
          </li>
        </ul>
      </div>
    </div>
  </div>
</section>

<section class="bg-gray-100 py-10">
  <div class="text-center">
    <h1 class="text-3xl font-medium">Experience</h1>
  </div>
  <div class="container mx-auto max-w-3xl px-4 my-8">
    <ul>
      <li>
        <span class="text-xs text-gray-800 uppercase">March 2020 - Present</span>
        <h2 class="text-2xl">RaceRoster</h2>
        <h3 class="text-lg text-gray-800">Software Developer</h3>
        <p class="mt-2">
          Fullstack developer pushing the legacy code base into more modern technologies and design patterns.
        </p>
        <span class="border-vertical"></span>
      </li>
      <li>
        <span class="text-xs text-gray-800 uppercase">MAY 2017 - MARCH 2020</span>
        <h2 class="text-2xl">Sport-Travel</h2>
        <h3 class="text-lg text-gray-800">Lead Software Developer</h3>
        <p class="mt-2">
          I lead the software department at Sport-Travel where I pushed the team to develop scalable lightweight, progressive web applications. 
          I approached leadership by encouraging idea sharing and regular employee participation. While also trying to lead by going above and beyond.
          <br><br>
          Our stack was build on Vue.js, Node.js deployed with CircleCI to Kubernetes on Google Cloud.
           Our data was stored relationally in mySQL with additional request caching and idempotency keys managed by redis.
        </p>
        <span class="border-vertical"></span>
      </li>
      <li>
        <span class="text-xs text-gray-800 uppercase">2015 - 2016</span>
        <h2 class="text-2xl">DukeToyCo</h2>
        <h3 class="text-lg text-gray-800">Web Developer Consultant</h3>
        <p class="mt-2">
          Responsible for web design, CMS, server administration, and analytics www.duketoyco.com is a toy company based in Toronto Ontario.
        </p>
        <span class="border-vertical"></span>
      </li>
      <li>
        <span class="text-xs text-gray-800 uppercase">2013 - 2017</span>
        <h2 class="text-2xl">University of Western Ontario</h2>
        <h3 class="text-lg text-gray-800">Studied Computer Science</h3>
      </li>
    </ul>
  </div>
</section>

<section class="py-10">
  <div class="text-center">
    <h1 class="text-3xl font-medium">Portfolio</h1>
  </div>
  <div class="container mx-auto max-w-3xl px-4 my-8">
    <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
      <div class="relative shadow-xs p-4">
        <span class="text-lg font-bold pb-2">jamesvan-ca</span>
        <p class="text-sm pb-10">
          A server-side rendered Svelte/Sapper app deployed to Google App Engine. 
        </p>
        <p class="absolute bottom-0 w-full text-right pb-4 pr-8">
          <a href="https://github.com/jvanst/jamesvan-ca" target="_blank" rel="noopener" class="bg-gray-300 hover:bg-gray-400 text-gray-800 font-bold text-sm py-1 px-3 rounded inline-flex items-center">
            <span>Source</span>
            <img src="./icons/open-in-new.svg" class="w-4 ml-2" alt="Open in new tab">
          </a>
        </p>
      </div>
      <div class="relative shadow-xs p-4">
        <span class="text-lg font-bold pb-2">vue-vuetify-ssr</span>
        <p class="text-sm pb-10">
          A template for building server-side rendered Vue apps with the Vuetify component library.
        </p>
        <p class="absolute bottom-0 w-full text-right pb-4 pr-8">
          <a href="https://github.com/jvanst/vue-vuetify-ssr" target="_blank" rel="noopener" class="bg-gray-300 hover:bg-gray-400 text-gray-800 font-bold text-sm py-1 px-3 rounded inline-flex items-center">
            <span>Source</span>
            <img src="./icons/open-in-new.svg" class="w-4 ml-2" alt="Open in new tab">
          </a>
        </p>
      </div>
      <div class="relative shadow-xs p-4">
        <span class="text-lg font-bold pb-2">battalion-dedicated-server</span>
        <p class="text-sm pb-10">
          A Battalion1944 linux server installation and update command line tool written in python.
        </p>
        <p class="absolute bottom-0 w-full text-right pb-4 pr-8">
          <a href="https://github.com/jvanst/battalion-dedicated-server" target="_blank" rel="noopener" class="bg-gray-300 hover:bg-gray-400 text-gray-800 font-bold text-sm py-1 px-3 rounded inline-flex items-center">
            <span>Source</span>
            <img src="./icons/open-in-new.svg" class="w-4 ml-2" alt="Open in new tab">
          </a>
        </p>
      </div>
      <div class="relative shadow-xs p-4">
        <span class="text-lg font-bold pb-2">banksole</span>
        <p class="text-sm pb-10">
          A mock banking console application for Linux.
        </p>
        <p class="absolute bottom-0 w-full text-right pb-4 pr-8">
          <a href="https://github.com/jvanst/banksole" target="_blank" rel="noopener" class="bg-gray-300 hover:bg-gray-400 text-gray-800 font-bold text-sm py-1 px-3 rounded inline-flex items-center">
            <span>Source</span>
            <img src="./icons/open-in-new.svg" class="w-4 ml-2" alt="Open in new tab">
          </a>
        </p>
      </div>
    </div>
  </div>
</section>

<section class="bg-gray-800 py-10">
  <div class="text-center">
    <h1 class="text-3xl font-medium text-white">Even more</h1>
  </div>
  <div class="container mx-auto max-w-4xl px-4 my-8">
    <div class="grid md:grid-cols-4 sm:grid-cols-2 grid-cols-1 gap-4 m-auto text-white text-lg">
      <div class="text-center">
        <a href="/blog" class="mt-3"><img src="./icons/post-outline.svg" class="w-6 mr-2 pb-1 inline-block" alt="">Follow my blog</a>
      </div>
      <div class="text-center">
        <a href="https://ca.linkedin.com/in/jamesvansteenkiste"><img src="./icons/linkedin.svg" class="w-6 mr-2 pb-1 inline-block" alt="">Connect with me</a>
      </div>
      <div class="text-center">
        <a href="https://github.com/jvanst"><img src="./icons/github.svg" class="w-6 mr-2 pb-1 inline-block" alt="">Explore my code</a>
      </div>
      <div class="text-center">
        <a href="https://twitter.com/jrvansteenkiste"><img src="./icons/twitter.svg" class="w-6 mr-2 pb-1 inline-block" alt="">Tweet at me</a>
      </div>
    </div>
  </div>
</section>

<style>
.border-vertical {
  border-left: solid medium #000000;
  display: block;
  margin: auto;
  width: 0px;
  height: 2px;
  padding-bottom: 50px;
  margin-top: 10px;
  margin-bottom: 10px;
}
</style>