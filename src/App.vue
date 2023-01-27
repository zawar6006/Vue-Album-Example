<script setup>
import PhotoCard from "./components/PhotoCard.vue";
</script>

<template>
  <header>
    <div class="navbar navbar-dark bg-dark shadow-sm">
      <div class="container d-flex justify-content-between">
        <a class="navbar-brand d-flex align-items-center" href="#"
          ><i class="fa fa-camera"></i><strong>&nbsp;My Album </strong></a
        >
      </div>
    </div>
  </header>
  <main role="main">
    <section class="jumbotron text-center">
      <div class="container">
        <h1>Album Rattikon</h1>
        <p class="lead text-muted"><br />Something just snaped.<br /></p>
      </div>
    </section>
    <div class="album py-5 bg-light">
      <div class="container">
        <div class="row">
          <PhotoCard image="https://picsum.photos/200/300?random=0" />
          <PhotoCard image="https://picsum.photos/200/300?random=1" />
          <PhotoCard image="https://picsum.photos/200/300?random=2" />
          <PhotoCard image="https://picsum.photos/200/300?random=3" />
          <PhotoCard image="https://picsum.photos/200/300?random=4" />
          <PhotoCard image="https://picsum.photos/200/300?random=5" />
          <PhotoCard image="https://picsum.photos/200/300?random=6" />
          <PhotoCard image="https://picsum.photos/200/300?random=7" />
          <PhotoCard image="https://picsum.photos/200/300?random=8" />
        </div>
      </div>
    </div>
  </main>
  <footer class="text-muted">
    <div class="container">
      <p class="float-right"><a href="#">Back To Top</a></p>
      <p>
        Album example is &copy; Bootstrap, but please download and customize it for
        yourself!
      </p>
      <p>
        New to Bootstrap?
        <a href="https://getbootstrap.com/">Visit the homepage</a> or read our
        <a href="/docs/4.4/getting-started/introduction/">getting started guide</a>.
      </p>
    </div>
  </footer>
</template>

<style scoped></style>
