<template>
  <div class="home">
    <Alert />
    <div class="mx-5">
      <Navbar />
      <Hero />
      <Divider />
      <Section title="About Us" subtitle="Colinear is a peer-to-peer (P2P) network, not a centralized financial institution. Its code is open for viewing by auditors and contributions from the general public." />
      <DividerLight />
      <Technology />
      <DividerLight />
      <Roadmap />
    </div>
    <Footer />
  </div>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>
