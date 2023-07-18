<script setup lang="ts">
import { GlobeAmericasIcon } from '@heroicons/vue/24/solid';
</script>
<template>
    <NavBar />
    <div class="px-2">
        <header class="mt-4 rounded-2xl overflow-hidden h-96 bg-cover bg-center bg-no-repeat relative"
            style="background-image: url('https://pixelprime.co/themes/jobster/images/company-hero-2.jpg');">
            <div class="absolute inset-0 bg-black bg-opacity-30"></div>
            <div class="absolute inset-x-5 bottom-5">
                <div class="flex flex-col justify-center items-center gap-8">
                    <img class="w-24 h-24 rounded-2xl bg-white p-2"
                        src="https://larajobs.com/logos/GoVzobP7chr6XMMDnmcwSuDf1sH0mFUPorlLEK9W.png" alt="Company Logo">
                    <div class="flex flex-col items-center text-white">
                        <h2 class="text-3xl font-bold">Wolvn Studio</h2>
                        <p class="font-thin text-md flex items-center gap-2">
                            <GlobeAmericasIcon class="w-5 h-5" /> Tijuana, BC
                        </p>
                    </div>
                </div>
            </div>
        </header>
        <section id="about" class="my-8">
            <h2 class="my-8 text-xl font-bold text-gray-900">About Wolvn Studio</h2>
            <p class="text-sm font-thin">
                Lorem ipsum dolor sit amet consectetur adipisicing elit.
                Quisquam, voluptatum. Quisquam, voluptatum. Quisquam, voluptatum.
                Quisquam, voluptatum. Quisquam, voluptatum. Quisquam, voluptatum.
                Quisquam, voluptatum. Quisquam, voluptatum. Quisquam, voluptatum.
                Quisquam, voluptatum. Quisquam, voluptatum. Quisquam, voluptatum.
                Quisquam, voluptatum. Quisquam, voluptatum. Quisquam, voluptatum.
                Quisquam, voluptatum. Quisquam, voluptatum. Quisquam, voluptatum.
                Quisquam, voluptatum. Quisquam, voluptatum. Quisquam, voluptatum.
            </p>
        </section>
        <section id="gallery">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
                <div class="grid gap-4">
                    <div>
                        <img class="h-auto max-w-full rounded-lg"
                            src="https://flowbite.s3.amazonaws.com/docs/gallery/masonry/image.jpg" alt="">
                    </div>
                    <div>
                        <img class="h-auto max-w-full rounded-lg"
                            src="https://flowbite.s3.amazonaws.com/docs/gallery/masonry/image-1.jpg" alt="">
                    </div>
                    <div>
                        <img class="h-auto max-w-full rounded-lg"
                            src="https://flowbite.s3.amazonaws.com/docs/gallery/masonry/image-2.jpg" alt="">
                    </div>
                </div>
                <div class="grid gap-4">
                    <div>
                        <img class="h-auto max-w-full rounded-lg"
                            src="https://flowbite.s3.amazonaws.com/docs/gallery/masonry/image-6.jpg" alt="">
                    </div>
                    <div>
                        <img class="h-auto max-w-full rounded-lg"
                            src="https://flowbite.s3.amazonaws.com/docs/gallery/masonry/image-7.jpg" alt="">
                    </div>
                    <div>
                        <img class="h-auto max-w-full rounded-lg"
                            src="https://flowbite.s3.amazonaws.com/docs/gallery/masonry/image-8.jpg" alt="">
                    </div>
                </div>
            </div>
        </section>
        <div class="rounded-xl px-4 py-8 bg-amber-100 my-8">
            <ul class="flex flex-col gap-6">
                <li class="flex flex-col gap-1 font-medium">
                    <span class="text-xs font-thin text-gray-800">Industry</span>
                    Software
                </li>
                <li class="flex flex-col gap-1 font-medium">
                    <span class="text-xs font-thin text-gray-800">Company Size</span>
                    50-100
                </li>
                <li class="flex flex-col gap-1 font-medium">
                    <span class="text-xs font-thin text-gray-800">Founded In</span>
                    2020
                </li>
                <li class="flex flex-col gap-1 font-medium">
                    <span class="text-xs font-thin text-gray-800">Phone</span>
                    (555) 123-4567
                </li>
                <li class="flex flex-col gap-1 font-medium">
                    <span class="text-xs font-thin text-gray-800">Email</span>
                    fake@mail.io
                </li>
                <li class="flex flex-col gap-1 font-medium">
                    <span class="text-xs font-thin text-gray-800">Location</span>
                    Tijuana, BC
                </li>
                <li class="flex flex-col gap-1 font-medium">
                    <span class="text-xs font-thin text-gray-800">Website</span>
                    <a class="text-indigo-800" href="http://site.local">site.local</a>
                </li>
                <li class="flex gap-5">
                    <a class="text-gray-600" href="https://facebook.com" target="_blank" rel="noopener noreferrer">
                        <svg
                            class="h-5 w-5"
                            fill="currentColor"
                            xmlns="http://www.w3.org/2000/svg" height="1em" viewBox="0 0 320 512">
                            <path
                                d="M279.14 288l14.22-92.66h-88.91v-60.13c0-25.35 12.42-50.06 52.24-50.06h40.42V6.26S260.43 0 225.36 0c-73.22 0-121.08 44.38-121.08 124.72v70.62H22.89V288h81.39v224h100.17V288z" />
                        </svg>
                    </a>
                    <a class="text-gray-600" href="https://twitter.com" target="_blank" rel="noopener noreferrer">
                        <svg
                            class="h-5 w-5"
                            fill="currentColor"
                            xmlns="http://www.w3.org/2000/svg" 
                            height="1em" viewBox="0 0 512 512">
                            <path
                                d="M459.37 151.716c.325 4.548.325 9.097.325 13.645 0 138.72-105.583 298.558-298.558 298.558-59.452 0-114.68-17.219-161.137-47.106 8.447.974 16.568 1.299 25.34 1.299 49.055 0 94.213-16.568 130.274-44.832-46.132-.975-84.792-31.188-98.112-72.772 6.498.974 12.995 1.624 19.818 1.624 9.421 0 18.843-1.3 27.614-3.573-48.081-9.747-84.143-51.98-84.143-102.985v-1.299c13.969 7.797 30.214 12.67 47.431 13.319-28.264-18.843-46.781-51.005-46.781-87.391 0-19.492 5.197-37.36 14.294-52.954 51.655 63.675 129.3 105.258 216.365 109.807-1.624-7.797-2.599-15.918-2.599-24.04 0-57.828 46.782-104.934 104.934-104.934 30.213 0 57.502 12.67 76.67 33.137 23.715-4.548 46.456-13.32 66.599-25.34-7.798 24.366-24.366 44.833-46.132 57.827 21.117-2.273 41.584-8.122 60.426-16.243-14.292 20.791-32.161 39.308-52.628 54.253z" />
                        </svg>
                    </a>
                    <a class="text-gray-600" href="https://instagram.com" target="_blank" rel="noopener noreferrer">
                        <svg
                            class="h-5 w-5"
                            fill="currentColor"
                            xmlns="http://www.w3.org/2000/svg" height="1em" viewBox="0 0 448 512">
                            <path
                                d="M224.1 141c-63.6 0-114.9 51.3-114.9 114.9s51.3 114.9 114.9 114.9S339 319.5 339 255.9 287.7 141 224.1 141zm0 189.6c-41.1 0-74.7-33.5-74.7-74.7s33.5-74.7 74.7-74.7 74.7 33.5 74.7 74.7-33.6 74.7-74.7 74.7zm146.4-194.3c0 14.9-12 26.8-26.8 26.8-14.9 0-26.8-12-26.8-26.8s12-26.8 26.8-26.8 26.8 12 26.8 26.8zm76.1 27.2c-1.7-35.9-9.9-67.7-36.2-93.9-26.2-26.2-58-34.4-93.9-36.2-37-2.1-147.9-2.1-184.9 0-35.8 1.7-67.6 9.9-93.9 36.1s-34.4 58-36.2 93.9c-2.1 37-2.1 147.9 0 184.9 1.7 35.9 9.9 67.7 36.2 93.9s58 34.4 93.9 36.2c37 2.1 147.9 2.1 184.9 0 35.9-1.7 67.7-9.9 93.9-36.2 26.2-26.2 34.4-58 36.2-93.9 2.1-37 2.1-147.8 0-184.8zM398.8 388c-7.8 19.6-22.9 34.7-42.6 42.6-29.5 11.7-99.5 9-132.1 9s-102.7 2.6-132.1-9c-19.6-7.8-34.7-22.9-42.6-42.6-11.7-29.5-9-99.5-9-132.1s-2.6-102.7 9-132.1c7.8-19.6 22.9-34.7 42.6-42.6 29.5-11.7 99.5-9 132.1-9s102.7-2.6 132.1 9c19.6 7.8 34.7 22.9 42.6 42.6 11.7 29.5 9 99.5 9 132.1s2.7 102.7-9 132.1z" />
                        </svg>
                    </a>
                    <a class="text-gray-600" href="https://linkedin.com" target="_blank" rel="noopener noreferrer">
                        <svg 
                            class="h-5 w-5"
                            fill="currentColor"
                            xmlns="http://www.w3.org/2000/svg" height="1em" viewBox="0 0 448 512">
                            <path
                                d="M100.28 448H7.4V148.9h92.88zM53.79 108.1C24.09 108.1 0 83.5 0 53.8a53.79 53.79 0 0 1 107.58 0c0 29.7-24.1 54.3-53.79 54.3zM447.9 448h-92.68V302.4c0-34.7-.7-79.2-48.29-79.2-48.29 0-55.69 37.7-55.69 76.7V448h-92.78V148.9h89.08v40.8h1.3c12.4-23.5 42.69-48.3 87.88-48.3 94 0 111.28 61.9 111.28 142.3V448z" />
                        </svg>
                    </a>
                </li>
            </ul>
        </div>
        <div class="h-screen"></div>
    </div>
</template>