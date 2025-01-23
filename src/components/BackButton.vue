<script setup>
import { RouterLink } from 'vue-router';
</script>

<template>
    <!-- Go Back -->
    <section>
        <div class="container m-auto py-6 px-6">
            <RouterLink to="/jobs" class="text-green-500 hover:text-green-600 flex items-center">
                <i class="fa-solid fa-arrow-left fa-fade mr-2" style="color: #63E6BE; "></i> Back to Job Listings
            </RouterLink>
        </div>
    </section>
</template>