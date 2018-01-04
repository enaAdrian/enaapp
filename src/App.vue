<template>
  <div id="app">
    <HelloWorld/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style>
#app {
  font-family: 'Open-Sans', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
#app body,
html {
  width: 100%;
  height: 100%; }
#app body {
  font-family: 'Merriweather', 'Helvetica Neue', Arial, sans-serif; }
#app hr {
  max-width: 50px;
  border-width: 3px;
  border-color: #F05F40; }
#app hr.light {
  border-color: #fff; }
#app a {
  color: #F05F40;
  -webkit-transition: all 0.2s;
  -moz-transition: all 0.2s;
  transition: all 0.2s; }
#app a:hover {
    color: #f05f40; }
#app h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: 'Open Sans', 'Helvetica Neue', Arial, sans-serif; }
#app .bg-primary {
  background-color: #F05F40 !important; }
#app .bg-dark {
  background-color: #212529 !important; }
#app .text-faded {
  color: rgba(255, 255, 255, 0.7); }
#app section {
  padding: 8rem 0; }
#app .section-heading {
  margin-top: 0; }
#app ::-moz-selection {
  color: #fff;
  background: #212529;
  text-shadow: none; }
#app ::selection {
  color: #fff;
  background: #212529;
  text-shadow: none; }
#app img::selection {
  color: #fff;
  background: transparent; }
#app img::-moz-selection {
  color: #fff;
  background: transparent; }
#app body {
  -webkit-tap-highlight-color: #212529; }
#app #mainNav {
  border-bottom: 1px solid rgba(33, 37, 41, 0.1);
  background-color: #fff;
  font-family: 'Open Sans', 'Helvetica Neue', Arial, sans-serif;
  -webkit-transition: all 0.2s;
  -moz-transition: all 0.2s;
  transition: all 0.2s; }
#app #mainNav .navbar-brand {
    font-weight: 700;
    text-transform: uppercase;
    color: #F05F40;
    font-family: 'Open Sans', 'Helvetica Neue', Arial, sans-serif; }
#app #mainNav .navbar-brand:focus, #mainNav .navbar-brand:hover {
      color: #f05f40; }
#app #mainNav .navbar-nav > li.nav-item > a.nav-link,
  #mainNav .navbar-nav > li.nav-item > a.nav-link:focus {
    font-size: .9rem;
    font-weight: 700;
    text-transform: uppercase;
    color: #212529; }
#app #mainNav .navbar-nav > li.nav-item > a.nav-link:hover,
    #mainNav .navbar-nav > li.nav-item > a.nav-link:focus:hover {
      color: #F05F40; }
#app #mainNav .navbar-nav > li.nav-item > a.nav-link.active,
    #mainNav .navbar-nav > li.nav-item > a.nav-link:focus.active {
      color: #F05F40 !important;
      background-color: transparent; }
#app #mainNav .navbar-nav > li.nav-item > a.nav-link.active:hover,
      #mainNav .navbar-nav > li.nav-item > a.nav-link:focus.active:hover {
        background-color: transparent; }
@media (min-width: 992px){
  #app #mainNav {
      border-color: transparent;
      background-color: transparent; }
  #app #mainNav .navbar-brand {
        color: rgba(255, 255, 255, 0.7); }
  #app #mainNav .navbar-brand:focus, #mainNav .navbar-brand:hover {
          color: #fff; }
  #app #mainNav .navbar-nav > li.nav-item > a.nav-link {
        padding: 0.5rem 1rem; }
  #app #mainNav .navbar-nav > li.nav-item > a.nav-link,
      #mainNav .navbar-nav > li.nav-item > a.nav-link:focus {
        color: rgba(255, 255, 255, 0.7); }
  #app  #mainNav .navbar-nav > li.nav-item > a.nav-link:hover,
        #mainNav .navbar-nav > li.nav-item > a.nav-link:focus:hover {
          color: #fff; }
  #app #mainNav.navbar-shrink {
        border-bottom: 1px solid rgba(33, 37, 41, 0.1);
        background-color: #fff; }
  #app #mainNav.navbar-shrink .navbar-brand {
          color: #F05F40; }
  #app #mainNav.navbar-shrink .navbar-brand:focus, #mainNav.navbar-shrink .navbar-brand:hover {
            color: #f05f40; }
  #app #mainNav.navbar-shrink .navbar-nav > li.nav-item > a.nav-link,
        #mainNav.navbar-shrink .navbar-nav > li.nav-item > a.nav-link:focus {
          color: #212529; }
  #app #mainNav.navbar-shrink .navbar-nav > li.nav-item > a.nav-link:hover,
          #mainNav.navbar-shrink .navbar-nav > li.nav-item > a.nav-link:focus:hover {
            color: #F05F40; }
}
#app header.masthead {
  padding-top: 10rem;
  padding-bottom: calc(10rem - 56px);
  background-image: url('assets/header.jpg');
  background-position: center center;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover; }
#app header.masthead hr {
    margin-top: 30px;
    margin-bottom: 30px; }
#app header.masthead h1 {
    font-size: 2rem; }
#app header.masthead p {
    font-weight: 300; }
@media (min-width: 768px) {
    #app header.masthead p {
      font-size: 1.15rem; } }
  @media (min-width: 992px) {
    #app header.masthead {
      height: 100vh;
      min-height: 650px;
      padding-top: 0;
      padding-bottom: 0; }
      #app header.masthead h1 {
        font-size: 3rem; } }
  @media (min-width: 1200px) {
    #app header.masthead h1 {
      font-size: 4rem; } }
#app .service-box {
  max-width: 400px; }
#app .text-primary {
  color: #F05F40 !important; }
#app .btn {
  font-weight: 700;
  text-transform: uppercase;
  border: none;
  border-radius: 300px;
  font-family: 'Open Sans', 'Helvetica Neue', Arial, sans-serif; }
#app .btn-xl {
  padding: 1rem 2rem; }
#app .btn-primary {
  background-color: #F05F40;
  border-color: #F05F40; }
#app .btn-primary:hover, .btn-primary:focus, .btn-primary:active {
    color: #fff;
    background-color: #ee4b28 !important; }
#app .btn-primary:active, .btn-primary:focus {
    box-shadow: 0 0 0 0.2rem rgba(240, 95, 64, 0.5) !important; }
</style>
