<template>
  <h1>Jobs</h1>
  <div v-for="job in jobs" :key="job.id">
    <h2>{{ job.title }}</h2>
  </div>
</template>

<script>
export default {
data() {
    return {
        jobs: [
            { title: 'UX designer', id: 1, details: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.' },
            { title: 'Software Engineer', id: 2, details: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.' },
            { title: 'Graphic Designer', id: 3, details: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.' },
            { title: 'Data Scientist', id: 4, details: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.' },
            { title: 'Product Manager', id: 5, details: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.' }
        ]
    }
}
}
</script>

<style>

</style>