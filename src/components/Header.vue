<script setup>

</script>

<template>
    <header class="overflow-hidden sticky top-0 z-50 w-full border-b p-4 min-h-16 flex justify-between items-center bg-white text-black">
        <!-- <div class="logo flex items-center gap-2">
            <div class="w-10 h-10 rounded-full bg-[#8E2323] flex items-center justify-center text-white font-bold text-xl">P</div>
            <div class="flex flex-col">
                <p class="text-rose-950 font-bold">Princeton Plainsboro</p>
                <p class="text-sm">Teaching Hospital</p>
            </div>
        </div> -->
        <img class="h-16" src="/ppth-fake-logo.png" alt="logo">


        <nav class="flex">
            <ul class="flex gap-8 font-medium">
            <li><router-link to="/">Home</router-link></li>
            <li><router-link to="/about">About</router-link></li>
            <li><router-link to="/contact">Contact</router-link></li>
            <li><router-link to="/departments">Departments</router-link></li>
            <li><router-link to="/doctors">Our Doctors</router-link></li>
            <li><router-link to="/patient-info">Patient Info</router-link></li>
            <li><router-link to="/research">Research</router-link></li>
            </ul>
        </nav>

        <router-link class="bg-rose-950 text-white px-4 py-2 rounded-md">Book a Consult</router-link>
    </header>
</template>

<style scoped>


</style>