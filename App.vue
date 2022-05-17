<template>
  <div id="main-container">
    <header>
      <nav>
        <div class="mobile hide">
          <div class="header">
            <button id="bmenu"><span class="material-symbols-outlined">menu</span></button>
            <router-link to="/about"><a href="#" >Microsofst</a></router-link>
          </div>
          <div class="links">
            <a href="#">Game Pass</a>
            <a href="#">Games</a>
            <a href="#">Devices</a>
            <a href="#">Cloud Gaming</a>
            <a href="#">Comunnity</a>
            <a href="#">Support</a>
            <a href="#">My Xbox</a>
            <a href="#">All Microsoft</a>
            <a href="#">Search</a>
          </div>
          <div>
            <router-link to="/home"><a href="#" ><span class="material-symbols-outlined">
              home
            </span></a></router-link>
            <router-link class="none" to="/about"><a href="#" >Abouta</a></router-link>
            <router-link to="/contact"><a href="#" >Contacts></a></router-link>
          </div>
        </div>
        <ul>
          <li><a href="#">YouDev</a></li>
          <router-link class="none link" to="/"><li><a  class="link">Home</a></li></router-link>
          <router-link class="none" to="/about"><li><a  class="link">About</a></li></router-link>
          <li class="more">
            <a href="#" class="link hide" id="bmore">More</a>
            <div class="menu hide">
              <a href="#" >Game Pass</a>
              <a href="#" >Games</a>
              <a href="#" >Devices</a>
              <a href="#" >Support</a>
              <a href="#" >My Xbox</a>
            </div>
          </li>
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

</template>

<style>

</style>
