<template>
  <footer>
    <section class="callout">
      <h2>"Buy Chibigreens. Be happy."</h2>
      <p>Karan Rami</p>
    </section>
    <app-footer-links />
    <div class="plug">
      <p>
        This project is
        <a href="https://github.com/nicobasile/chibigreens">on github</a>
        and made with love by the Chibigreens DSO-562 Team
      </p>
    </div>
  </footer>
</template>

<script>
import AppFooterLinks from "~/components/AppFooterLinks.vue";

export default {
  components: {
    AppFooterLinks
  }
};
</script>

<style lang="scss" scoped>
.callout {
  width: 100%;
  height: 280px;
  background: url("/greenery.jpg") center center no-repeat;
  background-size: cover;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  color: white;
  h2 {
    padding: 0 30px;
    text-align: center;
  }
}

.plug {
  background: black;
  width: 100%;
  padding: 10px 30px;
  color: white;
  text-align: center;
}

a,
a:visited,
a:active {
  color: #c4c3ec;
  font-weight: bold;
}
</style>