# newprogect-demo
this is my first git repository
<br>
first project ankit kumar sharma
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <script src="https://kit.fontawesome.com/0095b997a7.js" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    
    
    

    <div id="header">
      <div class="container">
        <nav>
          <!-- <img src="Dark Abstract Black Panther Gaming Logo.png" class="logo" /> -->
          <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">Contact</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Services</a></li>
            <li><a href="#">Portfolio</a></li>
           
          </ul>
         
        </nav>
        <div class="header-text">
         
          <h1>
            Hi, I am <span> Ankit kumar sharma</span> <br />
            An aspiring  developer 
          </h1>
        </div>
        
      </div>
    </div>
    <div id="about">
      <div class="container">
        <div class="row">
          <div class="about-col-1">
<img class ="ankit"src="image/1735044953660.jpg" alt="">
          </div>
          <div class="about-col-2">
            <h1 class="sub-title">About me</h1>
            <p>
              Greetings! My name is Ankit kumar sharma, and I am currently pursuing my Bachelor's degree in Computer Science Engineering (B.Tech , 3rd year) from Sandip university madhubani [bihar]. I am passionate about pursuing a career in 
              the field of IT & Software development and have developed a diverse skill set to excel in the industry.
              





            </p>
            <div class="tab-titles active-tab">
              <p class="tab-links active-link" onclick="opentab('skills')">
                skills
              </p>
              <p class="tab-links" onclick="opentab('Links')">
                Links
              </p>
              <p class="tab-links" onclick="opentab('Education')">Education</p>
            </div>
            <div class="tab-content active-tab" id="skills">
              <ul>
                <li><span>Frontend Development</span><br />Designing Website interfaces.</li>
                <li><span>Frameworks/Libraries</span><br />HTML, CSS , JavaScript(Basic), React.js</li>
                <li><span>Problem Solving</span><br />Solved 50+ questions combined across all platforms.</li>
              </ul>
            </div>
            <div class="tab-content" id="Education">
              <ul>
                <li>
                  <span>2024 - current</span><br />B.Tech in Computer science and Engineering
                  sandip university madhubani [BIHAR]
                  SGPA: 8.55 (as of now)
                  
                </li>
                <li><span>2021 -2023</span><br />S.N.J.N High school , Belhar
                  Higher Secondary PCM
                  Percentage: 60 %</li>
                <li><span>2019-2021</span><br />U.M.S. srinagar,BELHAR
                  Matriculate
                  Percentage: 76%</li>
              </ul>
            </div>
            <div class="tab-content" id="Links">
              <ul>
                <li><span>Linkedin</span><br /><a href="https://www.linkedin.com/in/ankit-kumar-sharma">Click here</a></li>
                <li><span>Leetcode</span><br /><a href="https://leetcode.com/u/ANKITKUMARSHARMA/">Click here</a></li>
                <li><span>Github</span><br /><a href="https://github.com/ANKITKUMARSHARMA2027/newprogect-demo">Click here</a></li>
                <li><span>codingnanja</span><br /><a href="https://www.naukri.com/code360/profile/daae5539-718d-4b8f-adb2-a33db370191f">Click here</a></li>
                <li><span>Gfg</span><br /><a href="https://www.geeksforgeeks.org/courses?source=google&medium=cpc&device=c&keyword=gfg&matchtype=e&campaignid=20039445781&adgroup=147845288105&gad_source=1&gclid=CjwKCAjwtdi_BhACEiwA97y8BKMN8YiraJD7REnOjrfZvhKgKamC8dlvwkwjBciX-czspLDmePOAERoCAJ8QAvD_BwE">Click here</a></li>



                
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>

    <!--services-->
   


    <!--PORTFOLIO-->
    

    <!--contact-->
    <div id="contact">
      <div class="container">
        <div class="row">
          <div class="contact-left">
            <h1 class="sub-title">Contact Me</h1>
            <p>   <a href=""><i class="fa-solid fa-envelope"></i></a> ankitsinghsharma07@gmail.com</p>

          
            <p><i class="fa-solid fa-phone"></i> 9006698071</p>
            <div class="social-icon">
              <a href="https://www.linkedin.com/in/ankit-kumar-sharma"><i class="fa-brands fa-linkedin"></i></a>
              <a href="https://leetcode.com/u/ANKITKUMARSHARMA/"><i class="fa-solid fa-code"></i></a>
              <a href="https://github.com/ANKITKUMARSHARMA2027/newprogect-demo"><i class="fa-brands fa-github"></i></a>
              
              
              
              
              
            </div>

          </div>
          <div class="contact-right">
            <form >
              <input type="text" name="Name" placeholder="Your name" required>
              <input type="email" name="email" placeholder="Your email" required>
              <textarea name="Message" placeholder="Your message"  rows="6"></textarea>
              <button type="submit" class="btn">Submit</button>
            </form>
          </div>
        </div>
      </div>
    </div>
    <script>
      var tablinks = document.getElementsByClassName("tab-links");
      var tabcontent = document.getElementsByClassName("tab-content");
      function opentab(tabname) {
        for (let tablink of tablinks) {
          tablink.classList.remove("active-link");
        }
        for (let tab of tabcontent) {
          tab.classList.remove("active-tab");
        }
        document.getElementById(tabname).classList.add("active-tab");
        event.currentTarget.classList.add("active-link");
      }
    </script>
  </body>
</html>
