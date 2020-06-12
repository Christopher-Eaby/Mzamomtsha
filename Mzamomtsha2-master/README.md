# Mzamomtsha2
$Mzamomtsha Primary School
========
​
- The project is a website for the Mzamomtsha Primary School, it helps to give information to the public about what the school stands for and what they offer to the community.
​
Usage
-----
- Slide show on homepage :
"    
(html)
<div class="main">
    <img class="mySlides" src="images/school.jpg">
    <img class="mySlides" src="images/school 2.jpg">
    <img class="mySlides" src="images/school3.jpg">
    <img class="mySlides" src="images/school4.jpg">
</div>
​
(scripting)
<script>
var slideIndex = 0;
    carousel();
function carousel() {
    var i;
    var x = document.getElementsByClassName("mySlides");
        for (i = 0; i < x.length; i++) {
            x[i].style.display = "none";
        }
        slideIndex++;
    if (slideIndex > x.length) {slideIndex = 1}
        x[slideIndex-1].style.display = "block";
        setTimeout(carousel, 2000); // Change image every 2 seconds
    }
</script>
"
- Contact us form :
"
(html)
<div class="contact">
    <form class="form-area">
    <h2>Contact Us</h2>
    <label for="fname">First name</label><br>
    <input type="text" id="fname" placeholder="First name here" required><br>
    <label for="message">Last name</label><br>
    <input type="text" id="lname" placeholder="Last name here"><br>
    <label for="message">Email address</label><br>
    <input type="text" id="email" placeholder="Email address" required><br>
    <label for="message">Your message</label><br>
    <textarea id="message" rows="6" cols="30" placeholder="Enter your message here" required></textarea><br>
    <input type="submit" id ="submit" value="Send Message">
    </form>
</div>
"
(scripting)
<script>
-// image 1
function toggle1() {
  var over = document.querySelector('.box1');
  if (over.className === 'box1 down') {
    over.className = 'box1 up';
  } else {
    over.className = 'box1 down';
  }
}
</script>
​
(html)
<div class="img1">
    <article class="box1 up">
        <h3 title="click here"><button id="button" class='click' onclick='toggle1()'>New Computers</button></h3>
        <p>Mzamomtsha Primary School is a school of Government. Which states that they get their funds from Government and some organizations.
        So Government provided the school with computers to help the teachers when making reports making life easy for both learners and the teachers.</p>
    </article>
</div>
"
​
- Web page scaling
"
Usage of 
- @media screen and (min-width: 1200px){}
- @media screen and (max-width: 1200px) and (min-width: 600px) {}
- @media screen and (max-width: 600px){}
"
to scale the webpage down and for certain parts of the webpage to not display at certain widths.
​
Features
--------
​
The webpage contains :
​
- A brief description of who the principal is and the motto of the school.
- A description of the school's history and background, all the current contact details for the school, and a contact form for ease of contact. 
- A list of all past and current events happening at the school.
​
Installation
------------
 
- No installion required, you can access the website via the following link : https://alexander-fortuin.github.io/Mzamomtsha2/
​
Contribute
----------
​
- Issue Tracker: We will not have an issue tracker, please feel free to submit any issues by contacting : interncptwex025@capaciti.org.za .
​
- Source Code: github.com/Alexander-Fortuin/Mzamomtsha2
​
Support
-------
​
If you are having issues, please let us know.
​
We have a mailing list located at: interncptwex025@capaciti.org.za
​
License
-------
​
The project is licensed under the CC BY-NC-ND license.
