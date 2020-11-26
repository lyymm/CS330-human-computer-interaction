# CS330-human-computer-interaction
## P6 Create your own portfolio website
### portfolio.html
The landing page of website with two showcase projects and one clickable project called smart eraser.
### biography.html
The biography page of myself, including self introduction, education and contact information with access to my email address.
### smarteraser.html
The smart eraser project page, containing details of project goal, techniques and final results.
### styles.css
The CSS file for all 3 html files and customizes in the same style.
### resume.pdf
The resume file inserted in my personal website.
### 0001.jpg~0005.jpg
Images used in the website for introduction of projects.
### selfie.jpg
My selfie picture is displayed in the biography.

<!DOCTYPE html>
<html>
   <head>
      <title>Portfolio</title>
      <link rel="stylesheet" href="styles.css">
   </head>
   <body>
      <nav class="top-menu">
         <ul>
            <li><a href="portfolio.html">Home</a></li>
            <li><a href="resume.pdf">Resume</a></li>
            <li><a href="biography.html">Biography</a></li>
         </ul>
      </nav>
      <main>
         <h1 class="web-title">Yangyun Li's Personal Website</h1>
         <p class="web-intro">Hello, welcome to Yangyun Li's personal portfolio website.</p>
         <p class="web-intro">You can begin to know me from my following two showcase projects.</p>
         <p class="web-intro">Or you can start with my resume and biography above.</p>
         <br>
         <br>       
         <h2 class="sub-title" id="showcase-projects">Showcase Projects</h2>
         <div class="projects">
            <div id="project1">
               <h3 class="project-title">Target Tracking</h3>
               <img class="project-cover" src="0001.jpg" alt="Target Tracking">
            </div>
            <div id="project2">
               <h3 class="project-title"><a href="smarteraser.html">Smart Eraser</a></h3>
               <a href="smarteraser.html"><img class="project-cover" src="0002.jpg" alt="Smart Eraser"></a>
            </div>
         </div>
      </main>
   </body>
</html>
