<script setup>
import Navbar from './components/Navbar.vue';
import Hero from './components/Hero.vue';
import About from './components/About.vue';
import Product from './components/Product.vue';
import Contact from './components/Contact.vue';
import Testimonials from './components/Testimonials.vue';
import Footer from './components/Footer.vue';
</script>


<template>
  <header>
    <Navbar />
  </header>

  <main>
    <section>
      <Hero />
    </section>

    <section>
      <About />
    </section>

    <section>
      <Product />
    </section>

    <section>
      <Contact />
    </section>

    <section>
      <Testimonials />
    </section>
  </main>

  <footer>
    <Footer />
  </footer>
</template>

<style>
section {
  background-color: white;
}
</style>