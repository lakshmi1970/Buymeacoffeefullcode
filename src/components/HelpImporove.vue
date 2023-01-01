<script setup>

 const categories = [
    {
      title: 'Ideate a list of features based on the Sociocracy model',
      desc: 'We’re looking for someone interested in business theory and research that’ll help us bridge the gap between our s...'
    },
    {
      title: 'Update documentation with FAQs',
      desc: 'Review our community chat for the most frequently asked questions and document answers for our product docs.'
    },
    {
      title: 'Tutorial video series',
      desc: 'Create a series of video tutorials that cover everything from start to finish on using Open Enterprise.'
    },
  ]
</script>

<template>
    <section>
        <div class="container-fluid xl:px-14 px-4 text-center">
            <h2 class="xl:text-5xl text-3xl leading-normal">Help us improve Open Enterprise</h2>
            <p class="mt-6 xl:w-4/6 mx-auto">As an Open Enterprise ourselves, we are actively looking for new talent to join our mission of improving and delivering the Open Enterprise model to the world. Apply for open tasks and earn a stake in our success..</p>
            <div class="lg:flex items-start gap-6 mt-12 text-left grid grid-cols-1">
                <div v-for="category of categories" :key="category.title" class="help-card card px-6 py-8 w-full rounded-lg overflow-hidden shadow-md bg-white">
                    <h3 class="font-bold text-lg mb-4 tracking-widest">{{ category.title }}</h3>
                    <p class="text-base mb-0 tracking-widest">{{ category.desc}}</p>
                    <ul class="flex items-center justify-between mt-4">
                        <li class="bg-secondary text-white px-4 py-2 text-base rounded-full tracking-widest">5 AUT</li>
                        <li class="tracking-widest">Apply by May 18</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>
</template>

<style>
    .help-card {
        font-family: "LatoRegular";
    }
</style>