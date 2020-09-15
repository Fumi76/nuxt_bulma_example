<template>
  <div class="page-wrapper">
    <NavBar />
    
		<div class="content-wrapper">    
    <Nuxt />
    </div>
    
    <Footer />
    
  </div>
</template>

<style scoped>
.page-wrapper {
	display: flex;
	min-height: 100vh;
	flex-direction: column;
}

.content-wrapper {
	flex: 1;
}
</style>
