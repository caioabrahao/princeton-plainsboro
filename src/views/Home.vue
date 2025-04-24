<script setup>

</script>

<template>

    <section class="hero flex flex-col items-start justify-center h-[90vh] px-16 bg-[url(/hospital-photo.webp)] text-white bg-cover bg-center">
        <h1 class="text-4xl md:text-5xl font-bold mb-4 max-w-2xl">Princeton Plainsboro Teaching Hospital</h1>
        <p class="text-lg md:text-xl mb-6 max-w-xl">Excellence in healthcare, teaching, and cutting-edge medical research</p>
    
        <div class="flex gap-4 flex-wrap">
            <router-link class="bg-princetonRed text-white px-4 py-2 rounded-md">Find a Doctor</router-link>
            <router-link class="bg-none border-2 text-white px-4 py-2 rounded-md">Emergency Services</router-link>
        </div>
    </section>

    <section class="bg-princetonRed text-white py-6">
        <div class="container flex align-center justify-center">
            <div class="grid grid-cols-3 gap-6">
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

    <section class="grid grid-cols-2 gap-4 px-16 py-12 bg-white text-black">
        <div class="flex flex-col gap-4 align-center justify-center">
            <h2 class="font-bold text-3xl">About out Hospital</h2>
            <p class="text-gray-600 mb-4">
                Princeton Plainsboro Teaching Hospital (PPTH) is a world-renowned medical facility dedicated to providing exceptional patient care, advancing medical research, and training the next generation of healthcare professionals.
                <br><br>
                Founded in 1965, our hospital has grown into one of the nation's premier teaching hospitals, known for our innovative diagnostic approaches and specialized departments led by world-class physicians.
            </p>

            <div class="grid grid-cols-2 gap-4 mb-4">
                <div class="flex items-center gap-3 mb-4">
                    <div>
                        <p class="font-bold text-4xl text-princetonRed">300+</p>
                        <p class="text-gray-600 text-sm">Hospital Beds</p>
                    </div>
                </div>

                <div class="flex items-center gap-3 mb-4">
                    <div>
                        <p class="font-bold text-4xl text-princetonRed">150+</p>
                        <p class="text-gray-600 text-sm">Specialists</p>
                    </div>
                </div>

                <div class="flex items-center gap-3 mb-4">
                    <div>
                        <p class="font-bold text-4xl text-princetonRed">15+</p>
                        <p class="text-gray-600 text-sm">Departments</p>
                    </div>
                </div>

                <div class="flex items-center gap-3 mb-4">
                    <div>
                        <p class="font-bold text-4xl text-princetonRed">24/7</p>
                        <p class="text-gray-600 text-sm">Emergency Care</p>
                    </div>
                </div>
            </div>

            <router-link class="bg-princetonRed text-white px-4 py-2 rounded-md w-fit">Learn More about PPTH</router-link>
        </div>

        <div class="flex items-center justify-center">
            <img class="rounded-md w-[70%]" src="/ppth-front.jpg" alt="our hospital front">
        </div>
    </section>

    <section class="grid grid-cols-2 gap-4 px-16 py-12 bg-white text-black">
        <div>
            <h2 class="font-bold text-3xl">Patient Information</h2>
            <p class="text-gray-600 mb-4">At Princeton Plainsboro Teaching Hospital, we strive to make your healthcare experience as smooth as possible. Find information about appointments, insurance, visiting hours, and more.</p>
        </div>

        
        <div class="grid grid-cols-2 gap-4">
            <div class="text-center flex flex-col gap-2 justify-center border-2 border-gray-400 rounded-md p-4 bg-gray-50">
                <div class="w-16 h-16 rounded-full bg-[#8E2323]/10 flex items-center justify-center mb-4">
                    P
                </div>
                
                <h3 class="font-bold text-xl">Patient Portal</h3>
                <p class="text-gray-600 mb-4 text-sm">Access your medical records, test results, and communicate with your care team.</p>
                <router-link class="bg-princetonRed text-white px-4 py-2 rounded-md w-full">Log In</router-link>
            </div>
            
            
        </div>
    </section>

</template>

<style scoped>


</style>
