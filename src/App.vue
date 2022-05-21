<template>
  <div id="main-container">
    <header>
      <nav>
        <ul class="fixed">
          <li><a href="#">YouDev</a></li>
          <router-link class="none link" to="/"><li><a  class="link"><strong>Home</strong></a></li></router-link>
          <router-link class="none" to="/about"><li><a  class="link"><strong>Acerca de</strong></a></li></router-link>
          <router-link class="none link" to="/contact"><li><a  class="link"><strong>Contact</strong></a></li></router-link>
        </ul>
        <ul class="hide">
         <li><a href="#" class="link">Search</a></li>
         <li><a href="#" class="link">Cart</a></li>
         <li><a href="#" class="link">Sing In</a></li>
       </ul>
     </nav>
   </header>

 </div>
 <router-view/>

 <footer>

  <div class="footer">
    <div class="copyright">
      <h5 class="copy-text">&copy; 2022  | Yohendri Becerra</h5>
    </div>
  </div>
</footer>


</template>

<style>

</style>
