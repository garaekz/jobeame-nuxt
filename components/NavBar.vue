<script setup lang="ts">
import { Bars3BottomLeftIcon } from '@heroicons/vue/24/solid';
</script>
<template>
    <nav class="bg-white w-full flex items-center justify-between py-6 px-2 shadow-lg">
        <div class="flex items-center gap-2">
            <span>Logo</span>
            <button>
                <Bars3BottomLeftIcon class="h-8 w-8 text-black" />
            </button>
        </div>
        <button>
            Login
        </button>
    </nav>
</template>