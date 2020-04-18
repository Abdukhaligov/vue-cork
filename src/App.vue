<template>
  <div id="app">
    <NavBar />
    <ToDoList />
  </div>
</template>

<script>

  import './assets/assets/css33d1.css?family=Nunito:400,600,700';
  import './assets/bootstrap/css/bootstrap.min.css';
  import './assets/assets/css/plugins.css';
  import './assets/plugins/editors/quill/quill.snow.css';
  import './assets/assets/css/apps/todolist.css';

  import $ from 'jquery'
  import 'popper.js';
  import 'bootstrap'
  import './assets/assets/js/ie11fix/fn.fix-padStart.js';


  import NavBar from './components/NavBar.vue'
  import ToDoList from './components/ToDoList.vue'

  export default {
    rules:{
        'no-unused-vars': 'off'
    },
    name: 'App',
    components: {
      NavBar,
      ToDoList,
    },
    mounted() {

      $('.scrollTop').click(function () {
        $("html, body").animate({scrollTop: 0});
      });


      $('.navbar .dropdown.notification-dropdown > .dropdown-menu, .navbar .dropdown.message-dropdown > .dropdown-menu ').click(function (e) {
        e.stopPropagation();
      });

      $('.bs-tooltip').tooltip();

      $('.bs-popover').popover();


      $('.t-dot').tooltip({
        template: '<div class="tooltip status rounded-tooltip" role="tooltip"><div class="arrow"></div><div class="tooltip-inner"></div></div>'
      });


    }
  }
</script>

<style>

</style>
