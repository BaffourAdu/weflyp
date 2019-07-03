<template>
    <header class="h-full">
        <div class="bg-cover bg-center bg-auto top-header relative" style="height: 60vh;">
           <img src="../assets/images/torn.svg" alt="Torn Image" class="absolute inset-x-0 bottom-0">
        </div>
        <div class="xl:px-48 md:p-8 p-6 bottom-header text-center" style="height: 40vh;">
            <h1 class="font-bold lg:text-5xl font-sans sm:text-3xl text-xl">Start Your Business from Home with Zero Capital</h1>
            <p class="md:text-xl text-base font-mono">Start and run a business without the hassle of managing inventory, packaging, or shipping.</p>
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
.top-header {
    background-image: url('../assets/images/bg.jpg');
    vertical-align: bottom;
}
.botttom-header {
    background-color: #f9f9f9;
}
</style>
