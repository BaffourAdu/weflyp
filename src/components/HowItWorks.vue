<template>
    <div class="h-auto py-12 xl:px-48 md:px-12 px-6">
        <div class="bg-white w-full h-32 p-6 border-2 border-black">
            <h1>How does WeFlyp work?</h1>
            <p>
                Reselling with WeFlyp is as easy as sharing pictures 
                with your customers. No more up front inventory costs or shipping logistics.  
            </p>
        </div>
        <div class="w-full flex flex-col md:flex-shrink lg:flex-row mt-4 text-center">
            <div class="md:flex w-full m-0  object-center">
                <div class="bg-white md:w-2/4 h-64 mt-2 p-6 border-2 border-black content-center">
                    <img src="../assets/images/browse.jpg" alt="">
                    <h1>Browse Products</h1>
                </div>
                <div class="bg-white md:w-2/4 h-64 md:ml-2 mt-2 p-6 border-2 border-black">
                    <img src="../assets/images/share.png" alt="">
                    <h1>Share with Customers</h1>
                </div>
            </div>
            <div class="md:flex w-full m-0">
                <div class="bg-white md:w-2/4 h-64 mt-2 lg:ml-2 p-6 border-2 border-black">
                    <img src="../assets/images/order.jpg" alt="">
                    <h1>place Order</h1>
                </div> 
                <div class="bg-white md:w-2/4 h-64 md:ml-2 mt-2 p-6 border-2 border-black">
                    <img src="../assets/images/deliver.jpg" alt="">
                    <h1>Order Delivered</h1>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'HowItWorks'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
