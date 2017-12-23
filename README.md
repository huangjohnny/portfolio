<!DOCTYPE HTML>
<html>
    <title>
        Johnny Huang
    </title>
    <link rel="stylesheet" type="text/css" href="style.css"/>
    <link rel="stylesheet" type="text/css" href="timelinestyle.css"/>
    <link rel="shortcut icon" href="https://cdn3.iconfinder.com/data/icons/vector-icons-14/96/657-128.png" />
    <link rel="stylesheet" href="timenil.css">
    <link rel="stylesheet" href="resume.css">
    <style>
.container {
    position: relative;
    
}

.galleryimage {
  opacity: 1;
  display: block;
  width: 100%;
  height: auto;
  transition: .5s ease;
  backface-visibility: hidden;
}

.middle {
  transition: .5s ease;
  opacity: 0;
  position: absolute;
  top: 100%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%)
}

.container:hover .image {
  opacity: 0.3;
}

.container:hover .middle {
  opacity: .8;
}

.text {
  background-color: gray;
  color: white;
  font-size: 16px;
  padding: 10px 20px;
}
</style>
    <body>
        
        <button class="tablink" onclick="openTab('Home', this, 'rgb(83,156,191')" id="defaultOpen">Home</button>
        <button class="tablink" onclick="openTab('About', this, 'green')" id="AboutMeTab">About Me</button>
        <button class="tablink" onclick="openTab('Projects', this, 'rgb(0,3,51')">Achievements</button>
        <button class="tablink" onclick="openTab('Resume', this, 'rgb(44,62,68')">Resume</button>
        <button class="tablink" onclick="openTab('Contact', this, 'rgb(241,179,182)')">Contact</button>
        
        <div id="Home" class="tabcontent">
          
          

    
        <section style="padding-top: 10%">
          <p class="codingtext" style="color: black;"> Hi, I'm Johnny! Welcome to my portfolio :)<span class="blink">|</span></p> <br>
            <div class="gallery cf">
              <div class="container">
                <img class="galleryimage"  src="chorus.jpg" />
                <div class="middle">
                  <div class="text">A Capella Choir</div>
                </div>
              </div>
              <div class="container">
                <img src="coned.JPG" />
                <div class="middle">
                  <div class="text">Con Edison Internship 2017</div>
                </div>
              </div>
              <div class="container">
                <img src="Makerspacetrip.png" />
                <div class="middle">
                  <div class="text">Makerspace Trip</div>
                </div>
              </div>
              <div class="container">
                <img src="TomBright.jpg" />
                <div class="middle">
                  <div class="text">TOM Makeathon</div>
                </div>
              </div>
              <div class="container">
                <img src="conedpres.png" />
                <div class="middle">
                  <div class="text">Con Edison Presentation</div>
                </div>
              </div>
              <div class="container">
                <img src="9.1.jpg" />
                <div class="middle">
                  <div class="text">My Supervisor and I</div>
                </div>
              </div>
            </div>
        </section>
    
        <!-- https://codepen.io/anon/pen/aLyJgd -->

        </div>
        
        <div id="About" class="tabcontent">
          
          
            
        <div>
          <br><br><br>
          <br>
          <br>
          <br>
          <br>
          <br>
          <br>
          <br>
          <br>
          
              <div class="gallery cf">
                  <img style="width:250px; float:left; margin-left: 10%; margin-top: 2%; margin-right: 5%; padding-bottom:2%;" src="Profile.png">
                <span>
                    <p class="AboutMeText">
                      <br>
                  Hi, my name is Johnny Huang! I am a senior at Brooklyn Technical High School, majoring in Mechatronics and Robotics. 
                  Though my first love has been for hardware, I'm very passionate about software development.
                  I am the founder of my school's makerspace, BTHS Makerspace, and am currently an intern at Con Edison.
                  I want to develop technology that will better our communities!
                    </p>
                </span>
                  
                  
              </div>
        </div>
        </div>
        
        <div id="Projects" class="tabcontent">
          <br><br><br>
          <br>
          <br>
            <div id="scrollbox" class="gallery cf"  style="color:black; opacity: 1; overflow-y: scroll; margin-left: 45%; width: 52%; height: 78vh;">
              
                <div id="timenil">
                  
  <div class="timenil-vertical-line"></div>
  <div class="timenil-node" style="margin-right:42%;">
    <div class="timenil-node-separator" style="">
      2016
    </div>
  </div>
  <div class="timenil-node">
    <div class="timenil-node-child-left timenil-node-child-left-theme">
      <div class="timenil-content-box">
          <div class="timenil-content-text">
              <img src="track.png" style="width:100%; height:100%;"/> 
          </div>
      </div>
    </div>
    <div class="timenil-node-center"></div>

    <div class="timenil-node-trace"></div>

    <div class="timenil-node-child-right">
      <div class="timenil-content-box">
          <div class="timenil-content-text">
              <p><h1></h1></p>
              <p>My Track Team</p>
          </div>
      </div>
    </div>
  </div>

  <div class="timenil-node">
    <div class="timenil-node-child-left">
      <div class="timenil-content-box">
          <div class="timenil-content-text">

          <p><h1></h1></p>
            <p>My Choir</p>
          </div>
      </div>
    </div>
    <div class="timenil-node-center"></div>
    <div class="timenil-node-trace"></div>
    <div class="timenil-node-child-right timenil-node-child-right-theme">
      <div class="timenil-content-box">
          <div class="timenil-content-text" style="font-size:30px">
              <img src="choir.png" style="width:100%; height:100%;"/>
             
          </div>
      </div>
    </div>

  </div>

  <div class="timenil-node" style="margin-right:42%;">
    <div class="timenil-node-separator" style="">
      2017
    </div>
  </div>
  
  <div class="timenil-node">

    <div class="timenil-node-child-left timenil-node-child-left-theme">
      <div class="timenil-content-box">

