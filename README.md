
<!DOCTYPE html>
<html>
<title>DopeDevUI</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Raleway">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body,h1,h2,h3,h4,h5,h6 {font-family: "Raleway", sans-serif}

body, html {
  height: 100%;
  line-height: 1.8;
}

/* Full height image header */
.bgimg-1 {
  background-position: center;
  background-size: cover;
  background-image: url("/Users/Koketso Thobane/Documents/My Web Sites/myPersonalWeb/images/bg.jpg");
  min-height: 100%;
}

.w3-bar .w3-button {
  padding: 16px;
}
</style>
<body>

<!-- Navbar (sit on top) -->
<div class="w3-top">
 <div class="w3-bar w3-white w3-card" id="myNavbar" style="background-image:url('/Users/Koketso Thobane/Documents/My Web Sites/myPersonalWeb/images/nav2.jpg')">
    <a href="#home" class="w3-bar-item w3-button w3-wide" style="background-image:url('/Users/Koketso Thobane/Documents/My Web Sites/myPersonalWeb/images/nav2.jpg')">DopeDevUI</a>
    <!-- Right-sided navbar links -->
    <div class="w3-right w3-hide-small">
      <a href="#about" class="w3-bar-item w3-button">ABOUT</a>
      <a href="#team" class="w3-bar-item w3-button"><i class="fa fa-user"></i> TEAM</a>
      <a href="#work" class="w3-bar-item w3-button"><i class="fa fa-th"></i> WORK</a>
      <a href="#pricing" class="w3-bar-item w3-button"><i class="fa fa-usd"></i> PRICING</a>
      <a href="#contact" class="w3-bar-item w3-button"><i class="fa fa-envelope"></i> CONTACT</a>
    </div>
    <!-- Hide right-floated links on small screens and replace them with a menu icon -->

    <a href="javascript:void(0)" class="w3-bar-item w3-button w3-right w3-hide-large w3-hide-medium" onclick="w3_open()">
      <i class="fa fa-bars"></i>
    </a>
  </div>
</div>

<!-- Sidebar on small screens when clicking the menu icon -->
<nav class="w3-sidebar w3-bar-block w3-black w3-card w3-animate-left w3-hide-medium w3-hide-large" style="display:none" id="mySidebar">
  <a href="javascript:void(0)" onclick="w3_close()" class="w3-bar-item w3-button w3-large w3-padding-16">Close ×</a>
  <a href="#about" onclick="w3_close()" class="w3-bar-item w3-button">ABOUT</a>
  <a href="#team" onclick="w3_close()" class="w3-bar-item w3-button">TEAM</a>
  <a href="#work" onclick="w3_close()" class="w3-bar-item w3-button">WORK</a>
  <a href="#pricing" onclick="w3_close()" class="w3-bar-item w3-button">PRICING</a>
  <a href="#contact" onclick="w3_close()" class="w3-bar-item w3-button">CONTACT</a>
</nav>

<!-- Header with full-height image -->
<header class="bgimg-1 w3-display-container w3-grayscale-min" id="home">
  <div class="w3-display-left w3-text-white" style="padding:48px">
    <span class="w3-jumbo w3-hide-small">Start something that matters</span><br>
    <span class="w3-xxlarge w3-hide-large w3-hide-medium">Start something that matters</span><br>
    <span class="w3-large">Stop wasting valuable time with projects that just isn't you.</span>
    <p><a href="#about" class="w3-button w3-white w3-padding-large w3-large w3-margin-top w3-opacity w3-hover-opacity-off">Learn more and start today</a></p>
  </div> 
  <div class="w3-display-bottomleft w3-text-grey w3-large" style="padding:24px 48px">
    <i class="fa fa-facebook-official w3-hover-opacity"></i>
    <i class="fa fa-instagram w3-hover-opacity"></i>
    <i class="fa fa-snapchat w3-hover-opacity"></i>
    <i class="fa fa-pinterest-p w3-hover-opacity"></i>
    <i class="fa fa-twitter w3-hover-opacity"></i>
    <i class="fa fa-linkedin w3-hover-opacity"></i>
  </div>
</header>

