<template>
    <section id="hero" class="hero is-medium">
        <div class="hero-head">
            <b-navbar>
                <template slot="brand">
                    <b-navbar-item >
                        
                        <img
                            src="https://www.eca-vaud.ch/extdpre/f43/img/ecalogo-sans-texte.svg"
                            alt="Lightweight UI components for Vue.js based on Bulma"
                            >
        
                    </b-navbar-item>
                     <b-navbar-item >
                        
                
                        
                        <h3 class="logo has-text-green is-size-4">Developper ressources</h3>
                    </b-navbar-item>
                </template>
                <template slot="end">
                    <b-navbar-item tag="div">
                        <div class="buttons">
                            <a class="a-menu is-size-7 navbar-item">
                                home
                            </a>
                            <a class="a-menu is-size-7 navbar-item">
                                about
                            </a>
                            <a class="a-menu is-size-7 navbar-item">
                                services
                            </a>
                            <a class="a-menu is-size-7 navbar-item">
                                contact
                            </a>
                        </div>

                    </b-navbar-item>
                </template>
            </b-navbar>
        </div>
        <div class="hero-body">
            <div class="container">
                <h1 class="has-text-green is-size-1 is-size-3-mobile">
                    Developper service
                </h1>
                <p class="has-text-green">
                    Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut 
                    labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum.
                </p>
                <button class="btn has-text-white has-company-bg is-size-7 a-menu">
                    Get started
                </button>
               
            </div>
        </div> 
    </section>
</template>

<style>
@media(min-width: 1024px) {
    .hero-body {
        background-image: url('../assets/img/logo.png');
        background-size: 30%;
        background-position: 80% 50%;
        background-repeat: no-repeat;
    }
    .hero-body p {
        width: 600px;
    }
}
</style>

<script>
export default {
    name: 'Navbar',
}
</script>