<img src="Facebook.jpg" style="width:100%; height:100%;"/>
             

      </div>
    </div>

    <div class="timenil-node-center"></div>
    <div class="timenil-node-trace"></div>

    <div class="timenil-node-child-right">
      <div class="timenil-content-box">
          <div class="timenil-content-text">
              <p><h1></h1></p>
              <p>My First Hackathon!</p>
          </div>
      </div>
    </div>

  </div>

  <div class="timenil-node">

    <div class="timenil-node-child-left">

      <div class="timenil-content-box">

          <div class="timenil-content-box">
          <p><h1></h1></p>

            <p>BTHS Makerspace</p>

          </div>

      </div>

    </div>

    <div class="timenil-node-center"></div>

    <div class="timenil-node-trace"></div>

    <div class="timenil-node-child-right timenil-node-child-right-theme">

      <div class="timenil-content-box">

          <div class="timenil-content-box" style="font-size:30px;">

               <img src="nyumakerspace.png" style="width:100%; height:100%;"/>

              

          </div>

      </div>

    </div>

  </div>
  <div class="timenil-node">

    <div class="timenil-node-child-left timenil-node-child-left-theme">
      <div class="timenil-content-box">

<img src="Outintech.png" style="width:100%; height:100%;"/>
             

      </div>
    </div>

    <div class="timenil-node-center"></div>
    <div class="timenil-node-trace"></div>

    <div class="timenil-node-child-right">
      <div class="timenil-content-box">
          <div class="timenil-content-text">
              <p><h1></h1></p>
              <p>Out in Tech Mentorship</p>
          </div>
      </div>
    </div>

  </div>

  <div class="timenil-node">

    <div class="timenil-node-child-left">

      <div class="timenil-content-box">

          <div class="timenil-content-box">
          <p><h1></h1></p>

            <p>Con Edison Internship</p>

          </div>

      </div>

    </div>

    <div class="timenil-node-center"></div>

    <div class="timenil-node-trace"></div>

    <div class="timenil-node-child-right timenil-node-child-right-theme">

      <div class="timenil-content-box">

          <div class="timenil-content-text">

               <img src="9.1.jpg" style="width:100%; height:100%;"/>

              

          </div>

      </div>

    </div>

  </div>
