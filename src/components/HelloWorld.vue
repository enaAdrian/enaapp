<template>
  <div class="hello">
   <b-navbar toggleable type="light" variant="light">
     <div class="container">
        <b-navbar-toggle target="nav_text_collapse"></b-navbar-toggle>
        <b-navbar-brand>ENA.<small>net.pl</small></b-navbar-brand>
        <b-collapse is-nav id="nav_text_collapse">
          <ul class="navbar-nav ml-auto">
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#about">O Nas</a>
            </li>
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#services">Rozwiązania</a>
            </li>
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="#contact">Kontakt</a>
            </li>
          </ul>
        </b-collapse>
      </div>
    </b-navbar>
   <header class="masthead text-center text-white d-flex">
      <div class="container my-auto">
        <div class="row">
          <div class="col-lg-10 mx-auto">
            <h1 class="text-uppercase">
              <strong>{{msg}}</strong>
            </h1>
            <hr>
          </div>
          <div class="col-lg-8 mx-auto">
            <p class="text-faded mb-5">Frima Ena zajmuję się rozwiązaniami informatycznymi</p>
            <a class="btn btn-primary btn-xl js-scroll-trigger" href="#about">Dowiedz się więcej</a>
          </div>
        </div>
      </div>
    </header>
    <section class="bg-primary" id="about">
      <div class="container">
        <div class="row">
          <div class="col-lg-8 mx-auto text-center">
            <h2 class="section-heading text-white">Jesteśmy tym czego potrzebujesz</h2>
            <hr class="light my-4">
            <p class="text-faded mb-4">Firma ENA zajmuję się od ponad 2 lat realizacją indywidualnie dopasowanych rozwiązań informatyczynych, stale poszerzając gamę swoich usług.</p>
            <a class="btn btn-light btn-xl js-scroll-trigger" href="#services">Zobacz!</a>
          </div>
        </div>
      </div>
    </section>
    <section id="services">
     <div class="container">
       <div class="row">
         <div class="col-lg-12 text-center">
           <h2 class="section-heading">Oferta</h2>
           <hr class="my-4">
         </div>
       </div>
     </div>
     <div class="container">
       <div class="row">
         <div class="col-lg-3 col-md-6 text-center">
           <div class="service-box mt-5 mx-auto">
             <icon name="code" scale="3"></icon>
             <h3 class="mb-3">{{www}}</h3>
             <p class="text-muted mb-0">Profesjonalne tworzenie responsywnych stron internetowych oraz zarządzanie treścią</p>
           </div>
         </div>
         <div class="col-lg-3 col-md-6 text-center">
           <div class="service-box mt-5 mx-auto">
             <icon name="desktop" scale="3"></icon>
             <h3 class="mb-3">{{web}}</h3>
             <p class="text-muted mb-0">Realizacja aplikacji internetowych dostosowanych do Twoich potrzeb, w tym sklepow internetowych</p>
           </div>
         </div>
         <div class="col-lg-3 col-md-6 text-center">
           <div class="service-box mt-5 mx-auto">
             <icon name="mobile" scale="3"></icon>
             <h3 class="mb-3">{{mob}}</h3>
             <p class="text-muted mb-0">Tworzenie aplikacji mobilnych dla systemu Android</p>
           </div>
         </div>
         <div class="col-lg-3 col-md-6 text-center">
           <div class="service-box mt-5 mx-auto">
             <icon name="code-fork" scale="3"></icon>
             <h3 class="mb-3">{{out}}</h3>
             <p class="text-muted mb-0">Realizacja modułów oraz całych projektów</p>
           </div>
         </div>
       </div>
     </div>
   </section>
   <section class="bg-dark text-white">
      <div class="container text-center">
        <h2 class="mb-4">W celu omowienia szczegółów zapraszamy do kontaktu!</h2>
        <a class="btn btn-light btn-xl sr-button" href="#contact">{{contact}}</a>
      </div>
    </section>
    <section id="contact">
     <div class="container">
       <div class="row">
         <div class="col-lg-8 mx-auto text-center">
           <h2 class="section-heading">{{contact}}</h2>
           <hr class="my-4">
           <p class="mb-5">W celu przeprowadzenia wyceny zapraszamy do kontaktu telefoniczengo, bądź e-mail!</p>
         </div>
       </div>
       <div class="row">
         <div class="col-lg-4 ml-auto text-center">
           <icon name="phone" scale="2"></icon>
           <p>+48 693 825 875</p>
         </div>
         <div class="col-lg-4 mr-auto text-center">
           <icon name="envelope" scale="2"></icon><p>
             <a href="mailto:biuro@ena.net.pl">biuro@ena.net.pl</a>
           </p>

         </div>
       </div>
     </div>
   </section>
  </div>
</template>

<script>
import Icon from 'vue-awesome/components/Icon'

export default {
  name: 'HelloWorld',
  components: Icon,
  data () {
    return {
      msg: 'ENA - Rozwiązania IT dla Twojej Firmy',
      contact: 'Kontakt !',
      www: 'Strony www',
      web: 'Aplikacje webowe',
      mob: 'Aplikacje mobilne',
      out: 'Outsourcing IT'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
