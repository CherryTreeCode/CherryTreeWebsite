<script lang="ts">
  import AboutUs from "./pages/AboutUs.svelte";
  import Navbar from "./components/Navbar.svelte";
  import Footer from "./components/Footer.svelte";
</script>

<div id="app" style="min-height: 100vh">
  <Navbar />
  <div style="padding-bottom: 50px">
    <div class="center" style="height: 100%">
      <AboutUs />
    </div>
  </div>
  <Footer />
</div>