<!-- About Section -->
<div class="w3-container" style="padding:128px 16px" id="about">
  <h3 class="w3-center">ABOUT THE COMPANY</h3>
  <p class="w3-center w3-large">Key features of our company</p>
  <div class="w3-row-padding w3-center" style="margin-top:64px">
    <div class="w3-quarter">
      <i class="fa fa-desktop w3-margin-bottom w3-jumbo w3-center"></i>
      <p class="w3-large">Responsive</p>
      <p>DopeDevUI offers clients a platform to display whatever they wish to offer on the internet with stylysh and responsive websites. Our websites look attractive on any device offering a responsive website.</p>
    </div>
    <div class="w3-quarter">
      <i class="fa fa-heart w3-margin-bottom w3-jumbo"></i>
      <p class="w3-large">Passion</p>
      <p>Coding is life.</p>
    </div>
    <div class="w3-quarter">
      <i class="fa fa-diamond w3-margin-bottom w3-jumbo"></i>
      <p class="w3-large">Design</p>
      <p>Simple and elegant designs thats easy to use.</p>
    </div>
    <div class="w3-quarter">
      <i class="fa fa-cog w3-margin-bottom w3-jumbo"></i>
      <p class="w3-large">Support</p>
      <p>Contact the developer for client support.</p>
    </div>
  </div>
</div>

<!-- Promo Section - "We know design" -->
<div class="w3-container w3-light-grey" style="padding:128px 16px">
  <div class="w3-row-padding">
    <div class="w3-col m6">
      <h3>We know design.</h3>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod<br>tempor incididunt ut labore et dolore.</p>
      <p><a href="#work" class="w3-button w3-black"><i class="fa fa-th"> </i> View Our Works</a></p>
    </div>
    <div class="w3-col m6">
      <img class="w3-image w3-round-large" src="/Users/Koketso Thobane/Documents/My Web Sites/myPersonalWeb/images/b1.jpg" alt="Buildings" width="700" height="394">
    </div>
  </div>
</div>

<!-- Team Section -->
<div class="w3-container w3-center" style="padding:128px 16px" id="team">
  <h3 class="w3-center">THE TEAM</h3>
  <p class="w3-center w3-large">The ones who runs this company</p>
  <div class="w3-row-padding w3-grayscale" style="margin-top:64px">
    <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="/Users/Koketso Thobane/Documents/My Web Sites/myPersonalWeb/images/drake.png" alt="boss" style="width:100%">
        <div class="w3-container">
          <h3>Koketso</h3>
          <p class="w3-opacity">CEO & Founder</p>
          <p>Developer</p>
          <p><a href="javascript:void(0)" class="w3-button w3-light-grey w3-block" onclick="document.getElementById('form').style.display='block'" ><i class="fa fa-envelope"></i> Contact</a></p>
        </div>
      </div>
    </div>
     <div class="w3-col l3 m6 w3-margin-bottom">
      <div class="w3-card">
        <img src="/Users/Koketso Thobane/Documents/My Web Sites/myPersonalWeb/images/drake.png" alt="boss" style="width:100%">
        <div class="w3-container">
          <h3>Koketso</h3>
          <p class="w3-opacity">CEO & Founder</p>
          <p>Developer</p>
          <p><a href="javascript:void(0)" class="w3-button w3-light-grey w3-block" onclick="document.getElementById('form').style.display='block'" ><i class="fa fa-envelope"></i> Contact</a></p>
        </div>
      </div>
    </div>
  </div>
</div>

    <!-- GOOgle form modal-->
    <div id="form" class="w3-modal">
                <span onclick="document.getElementById('form').style.display='none'" class="w3-button w3-display-position w3-large">x</span>
                    <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSf16N91IIGPeH0gxzCzZc1I1IHXJkGOQqY9eECCG3FzxcEg7Q/viewform?embedded=true" width="430" height="450" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>
    </div>


<!-- Promo Section "Statistics" -->
<div class="w3-container w3-row w3-center w3-dark-grey w3-padding-64">
  <div class="w3-quarter">
    <span class="w3-xxlarge">1+</span>
    <br>Partners
  </div>
  <div class="w3-quarter">
    <span class="w3-xxlarge">25+</span>
    <br>Projects Done
  </div>
  <div class="w3-quarter">
    <span class="w3-xxlarge">9+</span>
    <br>Happy Clients
  </div>
  <div class="w3-quarter">
    <span class="w3-xxlarge">15+</span>
    <br>Meetings
  </div>
</div>



