<template>
    <main class="user-layout">
        <article class="sidebar">
            <p>Dashboard</p>
            <p>Settings</p>
        </article>

        <section>
            <!-- Here nuxt will inject pages -->
            <slot></slot>
        </section>
    </main>
</template>

<style>
    .sidebar{
        display: flex;
        flex-direction: column;
        padding-right: 20px;
    }
    .user-layout{
        display: flex;
        
    }
</style>