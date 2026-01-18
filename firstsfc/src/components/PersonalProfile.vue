<!DOCTYPE html>
<html>
<head>
<title>My first Vue page</title>
<link rel="stylesheet" href="css/style.css?version=0.3">
<link rel="stylesheet" href="css/images.css">
</head>
<body>
 
<<div class="grid-container">

    <header class="header">
      <h1>My Personal Profile</h1>
    </header>

   <nav class="menu">
  <ul>
    
    <main class="content">
      <section id="about">
        <h2>About Me</h2>
        <p>Hi! I’m currently a 2nd year college student taking up Information Technology.</p>
      </section>

      <section id="education">
        <h2>Education / Achievements</h2>
        <p>°˖➴ Graduated high school (Year 12). Now in college year 2.</p>
      </section>

      <section id="experience">
        <h2>IT Experience</h2>
        <p>°˖➴ Worked with Outsystems and other technologies.</p>
      </section>

      <section id="hobbies">
        <h2>Hobbies & Interests</h2>
        <ul>
          <p>°˖➴ Competitive Video Games</p>
          <p>°˖➴ Perfume</p>
          <p>°˖➴ Spending time with my wife ❤️</p>
        </ul>
      </section>
    </main>

  

  </ul>
</nav>


    <main class="content">
      
    </main>

    <aside class="facts">
      <h2>Goals in Life / Dreams</h2>
      <ul>
        <p>°˖➴ Build a stable career to support my family</p>
        <p>°˖➴ Learn to cook</p>
        <br>
        <br>
        <br>
        <br>
        <br>
        <h2>I hope you have a fnatastic day!</h2>
      <h2>↩</h2>
      </ul>
    </aside>

    <footer class="footer">
      <h3>Picture Gallery</h3>
      <img src="https://dbw3zep4prcju.cloudfront.net/animal/05d9b271-997e-4768-8d10-e56fe19f0e6f/image/ce0d4f60-b199-41c3-8949-2b3ce49e9afd.jpg" alt="A cute cat" width="300" />
      <p>&copy; 2026 My Personal Profile</p>
    </footer>

  </div>
<div id="app">

  {{ message }}
</div>



<div id="app2">

  <div>
    <img v-for="x in manyFoods" v-bind:src="x">
  </div>

</div>

 
<script src="https://unpkg.com/vue@3/dist/vue.global.js"></script>
 
<script src="js/vue.js"></script>
<script src="js/images.js"></script>
 

  <div class="banner">
    <p>ฅ ฅ Welcome to my page! I tried my hardest — please enjoy (•˕ •マ.ᐟ</p>
  </div>

</body>
</html>