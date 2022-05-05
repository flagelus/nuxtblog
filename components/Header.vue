<template>
  <header><div class="title">Meu Blog</div>
      <nav>
        <nuxt-link to="/">Home</nuxt-link>
        <nuxt-link to="/about">Sobre</nuxt-link>
      </nav>
      </header>
</template>

<script>
export default {

}
</script>

<style>
header {
	padding: 15px 30px;
	background-color: rgb(11, 11, 14);
	display: flex;
	justify-content: space-between;
	align-items: center;
	box-shadow: 0px 3px 6px rgba(0, 0, 0, 0.1);
}
header .title {
	color: #dfd7d7;
	font-size: 24px;
	font-weight: 900;
	text-transform: uppercase;
}
nav {
	display: flex;
	align-items: center;
	margin: 0 -15px;
}
nav a {
	display: block;
	margin: 0 15px;
	color: #90e0e6;
}
</style>