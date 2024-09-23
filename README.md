<style>
  body {
    margin: 0;
    padding: 0;
    min-width: 500px;
    height: 1000px;
  }

  .container {
    width: 650px;
/*     height: 400px; */
    margin: 0 auto;
    overflow: auto;
  }

  .nav-links {
    font-size: 16px;
    text-align: center;
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 15px;
    margin-bottom: 20px;
  }
  
  .nav-links a {
    text-decoration: none;
    font-weight: bold;
  }
  
  .content {
    display: flex;
    flex-wrap: wrap;
    align-items: flex-start;
    gap: 20px;
  }
  
  .profile-img {
    width: 200px;
    height: auto;
  }
  
  .bio {
    flex: 1;
    min-width: 280px;
    font-size: 16px;
  }

  hr {
    width: 100%;
  }
</style>

<div class="container">
  <div class="nav-links">
    <a href="https://shaanpakala.github.io/resume.pdf" target="_blank">Resume</a>
    <a href="https://www.linkedin.com/in/shaan-pakala-b91024210/" target="_blank">LinkedIn</a>
    <a href="https://github.com/shaanpakala" target="_blank">GitHub</a>
    <a href="https://shaanpakala.github.io/Projects/" target="_blank">Projects</a>
    <a href="mailto:shaan.pakala@gmail.com">Email</a>
  </div>

  <hr>

  <div class="content">
    <img class="profile-img" src="images/picture_of_me.jpg" alt="Shaan Pakala">
    <p class="bio">
      Hello! My name is Shaan Pakala. I am a fourth year <a href="https://datascience.ucr.edu/">Data Science & Engineering</a> (B.S.) student at the University of California, Riverside. During my time here, I have been an <a href="https://www.nsf.gov/awardsearch/showAward?AWD_ID=2244480&HistoricalAwards=false">NSF REU</a> summer research intern, which resulted in a first author paper submission to <a href="https://www3.cs.stonybrook.edu/~ieeebigdata2024/" target="_blank">IEEE Big Data 2024</a> (under review). This was under the supervision of Professors <a href="https://www.cs.ucr.edu/~epapalex/">Vagelis Papalexakis</a>, <a href="https://sites.google.com/view/jiachen-research/home">Jia Chen</a>, and <a href="https://www.cs.ucr.edu/~tsotras/">Vassilis Tsotras</a>, and we are now working on extending this work. I am also currently a bioinformatics research assistant with Professor <a href="https://www.cs.ucr.edu/~stelo/">Stefano Lonardi</a>.
    </p>
  </div>
</div>
