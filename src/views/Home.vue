<script setup>

</script>

<template>

    <section class="hero flex flex-col items-start justify-center h-[90vh] px-16 bg-[url(/hospital-photo.webp)] text-white bg-cover bg-center">
        <h1 class="text-4xl md:text-5xl font-bold mb-4 max-w-2xl">Princeton Plainsboro Teaching Hospital</h1>
        <p class="text-lg md:text-xl mb-6 max-w-xl">Excellence in healthcare, teaching, and cutting-edge medical research</p>
    
        <div class="flex gap-4 flex-wrap">
            <router-link class="bg-rose-950 text-white px-4 py-2 rounded-md">Find a Doctor</router-link>
            <router-link class="bg-none border-2 text-white px-4 py-2 rounded-md">Emergency Services</router-link>
        </div>
    </section>

    <section class="bg-[#8E2323] text-white py-6 flex justify-center items-center">
        <div class="container">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <div class="flex items-center gap-3">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-phone h-6 w-6">
                        <path d="M22 16.92v3a2 2 0 0 1-2.18 2 19.79 19.79 0 0 1-8.63-3.07 19.5 19.5 0 0 1-6-6 19.79 19.79 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3a2 2 0 0 1 2 1.72 12.84 12.84 0 0 0 .7 2.81 2 2 0 0 1-.45 2.11L8.09 9.91a16 16 0 0 0 6 6l1.27-1.27a2 2 0 0 1 2.11-.45 12.84 12.84 0 0 0 2.81.7A2 2 0 0 1 22 16.92z"></path>
                    </svg>
                    <div>
                        <p class="text-sm font-medium">Emergency</p>
                        <p class="text-lg font-bold">609-555-0123</p>
                    </div>
                </div>
                <div class="flex items-center gap-3">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-clock h-6 w-6">
                        <circle cx="12" cy="12" r="10"></circle>
                        <polyline points="12 6 12 12 16 14"></polyline>
                    </svg>
                    <div>
                        <p class="text-sm font-medium">Working Hours</p>
                        <p class="text-lg font-bold">24/7 Emergency Care</p>
                    </div>
                </div>
                <div class="flex items-center gap-3">
                    <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-map-pin h-6 w-6">
                        <path d="M20 10c0 6-8 12-8 12s-8-6-8-12a8 8 0 0 1 16 0Z"></path>
                        <circle cx="12" cy="10" r="3"></circle>
                    </svg>
                    <div>
                        <p class="text-sm font-medium">Location</p>
                        <p class="text-lg font-bold">Princeton, New Jersey</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

</template>

<style scoped>


</style>
