<script setup>
import Navigation from '../components/Navigation.vue';
import AboutMe from '../components/AboutMe.vue';
import Projects from '../components/Projects.vue';
import HomeButton from '../components/HomeButton.vue';


</script>

<template>
    <div class="p-4">
        <Navigation />
        <div class="md:hidden">
            <HomeButton/>
        </div>

        <div class="min-h-[70vh]">
            <AboutMe/>
            <Projects/>

        </div>
        <Mainfooter />
    </div>
</template>