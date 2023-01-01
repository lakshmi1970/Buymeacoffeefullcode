<template>
  <NavBar />
  <BannerModel />
  <ReImagining />
  <KickStart />
  <OnboardUsers />
  <EngageCommit />
  <HelpImporove />
  <OpenEnterprise />
  <FooTer />
</template>

<script setup>
import NavBar from './components/NavBar.vue';
import FooTer from './components/FooTer.vue';
import OpenEnterprise from './components/OpenEnterprise.vue';
import ReImagining from './components/ReImagining.vue';
import BannerModel from './components/BannerModel.vue';
import KickStart from './components/KickStart.vue';
import OnboardUsers from './components/OnboardUsers.vue';
import HelpImporove from './components/HelpImporove.vue';
import EngageCommit from './components/EngageCommit';
</script>

<style src="./assets/tailwind.css" />
<style src="./assets/css/main.css" />
<style>
    h1, h2 {
        font-family: "BelyDisplay";
        line-height: 64px;
    }
    h1 {
        font-size: 64px;
        line-height: 80px;
    }
</style>