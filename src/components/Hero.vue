<template>
    <header class="h-full">
        <div class="bg-cover bg-center bg-auto top-header relative" style="height: 40vh;">
           <img src="../assets/images/torn.svg" alt="Torn Image" class="absolute inset-x-0 bottom-0">
        </div>
        <div class="bg-white sm:py-20 py-12 xl:px-48 md:px-8 px-6 bottom-header text-center" style="height: 60vh;">
            <h1 class="font-bold lg:text-5xl font-sans sm:text-3xl text-2xl">Start Your Business from Home with Zero Capital</h1>
            <p class="md:text-xl text-base font-mono py-4 leading-snug mb-4">Start and run a business without the hassle of managing inventory, packaging, or shipping.</p>
            <a href="https://epay-demo.herokuapp.com/" title="Get Early Access" class="hover:bg-white text-white bg-purple-700 hover:text-purple-700 no-underline tracking-wide uppercase rounded-lg text-sm font-bold shadow-md hover:shadow py-4 px-6">
                Get Early Access
            </a>
        </div>
    </header>
</template>

<script>
export default {
  name: 'Hero'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
/*
xl:px-48 md:p-8 p-6*/
.top-header {
    background-image: url('../assets/images/bg.jpg');
    vertical-align: bottom;
}
.botttom-header {
    /*background-color: #f9f9f9;*/
}
</style>
