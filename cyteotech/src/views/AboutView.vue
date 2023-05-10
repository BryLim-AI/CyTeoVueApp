<template>
  <div class="about">
   
    <h2>Contents</h2>
    <div class="container">

      <a href="" target="_blank">
        <p class="contentEdit"></p>
      </a>

    </div>

  </div>
</template>

<style>

h2{
  padding: 20px;
  color:aliceblue;
  font-family:fantasy;
  font-size: 2rem;
}

.container {
background: rgba( 255, 255, 255, 0.25 );
box-shadow: 0 8px 32px 0 rgba( 31, 38, 135, 0.37 );
backdrop-filter: blur( 4px );
-webkit-backdrop-filter: blur( 4px );
border-radius: 10px;
border: 1px solid rgba( 255, 255, 255, 0.18 );
width:550px;
height:470px;
}


@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    align-items: center;
  }
}
</style>
