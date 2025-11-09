<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
    <div>
        <nav class="navbar bg-base-100 shadow-lg mb-8">
            <div class="flex-1">
                <a class="btn btn-ghost text-xl">My App</a>
            </div>
            <div class="flex-none">
                <ul class="menu menu-horizontal px-1">
                    <li><router-link to="/">Home</router-link></li>
                    <li><router-link to="/about">About</router-link></li>
                </ul>
            </div>
        </nav>

        <router-view />
    </div>
</template>
