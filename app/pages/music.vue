<template>
  <section class="home">
    <div class="py-24 md:py-36 mx-auto flex flex-wrap flex-col md:flex-row items-center text-xl font-bold">
      <br>
      <h1>Odyn v Kanoe</h1>
      <br>
      <iframe 
      title="Odyn v Kanoe" 
      style="border-radius:12px" 
      src="https://open.spotify.com/embed/artist/5fMNki1cAszN37EYRTVdOc?utm_source=generator" 
      width="100%" 
      height="80" 
      frameBorder="0" 
      allowfullscreen="" 
      allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture"
      ></iframe>

      <br>
      <h1>Kazka</h1>
      <br>
      <iframe 
      style="border-radius:12px" 
      src="https://open.spotify.com/embed/artist/6tnqzaOroG2OtBaSfVJbEw?utm_source=generator" 
      width="100%" 
      height="80" 
      frameBorder="0" 
      allowfullscreen="" 
      allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture"
      ></iframe>

      <br>
      <h1>Tina Karol</h1>
      <br>
      <iframe 
      style="border-radius:12px" 
      src="https://open.spotify.com/embed/artist/0W3C8tSz8ERP2t37m6Ru6r?utm_source=generator" 
      width="100%" 
      height="80" 
      frameBorder="0" 
      allowfullscreen="" 
      allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture"
      ></iframe>

      <br>
      <h1>The Hardkiss</h1>
      <br>
      <iframe 
      style="border-radius:12px" 
      src="https://open.spotify.com/embed/artist/4IJcztNtY5L7G3qK4yu1qt?utm_source=generator" 
      width="100%" 
      height="80" 
      frameBorder="0" 
      allowfullscreen="" 
      allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture"
      ></iframe>

       <br>
      <h1>KALUSH</h1>
      <br>
      <iframe 
      style="border-radius:12px" 
      src="https://open.spotify.com/embed/artist/46rVVJwHWNS7C7MaWXd842?utm_source=generator" 
      width="100%" 
      height="80" 
      frameBorder="0" 
      allowfullscreen="" 
      allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture"
      ></iframe>

       <br>
      <h1>Go_A</h1>
      <br>
      <iframe 
      style="border-radius:12px" 
      src="https://open.spotify.com/embed/artist/4kvCU3MzggM2piZCqvxj0x?utm_source=generator" 
      width="100%" 
      height="80" 
      frameBorder="0" 
      allowfullscreen="" 
      allow="autoplay; clipboard-write; encrypted-media; fullscreen; picture-in-picture"
      ></iframe>

    </div>
  </section>
</template>

<script lang="ts">
import { Component, Vue } from 'nuxt-property-decorator';

@Component({
  // Called to know which transition to apply
  transition() {
    return 'slide-left';
  },
})
export default class Music extends Vue {}
</script>
