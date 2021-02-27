<template>
  <div class="container">
    <div class="media mt-4">
      <div class="media-body m-2">
        <h5 class="align-items-center mt-2">Links</h5>
        <p>Hallo! Ich bin Schmaik, 14 Jahre aus Hannover. <br> Hier findest du alle meine Links!</p>
      </div>
    </div>
    <div class="mt-4">
      <Link text="Fly or Die" icon="bi-controller" href="https://play.google.com/store/apps/details?id=com.Schmaik.FlyorDie"/>
      <Link text="Mein Discordserver" icon="bi-discord" href="https://discord.gg/gdgQGpD"/>
      <hr/>
      <Link text="Tiktok @schmaiiik" icon="bi-camera" href="https://www.tiktok.com/@schmaiiik" class="mt-2"/>
      <Link text="Instagram @derschmaik" icon="bi-instagram" href="https://www.instagram.com/derschmaik/"/>
      <Link text="Youtube @schmaik" icon="bi-youtube" href="https://www.youtube.com/channel/UCM7hqabymJChRgU8fUdWYxw"/>
    </div>
  </div>
</template>

<script>
import Link from '@/components/Link.vue';

export default {
  name: 'Home',
  components: {
    Link,
  },
};
</script>
