<template>
    <section id="footer" class="section has-green-bg">

         <div class="container">
            <div class="columns">
                <div class="column">
                    <img class="feature-img" src="https://www.eca-vaud.ch/templates/eca/img/logos/eca-logo-footer.svg" alt="feature" />
                </div>
                <div class="column has-text-left">
                    <p>
                        <strong>
                            Etablissement d'assurance contre l'incendie et les éléments naturels du Canton de Vaud
                        </strong>
                        <br>
                        Av. du Général-Guisan 56
                        <br>
                        CP 300 - CH-1009 Pully
                        <br>
                        T. <a href="tel:++41 21 316 43 18 ">++41 21 316 43 18</a>
                    </p>
                  
                </div>
            </div>
        </div>

       
    </section>
</template>
<script>
export default {
    name: 'Footer',
    props: {
        year: String
    },
    data(){
        return {
            msg:""
        }
    }
}
</script>

<style>
#footer {
    margin-top: 1.875rem;
    padding-top: 2.875rem;
    padding-bottom: 1rem;
    background-color: #C6C6C6;
}
</style>