<template>
  <div class="container-full">
    <div class="video">
      <video class="video-background1" autoplay="autoplay" loop="loop">
        <source src="/static/regroupe.mp4"  type="video/mp4"  />
        Your browser doesn't support video API
      </video>
      <h4> UN REGROUPEMENT PARTAGE</h4>
      <p>Depuis la chute du mur, Berlin Est est déserté et se révèle comme un lieu propice aux raves et aux soirées interminables. Plus d’Est, plus d’Ouest … juste un lieu pour faire la fête et se sentir libre.</p>
    </div>
    <router-link :to="{name: 'chapters.page10'}" class="sous-page-link-9-1">EN SAVOIR PLUS</router-link>
    <router-link :to="{name: 'chapters.page11'}" class="sous-page-link-9-2">EN SAVOIR PLUS</router-link>
  </div>
</template>

<script>
  export default {
    name: 'chapter4'
  }
</script>
