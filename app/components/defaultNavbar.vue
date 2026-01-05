<template>
    <nav class="bg-gray-800 p-4">
        <div class="container mx-auto flex justify-between items-center">
            <NuxtLink to="/" class="text-white text-lg font-semibold">
                Sample App
            </NuxtLink>

            <div class="md:flex space-x-4">
                <NuxtLink to="/about" class="text-gray-300 hover:text-white">About</NuxtLink>
                <NuxtLink to="/services" class="text-gray-300 hover:text-white">Services</NuxtLink>
                <NuxtLink to="/contact" class="text-gray-300 hover:text-white">Contact</NuxtLink>
            </div>
        </div>
    </nav>
</template>

