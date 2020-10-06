# asher-musings
<style>
  .flex-contain {
    display: flex;
  }
  #img {
    display:flex;
    align-items: center; 
  }
 .nav-link {
  border: none;
  outline: none;
  padding: 10px 20px;
  background-color: #f1f1f2;
  cursor: pointer;
}
  .nav-link:hover {
  background-color: #777;
  color: black;
}
  header {
  text-align: center;
  padding: 10px 50px;
  }
#form {
   
  }
  footer {
 background-color: #f1f1f2;
   
  } 
  @media (max-width: 600px) {
  }
</style>


<body>
<header id="header">
  <header>
 <img id="header-img" src="https://img.hmn.com/fit-in/450x253/filters:upscale()/stories/2018/08/344051.jpg" alt="cadillac logo"> 
 <nav id="nav-bar">
   <nav>
   <a class="nav-link" href="#features">Features</a>
    <a class="nav-link" href="#safety">Safety</a>
    <a class="nav-link" href="#contact">Contact</a>
</nav>
</header>
  <section id="features">
  <h1>Features</h1>
  <p>Cadillac Live provides you with a real-time, one-on-one virtual tour of the unmistakable 2020 XT4 from the comfort of anywhere. Once your session begins, you’ll be matched with a Live ambassador who can help answer any questions you might have about the XT4, such as innovative technologies like the available hands-free power liftgate and the Rotary Infotainment Controller, or advanced safety features like Rear Camera</p>
  <iframe id="video" width="420" height="315"
src="https://www.youtube.com/embed/UKTBIZkqKB4">
</iframe>
    </section>
  <section id="safety">
    <h2>Saefty</h2>
  <p>Automatic Emergency Braking<p><p>Rear Camera Mirror</p>
<p>Safety Alert Seat</p>
<p>Adaptive Cruise Control</p>
<p>Head-up Display</p>
    </section>
  <section id="contact">  
    <h2>Contact</h2>
  <form id="form" action="https://www.freecodecamp.com/email-submit">
  <input type="email" id="email" name="email" required button type="submit" placeholder="joe@example.com"><br>
    <input id="submit" type="submit">
   </form>
    </section>
    </body>



