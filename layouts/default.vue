<script setup lang="ts">
const route = useRoute()

const links = [{
  label: 'About',
  avatar: {
    src: 'https://media.licdn.com/dms/image/D4E03AQFFhycQFzuD4w/profile-displayphoto-shrink_200_200/0/1664346326892?e=1714608000&v=beta&t=Wm9Abo41aZOtLG4Gsb3S4ZYDupSg3papM57qu2GMWbo'
  },
  to: '/'
  
}, {
  label: 'Contact',
  icon: 'i-heroicons-phone',
  to: '/contact'
}, {
  label: 'Github',
  icon: "i-mdi-github",
  to: `/github`
}]
</script>

<template>
  <UHorizontalNavigation :links="links" :ui="{ active: 'text-primary-500 dark:text-primary-400 before:bg-gray-100 dark:before:bg-gray-800' }"/>
  <slot />
</template>