</div>
            </div>  
        </div>
        
        <div id="Resume" class="tabcontent">
          <br>
          
          <div id="wrapper" style="overflow-y: scroll; overflow-x: hidden; height: 86%;">
  <div class="wrapper-top"></div>
  <div class="wrapper-mid">
    <!-- Begin Paper -->
    <div id="paper">
      <div class="paper-top"></div>
      <div id="paper-mid">
        <div class="entry">
            <div class="self">
            <h1>Johnny Huang<br />
            <br>
            <br>
              <span>Software Engineer</span></h1>
            <ul>
              <li style="margin-left:60%;" class="mail">jhuang5751@bths.edu</li>
              <li style="margin-left:60%;" class="tel">+11 646 331 1845</li>
            </ul>
          </div>
          <!-- End Personal Information -->
          <!-- Begin Social -->
          <div class="social">
            <ul>
              <li><a class='north' href="#" title="Download .pdf"><img src="images/icn-save.jpg" alt="Download the pdf version" /></a></li>
              <li><a class='north' href="javascript:window.print()" title="Print"><img src="images/icn-print.jpg" alt="" /></a></li>
              <li><a class='north' id="contact" href="contact/index.html" title="Contact Me"><img src="images/icn-contact.jpg" alt="" /></a></li>
            </ul>
          </div>
          <!-- End Social -->
        </div>
        
        <!-- Begin 2nd Row -->
        <div class="entry">
          <h2>EDUCATION</h2>
          <div class="content">
            <h3>Sept 2014 - Feb 2017</h3>
            <p>Brooklyn Technical High School<br />
              <em>Mechatronics and Robotics</em></p>
          </div>
        </div>
        <!-- End 2nd Row -->
        <!-- Begin 3rd Row -->
        <div class="entry">
          <h2>EXPERIENCE</h2>
          <div class="content">
            <h3>July 2017 - Present</h3>
            <p>Con Edison<br />
              <em>Intern/Co-Op</em></p>
            <ul class="info">
              <li>Updated legacy code of a 10 year old database to minimize misinformation in the remote monitoring system using MS Access VBA and SQL
</li>
              <li>Updated important documents such as Morning Reports, Distribution Generation logs, and on-site Parking Restrictions for the MTA.
</li>
            </ul>
          </div>
          <div class="content">
            <h3>Sept 2016 - Present</h3>
            <p>BTHS Makerspace <br />
              <em>Founder & President</em></p>
            <ul class="info">
              <li>Opened a space for approximately 30 students to gain access to tools and materials to build their own projects on Fridays after school
</li>
              <li>Currently leading hour and a half meetings - teaching other students how to use various cutting, 3D printing, and milling machines
</li>
            </ul>
          </div>
        </div>
        <!-- End 3rd Row -->
        <!-- Begin 4th Row -->
        <div class="entry">
          <h2>SKILLS</h2>
          <div class="content">
            <h3>Software Knowledge</h3>
            <ul class="skills">
              <li>Web Development</li>
              <li>Git</li>
              <li>C</li>
              <li>VBA</li>
              <li>AutoCAD</li>
              <li>Electrical Design</li>
            </ul>
          </div>
        </div>
        <!-- End 4th Row -->
         <!-- Begin 5th Row -->
        <div class="entry">
        <h2>Extracurriculars</h2>
        <br>
        <br>
          	<ul class="skills">
          	    <li>BTHS Makerspace</li>
                <li>A Capella Choir</li>
                <li>Cross Country / Track & Field</li>
          	</ul>
        </div>
        <!-- Begin 5th Row -->
      </div>
      <div class="clear"></div>
      <div class="paper-bottom"></div>
    </div>
    <!-- End Paper -->
  </div>
  <div class="wrapper-bottom"></div>
</div>
<div id="message"><a href="#top" id="top-link">Go to Top</a></div>
       
        </div>
        
        <div id="Contact" class="tabcontent">
        <div>
                    <div class="AboutMeText" style="padding-top: 22%;font-size: 25px;">
                        <p>
                            Johnny Huang
                        <br><br>
                            Jhuang5751@bths.edu
                        <br><br>
                            1(646)-331-1845
                        </p>
                    </div>
        </div>
        
        </div>
        
        
    
    </body>
    <script src="script.js"> </script>
</html>