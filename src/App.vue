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
  width: 100%;
  height: 100%;
  font-family: 'Merriweather', 'Helvetica Neue', Arial, sans-serif; }
#app hr {
  max-width: 50px;
  border-width: 3px;
  border-color: #B56357; }
#app hr.light {
  border-color: #fff; }
#app a {
  color: #192231;
  -webkit-transition: all 0.2s;
  -moz-transition: all 0.2s;
  transition: all 0.2s; }
#app a:hover {
    color: #B56357; }
#app h1,
h2,
h3,
h4,
h5,
h6 {
  font-family: 'Open Sans', 'Helvetica Neue', Arial, sans-serif; }
#app .bg-primary {
  background-color: #494e68 !important; }
#app .bg-dark {
  background-color: #192231 !important; }
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
  background-color: #B56357;
  color:#fff;
  border-color: #D3CEC3; }
#app .btn-primary:hover, .btn-primary:focus, .btn-primary:active {
    color: #fff;
    background-color: #98878F !important; }
#app .btn-primary:active, .btn-primary:focus {
    box-shadow: 0 0 0 0.2rem rgba(240, 95, 64, 0.5) !important; }
#app #contact a{
      color:#B56357;
    }
</style>
