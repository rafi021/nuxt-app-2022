<template>
    <div class="">
        <nav class="bg-purple-700 text-white shadow-lg text-lg flex justify-between">
        <NuxtLink to="/">Home</NuxtLink> |
        <NuxtLink to="/about">About</NuxtLink> |
        <NuxtLink to="/profile">Profile</NuxtLink> |
        <NuxtLink to="/iphone">iPhone</NuxtLink>
        </nav>
        <!-- Here nuxt will replace page content -->
        <slot></slot> 
    </div>
</template>
