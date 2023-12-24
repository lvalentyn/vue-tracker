<script setup>
import { CheckCircleIcon } from '@heroicons/vue/24/solid'
</script>
<template>
    <header class="sticky top-0 z-20 flex justify-between items-center border-b bg-white p-3">
        <a href="#">
            <img class="h-9" src="./assets/img/logo.png" alt="" />
        </a>

        <a href="#" class="">
            <span v-if="true" class="flex items-center gap-1 text-sm">
                Day complete!
                <CheckCircleIcon class="h-7 text-green-500" />
            </span>

            <span v-else class="flex items-center gap-1 text-sm">
                Progress: <span class="font-mono">20%</span>
                <span class="h-3 w-3 rounded-full bg-red-500"></span>
            </span>
        </a>
    </header>
    <main class="flex flex-grow flex-col">
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Aspernatur recusandae ut ullam
        earum rerum quasi repellendus, atque et laboriosam quia, temporibus modi possimus fugit,
        quis deserunt! Tenetur id temporibus delectus nisi eveniet molestias sint veniam voluptate
        incidunt inventore. Nemo excepturi vel modi error. Quae, distinctio! Earum ullam nesciunt
        delectus incidunt?
    </main>
    <nav class="sticky bottom-0 z-10 bg-white text-3xl">nav</nav>
</template>