<!-- Work Section -->
<div class="w3-container" style="padding:128px 16px" id="work">
  <h3 class="w3-center">OUR WORK</h3>
  <p class="w3-center w3-large">What we've done for people</p>

  <div class="w3-row-padding" style="margin-top:64px">
    <div class="w3-col l3 m6">
      <img src="/Users/Koketso Thobane/Documents/My Web Sites/myPersonalWeb/images/w1.jpg"style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="A microphone">
    </div>
    <div class="w3-col l3 m6">
      <img src="/Users/Koketso Thobane/Documents/My Web Sites/myPersonalWeb/images/w2.jpg"style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="A phone">
    </div>
    <div class="w3-col l3 m6">
      <img src="/Users/Koketso Thobane/Documents/My Web Sites/myPersonalWeb/images/w3.jpg"style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="A drone">
    </div>
    <div class="w3-col l3 m6">
      <img src="/Users/Koketso Thobane/Documents/My Web Sites/myPersonalWeb/images/w4.jpg"style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="Soundbox">
    </div>
  </div>

  <div class="w3-row-padding w3-section">
    <div class="w3-col l3 m6">
      <img src="/Users/Koketso Thobane/Documents/My Web Sites/myPersonalWeb/images/w5.jpg"style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="A tablet">
    </div>
    <div class="w3-col l3 m6">
      <img src="/Users/Koketso Thobane/Documents/My Web Sites/myPersonalWeb/images/w6.jpg"style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="A camera">
    </div>
    <div class="w3-col l3 m6">
      <img src="/Users/Koketso Thobane/Documents/My Web Sites/myPersonalWeb/images/w7.jpg"style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="A typewriter">
    </div>
    <div class="w3-col l3 m6">
      <img src="/Users/Koketso Thobane/Documents/My Web Sites/myPersonalWeb/images/w8.jpg"style="width:100%" onclick="onClick(this)" class="w3-hover-opacity" alt="A tableturner">
    </div>
  </div>
</div>

<!-- Modal for full size images on click-->
<div id="modal01" class="w3-modal w3-black" onclick="this.style.display='none'">
  <span class="w3-button w3-xxlarge w3-black w3-padding-large w3-display-topright" title="Close Modal Image">×</span>
  <div class="w3-modal-content w3-animate-zoom w3-center w3-transparent w3-padding-64">
    <img id="img01" class="w3-image">
    <p id="caption" class="w3-opacity w3-large"></p>
  </div>
</div>

<!-- Skills Section -->
<div class="w3-container w3-light-grey w3-padding-64">
  <div class="w3-row-padding">
    <div class="w3-col m6">
      <h3>Our Skills.</h3>
      <p>C# developer, Java, Html, Css, Javascript, Android, Asp.Net(MVC).</p>
      <p>System analysist, Cloud Developer, SQL</p>
    </div>
    <div class="w3-col m6">
        <p class="w3-wide"><i class="fa fa-desktop w3-margin-right"></i>Java</p>
        <div class="w3-grey">
            <div class="w3-container w3-dark-grey w3-center" style="width:71%">71%</div>
        </div>
        <p class="w3-wide"><i class="fa fa-desktop w3-margin-right"></i>C#</p>
        <div class="w3-grey">
            <div class="w3-container w3-dark-grey w3-center" style="width:85%">85%</div>
        </div>
        <p class="w3-wide"><i class="fa fa-desktop w3-margin-right"></i>HTML</p>
        <div class="w3-grey">
            <div class="w3-container w3-dark-grey w3-center" style="width:89%">89%</div>
        </div>
        <p class="w3-wide"><i class="fa fa-desktop w3-margin-right"></i>Android</p>
        <div class="w3-grey">
            <div class="w3-container w3-dark-grey w3-center" style="width:85%">85%</div>
        </div>
        <p class="w3-wide"><i class="fa fa-desktop w3-margin-right"></i>SQL</p>
        <div class="w3-grey">
            <div class="w3-container w3-dark-grey w3-center" style="width:95%">95%</div>
        </div>
    </div>
  </div>
</div>

<!-- Pricing Section -->
<div class="w3-container w3-center w3-dark-grey" style="padding:128px 16px" id="pricing">
  <h3>PRICING</h3>
  <p class="w3-large">Choose a pricing plan that fits your needs.</p>
  <div class="w3-row-padding" style="margin-top:64px">
    <div class="w3-third w3-section">
      <ul class="w3-ul w3-white w3-hover-shadow">
        <li class="w3-black w3-xlarge w3-padding-32">Basic</li>
        <li class="w3-padding-16"><b>10GB</b> Storage</li>
        <li class="w3-padding-16"><b>10</b> Emails</li>
        <li class="w3-padding-16"><b>10</b> Domains</li>
        <li class="w3-padding-16"><b>Endless</b> Support</li>
        <li class="w3-padding-16">
          <h2 class="w3-wide">R 189.99</h2>
          <span class="w3-opacity">per month</span>
        </li>
        <li class="w3-light-grey w3-padding-24">
          <a href="#contact" class="w3-button w3-black w3-padding-large">Sign Up</a>
        </li>
      </ul>
    </div>
    <div class="w3-third">
      <ul class="w3-ul w3-white w3-hover-shadow">
        <li class="w3-red w3-xlarge w3-padding-48">Pro</li>
        <li class="w3-padding-16"><b>25GB</b> Storage</li>
        <li class="w3-padding-16"><b>25</b> Emails</li>
        <li class="w3-padding-16"><b>25</b> Domains</li>
        <li class="w3-padding-16"><b>Endless</b> Support</li>
        <li class="w3-padding-16">
          <h2 class="w3-wide">R 459.99</h2>
          <span class="w3-opacity">per month</span>
        </li>
        <li class="w3-light-grey w3-padding-24">
          <a href="#contact" class="w3-button w3-black w3-padding-large">Sign Up</a>
        </li>
      </ul>
    </div>
    <div class="w3-third w3-section">
      <ul class="w3-ul w3-white w3-hover-shadow">
        <li class="w3-black w3-xlarge w3-padding-32">Premium</li>
        <li class="w3-padding-16"><b>50GB</b> Storage</li>
        <li class="w3-padding-16"><b>50</b> Emails</li>
        <li class="w3-padding-16"><b>50</b> Domains</li>
        <li class="w3-padding-16"><b>Endless</b> Support</li>
        <li class="w3-padding-16">
          <h2 class="w3-wide">R 799.99</h2>
          <span class="w3-opacity">per month</span>
        </li>
        <li class="w3-light-grey w3-padding-24">
          <a href="#contact" class="w3-button w3-black w3-padding-large">Sign Up</a>
        </li>
      </ul>
    </div>
  </div>
