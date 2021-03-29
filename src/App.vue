<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <h1 class="mt-4 text-center">Hobby</h1>
    <!-- <div class="mt-8 grid grid-flow-col grid-cols-3 gap-4">
        <div class="rounded-lg shadow-md"></div>
        <div class="rounded-lg shadow-md">2</div>
        <div class="rounded-lg shadow-md">3</div>
    </div> -->
    <body class="font-sans antialiased text-gray-900 leading-normal tracking-wider bg-cover" style="background-image:url('');">



  <div class="max-w-4xl flex items-center h-auto lg:h-screen flex-wrap mx-auto my-32 lg:my-0">
    
	<!--Main Col-->
	<div id="profile" class="w-full lg:w-3/5 rounded-lg lg:rounded-l-lg lg:rounded-r-none shadow-2xl bg-white opacity-75 mx-6 lg:mx-0">
	

		<div class="p-4 md:p-12 text-center lg:text-left">
			<!-- Image for mobile view-->
			<div class="block lg:hidden rounded-full shadow-xl mx-auto -mt-16 h-48 w-48 bg-cover bg-center" style="background-image: url(https://fsa.zobj.net/crop.php?r=t26OJWq0ZW9qIx5qs9h99GpdsUPVMhATAVbYdJ4M380H4o5lyBrVkhg6gPEmwgJDNvwDv51Tc4-mJKWuX5hzjEVThJRi1UbNzAqjlWFbb2syUTf7kjVUyAYDM1gQZkNA_f02wVUaxMvMVRgE)"></div>
			
			<h1 class="text-3xl font-bold pt-8 lg:pt-0">Hobby 1</h1>
			<div class="mx-auto lg:mx-0 w-4/5 pt-3 border-b-2 border-green-500 opacity-25"></div>
			<p class="pt-8 text-sm">Listening to Music</p>

		</div>

	</div>
	
	<!--Img Col-->
	<div class="w-full lg:w-2/5">
		<!-- Big profile image for side bar (desktop) -->
		<img src="./assets/img/music.jpg" class="rounded-none lg:rounded-lg shadow-2xl hidden lg:block">		
	</div>

</div>
    </body>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
