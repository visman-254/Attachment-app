<template>
    <div class="wrapper"> 
        <div class="content"> 
        <h1 class="header">About Us</h1>
        <p>Welcome to Kerio Valley Development Authority, our mission is to create sustainable, inclusive, and vibrant communities that enhance the quality of life for all residents. </p>
    
        <h1> Mission</h1>
        <p>To promote conservation and sustainable management of river basin based natural resources through intergrated development for improvement of livelihoods.</p>
        <h1>Vision</h1>
        <p>A prosperous, green and conflict free society</p>
        <h1>Mandate</h1>
        <p>KVDA is mandated by Law (Cap 441) to plan, initiate, co-ordinate and monitor implementation of programmes and projects that transcend administrative boundaries within KVDA’s area of operation. It is also mandated to maintain a liaison between the institutions (KVDA), Government, Private sector and other agencies on matters of development in the area in view of limiting duplication of activities and ensuring best use of Technical, Financial, Human and Natural resources.</p>
            
        <footer/>
    </div>
</div>
  
        
       
    
</template>

<script setup>

</script>

<style  scoped>


.header{
    margin-top: 100px;

}

  
  .wrapper {
    
    
    min-height: 100vh;
    background: url('assets/images/treeplanting.jpg');
    background-size: cover;
    font-family: Arial, Helvetica, sans-serif;
    position: relative;
    color: rgb(0, 0, 0);
   margin-top: 10px;
    
    
    
  }
  
 
  .content {
    flex: 1;
    padding: 20px;
    backdrop-filter: blur(15px);
    padding-top: 10px;
    
  }
  footer {
    background-color: #1640ca;
    color: #753939;
    text-align: center;
    
  }
  h1{
    color: rgb(243, 243, 147);
    font-weight: bolder;
    text-decoration: underline ;
    
  }
  p{
   
    color: #fcfafa
  }
  

</style>