<script setup>
const currentYear = new Date().getFullYear();
</script>

<template>
    <div class="py-2 flex text-center w-full">
        <div class="mx-auto">
            <span class="text-center">
                &copy; {{ currentYear }} Deoxys
            </span>
        </div>
    </div>
</template>