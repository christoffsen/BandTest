<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Pacifico&display=swap');
*{
	box-sizing: border-box;
}
#app {
	border-style: hidden;
	border-radius: 0;
	font-family: Avenir, Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	background-color: #FCF6F5FF;
	width: inherit;
	min-width: 40rem;
}
#home {
	border-style: hidden;
	border-radius: 0;
}
h1 {
	font-family: Pacifico, cursive;
	font-size: 5rem;
	color: #990011FF;
}
h2 {
	color: #000000;
	font-style: italic;
	background-color: #FFFFFF;
	display: block;
	margin-left: auto;
	margin-right: auto;
	border-radius: 1rem;
	width: 33%;
}

div {
	border-width: 1px;
	border-radius: 1rem;
	border-color: #880000DD;
	border-style: solid;
	width: 100%;
	overflow-x: auto;
	padding-bottom: 5rem;
}
iframe {
	border-style: hidden;
}
</style>