</div>

<!-- Contact Section -->
<div class="w3-container w3-light-grey" style="padding:128px 16px" id="contact">
  <h3 class="w3-center">CONTACT</h3>
  <p class="w3-center w3-large">Lets get in touch. Send us a message:</p>
  <div style="margin-top:48px">
    <p><i class="fa fa-map-marker fa-fw w3-xxlarge w3-margin-right"></i> Johannesburg South, SA</p>
    <p><i class="fa fa-phone fa-fw w3-xxlarge w3-margin-right"></i> Phone: +27 65 903 8160</p>
    <p><i class="fa fa-envelope fa-fw w3-xxlarge w3-margin-right"> </i> Email: fxeagle61@gmail.com</p>
    <br>
    <form>
        <!-- old contact details form
      <p><input class="w3-input w3-border" type="text" placeholder="Name" required name="Name"></p>
      <p><input class="w3-input w3-border" type="text" placeholder="Email" required name="Email"></p>
      <p><input class="w3-input w3-border" type="text" placeholder="Subject" required name="Subject"></p>
      <p><input class="w3-input w3-border" type="text" placeholder="Message" required name="Message"></p>
      <p>
        <button runat="server" class="w3-button w3-black" onClick="MsgSend_Click" id="MsgSend" >
          <i class="fa fa-paper-plane" ></i> SEND MESSAGE
        </button>
      </p>-->
       <iframe src="https://docs.google.com/forms/d/e/1FAIpQLSf16N91IIGPeH0gxzCzZc1I1IHXJkGOQqY9eECCG3FzxcEg7Q/viewform?embedded=true" width="390" height="450" frameborder="0" marginheight="0" marginwidth="0">Loading…</iframe>

    </form >
    <!-- Image of location/map -->
    <img src="/Users/Koketso Thobane/Documents/My Web Sites/myPersonalWeb/images/m1.jpg" class="w3-image w3-greyscale" style="width:100%;margin-top:48px">
  </div>
</div>


<!-- Footer -->
<footer class="w3-center w3-black w3-padding-64">
  <a href="#home" class="w3-button w3-light-grey"><i class="fa fa-arrow-up w3-margin-right"></i>To the top</a>
  <div class="w3-xlarge w3-section">
    <i class="fa fa-facebook-official w3-hover-opacity"></i>
    <i class="fa fa-instagram w3-hover-opacity"></i>
    <i class="fa fa-snapchat w3-hover-opacity"></i>
    <i class="fa fa-pinterest-p w3-hover-opacity"></i>
    <i class="fa fa-twitter w3-hover-opacity"></i>
    <i class="fa fa-linkedin w3-hover-opacity"></i>
  </div>
  <p>Powered by <a href="Default.aspx" title="DopeDevUI" target="_blank" class="w3-hover-text-green">DopeDevUI</a></p>
</footer>
 
<script>
    // Modal Image Gallery
    function onClick(element) {
        document.getElementById("img01").src = element.src;
        document.getElementById("modal01").style.display = "block";
        var captionText = document.getElementById("caption");
        captionText.innerHTML = element.alt;
    }



    // Toggle between showing and hiding the sidebar when clicking the menu icon
    var mySidebar = document.getElementById("mySidebar");

    function w3_open() {
        if (mySidebar.style.display === 'block') {
            mySidebar.style.display = 'none';
        } else {
            mySidebar.style.display = 'block';
        }
    }

    // Close the sidebar with the close button
    function w3_close() {
        mySidebar.style.display = "none";
    }

    function openForm() {
        document.getElementById("myForm").style.display = "block";
    }

    function closeForm() {
        document.getElementById("myForm").style.display = "none";
    }
</script>

</body>
</html>
