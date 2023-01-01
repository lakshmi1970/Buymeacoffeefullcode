<script setup>

  import reimage1 from "../assets/images/reimage-icon1.svg"
  import reimage2 from "../assets/images/reimage-icon2.svg"
  import reimage3 from "../assets/images/reimage-icon3.svg"

 const categories = [
    {
      title: 'Modern workforce',
      image: reimage1,
      desc: 'Multistakeholder governance aligns employees with the organization’s wider community.'
    },
    {
      title: 'Meritocratic by design',
      image: reimage2,
      desc: 'Tokenized ownership aligns deeply committed individuals with the organization’s success.'
    },
    {
      title: 'Engineered for resilience',
      image: reimage3,
      desc: 'Open Enterprise supports best practices in sociocratic management.'
    },
  ]
</script>

<template>
    <section>
        <div class="container-fluid xl:px-14 px-4 text-center">
            <h2 class="xl:text-5xl text-3xl leading-snug">Reimagining what it means to work</h2>
            <p class="mt-6 xl:w-4/6 mx-auto">Teams and communities using Open Enterprise fundamentally unlock a reality of work that reimagines how people engage in economic opportunity, meeting the demands and expectations of a modern organization.</p>
            <div class="lg:grid grid-cols-3 gap-4 mt-12 flex lg:overflow-none overflow-auto">
                <div v-for="category of categories" :key="category.title" class="card px-6 lg:py-16 py-12 lg:w-full rounded overflow-hidden shadow-md bg-white">
                    <img :src="category.image" alt="category.title" class="mx-auto" />
                    <h3 class="font-bold text-2xl mt-6 mb-4">{{ category.title }}</h3>
                    <p class="text-lg mb-0">{{ category.desc}}</p>
                </div>
            </div>
        </div>
    </section>
</template>

<style scoped>
@media(max-width:1024px){
    .card {
        min-width:300px;
    }
}
</style>