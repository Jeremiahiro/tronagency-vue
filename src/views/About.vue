<template>
    <b-container fluid class="about__container p-0 m-0">
        <div>
            <div>
                <Navbar />
            </div>
            <div class="h-100 flex-1 p-5">
                <Aboutpage />
            </div>
        </div>
        <div class="footer__container">
            <Footer />
        </div>
    </b-container>
</template>
<script>
import Navbar from '../components/Navbar.vue';
import Footer from '../components/Footer.vue';
import Aboutpage from '../components/pages/Aboutpage.vue';

export default {
    name: "About",
    components: { Navbar, Footer, Aboutpage },

    data() {
      return {

      };
    },
}
</script>
<style lang="scss">
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@100;300;500;700&family=Quando&display=swap');

.about__container {
    background-color: #DCDCDC;
    display: flex;
    flex-direction: column;
    min-height: 100vh;
    overflow-x: hidden;
     font-family: 'Poppins', sans-serif;
    .footer__container {
        margin-top: auto;
    }
}
</style>