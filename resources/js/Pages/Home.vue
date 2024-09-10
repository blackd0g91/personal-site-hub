<script setup>

import { Head, Link } from '@inertiajs/vue3';
import BaseBlock from '@/Components/BaseBlock.vue';

defineProps({
    laravelVersion: {
        type: String,
        required: true,
    },
    phpVersion: {
        type: String,
        required: true,
    },
});

</script>

<template>
    <Head title="Home" />

    <div class="bg-white text-white/50">

        <header 
            class="grid grid-cols-2 lg:grid-cols-3"
            style="background-image: url(https://static.vecteezy.com/system/resources/previews/008/161/952/non_2x/background-sea-shores-cartoon-ocean-floor-vector.jpg); background-size: cover;"   
        >
            <div class="p-4">
                <img src="https://png.pngtree.com/png-vector/20230801/ourmid/pngtree-tattoo-with-a-lighthouse-on-a-cloudy-image-vector-png-image_6825893.png" alt="Laravel" class="w-28 h-28">
            </div>
            <nav class="lg:bg-gradient-to-r from-sky-950 to-black flex items-end py-2 justify-end lg:row-start-2 lg:col-span-3">
                <Link class="mx-2" href="/" >
                    <!-- Home -->
                    <svg class="h-6 w-6 text-black lg:text-white/50 hover:text-sky-600"  fill="none" viewBox="0 0 24 24" stroke="currentColor">  <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 12l2-2m0 0l7-7 7 7M5 10v10a1 1 0 001 1h3m10-11l2 2m-2-2v10a1 1 0 01-1 1h-3m-6 0a1 1 0 001-1v-4a1 1 0 011-1h2a1 1 0 011 1v4a1 1 0 001 1m-6 0h6"/></svg>
                </Link>
                <a target="_blank" class="mx-2" href="http://murilomotta.ddns.net:50002" >
                    <!-- Nextcloud -->
                    <svg class="h-6 w-6 text-black lg:text-white/50 hover:text-sky-600"  width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">  <path stroke="none" d="M0 0h24v24H0z"/>  <path d="M7 18a4.6 4.4 0 0 1 0 -9h0a5 4.5 0 0 1 11 2h1a3.5 3.5 0 0 1 0 7h-12" /></svg>
                </a>
                <a target="_blank" class="mx-2" href="http://murilomotta.ddns.net:50001" >
                    <!-- Nextcloud -->
                    <p class="font-semibold text-black lg:text-white/50 hover:text-sky-600">
                        .blog
                    </p>
                </a>
            </nav>
        </header>

        <main>

            <section class="bg-sky-200 px-4 py-6">
                <div class="grid gap-6 lg:grid-cols-2 lg:gap-8 text-center">
                    <BaseBlock class="row-span-3">
                        <img src="https://cdn.dribbble.com/users/405330/screenshots/2755814/lighthouseillustrationdribbble.png" class="w-full rounded" alt="">
                        <div class="mt-4 text-justify text-md px-2">
                            <p>&nbspYou're running Laravel v{{ laravelVersion }} and PHP v{{ phpVersion }}.You're running Laravel v{{ laravelVersion }} and PHP v{{ phpVersion }}.You're running Laravel v{{ laravelVersion }} and PHP v{{ phpVersion }}.You're running Laravel v{{ laravelVersion }} and PHP v{{ phpVersion }}.</p>
                            <p>&nbspYou're running Laravel v{{ laravelVersion }} and PHP v{{ phpVersion }}.You're running Laravel v{{ laravelVersion }} and PHP v{{ phpVersion }}.You're running Laravel v{{ laravelVersion }} and PHP v{{ phpVersion }}.You're running Laravel v{{ laravelVersion }} and PHP v{{ phpVersion }}.</p>
                            <p>&nbspYou're running Laravel v{{ laravelVersion }} and PHP v{{ phpVersion }}.You're running Laravel v{{ laravelVersion }} and PHP v{{ phpVersion }}.You're running Laravel v{{ laravelVersion }} and PHP v{{ phpVersion }}.You're running Laravel v{{ laravelVersion }} and PHP v{{ phpVersion }}.</p>
                        </div>
                    </BaseBlock>
                    <BaseBlock class="grid grid-cols-3 place-items-center">
                        <div>
                            <img src="https://cdn.dribbble.com/users/405330/screenshots/2755814/lighthouseillustrationdribbble.png" class="w-full rounded" alt="">
                        </div>
                        <div class="h-full col-span-2 px-4">
                            <h1 class="text-3xl font-bold">Welcome to Laravel</h1>
                            <p class="mt-4 text-justify text-md">&nbspYou're running Laravel v{{ laravelVersion }} and PHP v{{ phpVersion }}.You're running Laravel v{{ laravelVersion }} and PHP v{{ phpVersion }}.You're running Laravel v{{ laravelVersion }} and PHP v{{ phpVersion }}.You're running Laravel v{{ laravelVersion }} and PHP v{{ phpVersion }}.You're running Laravel v{{ laravelVersion }} and PHP v{{ phpVersion }}.</p>
                        </div>
                    </BaseBlock>
                    <BaseBlock class="grid grid-cols-3 place-items-center">
                        <div>
                            <img src="https://cdn.dribbble.com/users/405330/screenshots/2755814/lighthouseillustrationdribbble.png" class="w-full rounded" alt="">
                        </div>
                        <div class="h-full col-span-2 px-4">
                            <h1 class="text-3xl font-bold">Welcome to Laravel</h1>
                            <p class="mt-4 text-justify text-md">&nbspYou're running Laravel v{{ laravelVersion }} and PHP v{{ phpVersion }}.You're running Laravel v{{ laravelVersion }} and PHP v{{ phpVersion }}.You're running Laravel v{{ laravelVersion }} and PHP v{{ phpVersion }}.You're running Laravel v{{ laravelVersion }} and PHP v{{ phpVersion }}.You're running Laravel v{{ laravelVersion }} and PHP v{{ phpVersion }}.</p>
                        </div>
                    </BaseBlock>
                    <BaseBlock class="grid grid-cols-3 place-items-center">
                        <div>
                            <img src="https://cdn.dribbble.com/users/405330/screenshots/2755814/lighthouseillustrationdribbble.png" class="w-full rounded" alt="">
                        </div>
                        <div class="h-full col-span-2 px-4">
                            <h1 class="text-3xl font-bold">Welcome to Laravel</h1>
                            <p class="mt-4 text-justify text-md">&nbspYou're running Laravel v{{ laravelVersion }} and PHP v{{ phpVersion }}.You're running Laravel v{{ laravelVersion }} and PHP v{{ phpVersion }}.You're running Laravel v{{ laravelVersion }} and PHP v{{ phpVersion }}.You're running Laravel v{{ laravelVersion }} and PHP v{{ phpVersion }}.You're running Laravel v{{ laravelVersion }} and PHP v{{ phpVersion }}.</p>
                        </div>
                    </BaseBlock>
                </div>
            </section>

            <section class="bg-sky-900 px-4 py-6">
                <div class="p-4 lg:px-16 gap-16 flex flex-wrap lg:flex-nowrap justify-around">
                    <BaseBlock>
                        <img src="https://cdn.dribbble.com/users/405330/screenshots/2755814/lighthouseillustrationdribbble.png" class="w-full rounded" alt="">
                        <p class="mt-4 text-md">&nbspYou're running Laravel v{{ laravelVersion }} and PHP v{{ phpVersion }}.</p>
                    </BaseBlock>
                    <BaseBlock>
                        <img src="https://cdn.dribbble.com/users/405330/screenshots/2755814/lighthouseillustrationdribbble.png" class="w-full rounded" alt="">
                        <p class="mt-4 text-md">&nbspYou're running Laravel v{{ laravelVersion }} and PHP v{{ phpVersion }}.</p>
                    </BaseBlock>
                    <BaseBlock>
                        <img src="https://cdn.dribbble.com/users/405330/screenshots/2755814/lighthouseillustrationdribbble.png" class="w-full rounded" alt="">
                        <p class="mt-4 text-md">&nbspYou're running Laravel v{{ laravelVersion }} and PHP v{{ phpVersion }}.</p>
                    </BaseBlock>
                </div>
            </section>

        </main>

        <footer class="text-center text-sm">
            <nav class="bg-gradient-to-r from-sky-950 to-black flex items-end py-2 justify-end lg:row-start-2 lg:col-span-3">

                <!-- Github -->
                <a target="_blank" class="mx-2" href="https://github.com/blackd0g91" >
                    <svg class="h-6 w-6 text-white/50 hover:text-sky-600"  viewBox="0 0 24 24"  fill="none"  stroke="currentColor"  stroke-width="2"  stroke-linecap="round"  stroke-linejoin="round">  <path d="M9 19c-5 1.5-5-2.5-7-3m14 6v-3.87a3.37 3.37 0 0 0-.94-2.61c3.14-.35 6.44-1.54 6.44-7A5.44 5.44 0 0 0 20 4.77 5.07 5.07 0 0 0 19.91 1S18.73.65 16 2.48a13.38 13.38 0 0 0-7 0C6.27.65 5.09 1 5.09 1A5.07 5.07 0 0 0 5 4.77a5.44 5.44 0 0 0-1.5 3.78c0 5.42 3.3 6.61 6.44 7A3.37 3.37 0 0 0 9 18.13V22" /></svg>
                </a>

                <!-- LinkedIN -->
                <a target="_blank" class="mx-2" href="https://www.linkedin.com/in/murilo-motta-32a6b3172/" >
                    <svg class="h-6 w-6 text-white/50 hover:text-sky-600"  viewBox="0 0 24 24"  fill="none"  stroke="currentColor"  stroke-width="2"  stroke-linecap="round"  stroke-linejoin="round">  <path d="M16 8a6 6 0 0 1 6 6v7h-4v-7a2 2 0 0 0-2-2 2 2 0 0 0-2 2v7h-4v-7a6 6 0 0 1 6-6z" />  <rect x="2" y="9" width="4" height="12" />  <circle cx="4" cy="4" r="2" /></svg>
                </a>

                <!-- Instagram -->
                <a target="_blank" class="mx-2" href="https://www.instagram.com/murilofmotta" >
                    <svg class="h-6 w-6 text-white/50 hover:text-sky-600"  viewBox="0 0 24 24"  fill="none"  stroke="currentColor"  stroke-width="2"  stroke-linecap="round"  stroke-linejoin="round">  <rect x="2" y="2" width="20" height="20" rx="5" ry="5" />  <path d="M16 11.37A4 4 0 1 1 12.63 8 4 4 0 0 1 16 11.37z" />  <line x1="17.5" y1="6.5" x2="17.51" y2="6.5" /></svg>
                </a>

                <!-- Twitter
                <a target="_blank" class="mx-2" href="/" >
                    <svg class="h-6 w-6 text-white/50 hover:text-sky-600"  width="24" height="24" viewBox="0 0 24 24"  fill="none"  stroke="currentColor"  stroke-width="2"  stroke-linecap="round"  stroke-linejoin="round" ><path stroke="none" d="M0 0h24v24H0z" fill="none"/><path d="M4 4l11.733 16h4.267l-11.733 -16z" /><path d="M4 20l6.768 -6.768m2.46 -2.46l6.772 -6.772" /></svg>
                </a> -->

                <!-- Twitch -->
                <a target="_blank" class="mx-2" href="https://www.twitch.tv/blackd0g" >
                    <svg class="h-6 w-6 text-white/50 hover:text-sky-600"  viewBox="0 0 24 24"  fill="none"  stroke="currentColor"  stroke-width="2"  stroke-linecap="round"  stroke-linejoin="round">  <path d="M21 2H3v16h5v4l4-4h5l4-4V2zM11 11V7M16 11V7" /></svg>
                </a>

                <!-- Telegram -->
                <a target="_blank" class="mx-2" href="https://t.me/murilomotta" >
                    <svg class="h-6 w-6 text-white/50 hover:text-sky-600"  width="24" height="24" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" fill="none" stroke-linecap="round" stroke-linejoin="round">  <path stroke="none" d="M0 0h24v24H0z"/>  <path d="M15 10l-4 4l6 6l4 -16l-18 7l4 2l2 6l3 -4" /></svg>
                </a>

                <!-- Email -->
                <a target="_blank" class="mx-2" href="mailto:murilofmotta@gmail.com" >
                    <svg class="h-6 w-6 text-white/50 hover:text-sky-600"  fill="none" viewBox="0 0 24 24" stroke="currentColor"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"/></svg>

                </a>

            </nav>
            <p class="bg-black">
                Laravel v{{ laravelVersion }} (PHP v{{ phpVersion }})
            </p>
        </footer>
    </div>



</template>
