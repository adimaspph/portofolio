<template>
    <Profile></Profile>
    <AboutMe></AboutMe>
    <Project></Project>
    <Skill></Skill>
    <Contact></Contact>
</template>

<script>
import AboutMe from '../components/AboutMe.vue';
import Header from '../components/Header.vue';
import Profile from '../components/Profile.vue';
import Project from '../components/Project.vue';
import Contact from '../components/Contact.vue';
import Footer from '../components/Footer.vue';
import Skill from '../components/Skill.vue';


export default {
    name: "Home",
    components: { Header, Profile, AboutMe, Project, Contact, Footer, Skill }
}
</script>
