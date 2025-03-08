# LandingPage

git clone https://hezekiah-hub-create.github.io/LandingPage/

cd LandingPage
code .
open index.html

/C:/Users/lenovo/Desktop/LandingPage/
├── css/
│ └── styles.css
├── images/
│ └── icon0.jpg
│ └── icon1.png
│ └── icon2.png
│ └── icon3.png
│ └── icon4.png
│ └── logo.svg
│ └── hero-img.png
│ └── validation.png
│ └── manager.png
│ └── marketer.png
│ └── marketing01.png
│ └── marketing02.png
│ └── marketing03.png
│ └── tick.png
├── js/
│ └── scripts.js
└── index.html

HTML Structure
Navbar
The navbar contains the logo and navigation links for different sections of the landing page. It also includes sign-in and sign-up buttons.

<nav class="navbar">
  <div class="navbar-container">
    <a href="index.html" class="navbar-logo"><img src="images/logo.svg" alt="logo" class="navbar-logo-img"/></a>
    <div class="navbar-items">
      <ul>
        <li class="navbar-item"><a href="#feature">Product</a></li>
        <li class="navbar-item"><a href="#validation">Customers</a></li>
        <li class="navbar-item"><a href="#superhero">Pricing</a></li>
        <li class="navbar-item"><a href="#marketing">Resources</a></li>
      </ul>
      <div class="navbar-btns">
        <a href="#" class="navbar-sign-in-btn">Sign In</a>
        <a href="#" class="navbar-sign-up-btn">Sign Up</a>
      </div>
    </div>
  </div>
</nav>

Hero Section
The hero section includes a title, a brief description, and call-to-action buttons. It also features an image.

<section class="hero">
  <div class="hero-container">
    <div class="hero-content">
      <h1 class="hero-title">The Design Thinking Superpowers</h1>
      <p class="hero-text">Tools tutorials, design and innovation experts, all<br/>in one place! The most intuitive way to imagine<br/>your next user experience.</p>
      <div class="hero-btns">
        <a href="#" class="hero-btn1">Get started</a>
        <a href="#" class="hero-btn2">Watch the video</a>
      </div>
    </div>
    <div class="hero-img">
      <img src="images/hero-img.png" alt="hero" height="450">
    </div>
  </div>
</section>

Feature Section
The feature section highlights various features of the product with images and descriptions.

<section class="feature" id="feature">
  <div class="feature-container">
    <div class="feature-content">
      <h1 class="feature-title"> We design tools to unveil <br class="feature-br">your superpowers</h1>
      <div class="feature-cards">
        <div class="feature-card">
          <img src="images/icon1.png" alt="feature" class="feature-card-img"/>
          <h4 class="feature-card-title">First click tests</h4>
          <p class="feature-card-text">While most people enjoy casino gambling,</p>
        </div>
        <div class="feature-card">
          <img src="images/icon2.png" alt="feature" class="feature-card-img"/>
          <h4 class="feature-card-title">Design surveys</h4>
          <p class="feature-card-text">Sports betting,lottery and bingo playing for the fun</p>
        </div>
        <div class="feature-card">
          <img src="images/icon3.png" alt="feature" class="feature-card-img"/>
          <h4 class="feature-card-title">Preference tests</h4>
          <p class="feature-card-text">The Myspace page defines the individual.</p>
        </div>
        <div class="feature-card">
          <img src="images/icon4.png" alt="feature" class="feature-card-img"/>
          <h4 class="feature-card-title">Five second tests</h4>
          <p class="feature-card-text">Personal choices and the overall personality of the person.</p>
        </div>
      </div>
      <div class="feature-btns">
        <a href="#!" class="feature-btn">SIGN UP NOW</a>        
      </div>
    </div>
  </div>
</section>

Validation Section
The validation section provides information about effortless validation for design professionals.

<section class="validation" id="validation">
  <div class="validation-container">
    <div class="validation-content">
      <p class="validation-title">Effortless Validation for</p>
      <h2 class="validation-subtitle">Design Professionals</h2>
      <p class="validation-text">The Myspace page defines the individual,his or her characteristics, <br> traits, personal choices and the overall<br />personality of the person.</p>
      <h4 class="validation-subtitle-2">Accessory makers</h4>
      <p class="validation-text">While most people enjoy casino gambling, sports betting,<br />lottery and bingo playing for the fun</p>
      <h4 class="validation-subtitle-3">Alterationists</h4>
      <p class="validation-text">If you are looking for a new way to promote your business<br />that won't cost you money,</p>
      <h4 class="validation-subtitle-4">Custom Design designers</h4>
      <p class="validation-text">If you are looking for a new way to promote your business<br/>that won't cost you more money,</p>
    </div>
    <div class="validation-img">
      <img src="images/validation.png" alt="validation" height="565">
    </div>
  </div>
</section>

Manager Section
The manager section provides information about easier decision-making for product managers.

