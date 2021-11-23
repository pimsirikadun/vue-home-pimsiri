<template>
  <div class="w3-row">
    <div class="w3-half w3-container">
        <h1><b>PROFILE</h1>
      <img
        :src="`https://reg.buu.ac.th/registrar/getstudentimage.asp?id=61160223`"
      />
    </div>

    <br>
    <br>
    <br>
    <br>
      <p>
      <h2><u>EDUCATION</u></h2>
       <b>2018 - present<br />
          Burapha University</b><br />
          B.Sc. (Information Technology) Faculty of Informatics <br />
      <b>2012 - 2017<br /></b>
         Art & Math, Suansriwittaya School, Langsuan Chumphum 
      </p>
  </div>

  <div class="w3-row">
    <div class="w3-half w3-container">
      <h2>Miss Pimsiri Kadun</h2>
    </div>
  </div>

  <div class="w3-row">
    <div class="w3-half w3-container">
         <h2><u>ABOUT ME</u></h2>
         <p>Hello, my name is Pimsiri Kadun, call me Pim. <br />
         Born on December 30, 1999, now I'm 21 years old. <br />
         Project experience Building a website with HTML, <br />
         PHP, CSS, Javascript and using Huawei Cloud.
         <br />
         <br />
         <br />

        <h2><u>CONTACT INFORMATION</u></h2>
        <p> Adress : 93 Village 12, Hadyay, Lang suan, Chumphon 86110<br />
         Tel : 0936844195
         </p>
    </div>
    
    <div>
      <h2><u>SKILL</u></h2>
       <b>Ability to use the program</b><br />
          HTML, Java, R, Python, PHP and CSS<br />
      <b>Ability to use software<br /></b>
         Microsoft Word, Microsoft Excel, Microsoft Power point, Docker and My SQL
      </p>
       <b>Ability to use computer tools<br /></b>
         Git hub, Eclipse Java, Vs Code, R studio and GUN Octave
      </p>
    </div>
    <br>

    <router-link :to="{ name: 'contact'}">
    <button>Contact</button>
    </router-link>
    
  </div>
</template>

<script>

export default {
  name: 'Profile',
};
</script>

<style>
</style>