<section class="manager" id="manager">
  <div class="manager-container">
    <div class="manager-img">
      <img src="images/manager.png" alt="manager">
    </div>
    <div class="manager-content">
      <h5 class="manager-title">Easier decision making for</h5>
      <p class="manager-subtitle">Product Managers</p>
      <p class="manager-text">The Myspace page defines the individual,his or her characteristics, traits, personal choices and the overall<br />personality of the person.</p>
      <div class="manager-tick"> 
        <img src="images/tick.png" width="35" alt="tick" />
        <p>Never worry about overpaying for your<br />energy again.</p>
      </div>
      <div class="manager-tick"> 
        <img src="images/tick.png" width="35" alt="tick" />
        <p>We will only switch you to energy companies<br />that we trust and will treat you right</p>
      </div>
      <div class="manager-tick">
        <img src="images/tick.png" width="35" alt="tick" />
        <p> We track the markets daily and know where the<br />savings are.</p>
      </div>
    </div>
  </div>
</section>

Marketer Section
The marketer section provides information about optimization for marketers.

<section class="marketer" id="marketer">
  <div class="marketer-container">
    <div class="marketer-content">
      <h5 class="marketer-title">Optimisation for</h5>
      <p class="marketer-subtitle">Marketers</p>
      <p class="marketer-text">Few would argue that, despite the advancements of<br />feminism over the past three decades, women still face a<br />double standard when it comes to their behavior.</p>
      <h4 class="marketer-subtitle-2">Accessory makers</h4>
      <p class="marketer-text">While most people enjoy casino gambling, sports betting,<br />lottery and bingo playing for the fun</p>
      <h4 class="marketer-subtitle-3">Alterationists</h4>
      <p class="marketer-text">If you are looking for a new way to promote your business<br />that won't cost you money,</p>
      <h4 class="marketer-subtitle-4">Custom Design designers</h4>
      <p class="marketer-text">If you are looking for a new way to promote your business<br />that won't cost you more money,</p>
    </div>
    <div class="marketer-img">
      <img src="images/marketer.png" alt="marketer" height="565">
    </div>
  </div>
</section>

Marketing Section
The marketing section provides information about marketing strategies and includes cards with images and descriptions.

<section class="marketing" id="marketing">
  <div class="marketing-container">
    <div class="marketing-content">
      <h1 class="marketing-title">Marketing Strategies</h1>
      <p class="marketing-subtitle">Join 40,000+ other marketers and get proven strategies on email marketing</p>
      <div class="cards-container">
        <div class="cards">
          <div class="card">
            <img class="card-img-top" src="images/marketing01.png" alt="" />
            <div class="card-body">
              <p class="card-text">By <a href="#">Abdullah</a> | <span class="marketing-date">03 March 2019</span></p>
              <h3 class="card-title">Increasing Prosperity With Positive Thinking</h3>
            </div>
          </div>
        </div>
        <div class="cards">
          <div class="card">
            <img class="card-img-top" src="images/marketing02.png" alt="" />
            <div class="card-body">
              <p class="card-text">By <a href="#">Abdullah</a> | <span class="marketing-date">03 March 2019</span></p>
              <h3 class="card-title">Motivation Is The First Step To Success</h3>
            </div>
          </div>
        </div>
        <div class="cards">
          <div class="card">
            <img class="card-img-top" src="images/marketing03.png" alt="" />
            <div class="card-body">
              <p class="card-text">By <a href="#">Abdullah</a> | <span class="marketing-date">03 March 2019</span></p>
              <h3 class="card-title">Success Steps For Your <br> Personal Or Business Life</h3>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

Footer Section
The footer section includes quick links, legal information, and a sign-up form.

<section class="footer">
  <div class="footer-container">
    <div class="footer-content">
      <div class="footer-img">
        <a href="index.html" class="logo"><img src="images/logo.svg" height="38" alt="logo" /></a>
      </div>
      <div class="quick-links">
        <p class="quick-links-title">Quick Links</p>
        <ul class="quick-links-list">
          <li><a href="#!">About us</a></li>
          <li><a href="#!">Blog</a></li>
          <li><a href="#!">Contact</a></li>
          <li><a href="#!">FAQ</a></li>
        </ul>
      </div>
      <div class="legal">
        <p class="legal-title">Legal stuff</p>
        <ul class="legal-list">
          <li><a href="#!">Disclaimer</a></li>
          <li><a href="#!">Financing</a></li>
          <li><a href="#!">Privacy Policy</a></li>
          <li><a href="#!">Terms of Service</a></li>
        </ul>
      </div>
      <div class="signup">
        <p class="signup-title">knowing you're always on the best energy deal.</p>
        <form class="form-inline">
          <input class="form-control" type="phone" placeholder="Enter your phone Number" aria-label="phone" />
        </form>
        <button class="signup-btn">Sign up Now</button>
      </div>
    </div>
  </div>
</section>

Copyright Section
The copyright section includes the company name and a link to the theme provider.

<section class="copyright">
  <div class="copyright-container">
    <div class="copyright-content">
      <div class="copyright-text">
        <div class="copyright-logo-text">
          <p>&copy; 2022 Your Company Inc </p>
        </div>
        <div class="copyright-logo-link">
          <p> Made with<span>❤️</span>by <a href="https://themewagon.com/" target="_blank">ThemeWagon</a></p>
        </div>
      </div>
    </div>
  </div>
</section>
