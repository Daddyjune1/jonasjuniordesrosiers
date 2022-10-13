
<!DOCTYPE html>
<html lang="en-us">

<head>
  <meta charset="utf-8" />
  <title>Site Plan</title>
  <link type="text/css" rel="stylesheet" href="styles/site-plan-rafting.css" />
</head>

<body>
  <header>
    <h1>DaddyJune Web Design services and Marketing</h1>
    <h2>Jonas Junior Desrosiers</h2>
    <h2>WDD 130-[01]</h2>
    <!-- In the header above, add the name of your site, your name and class number. For example if you are in section 3 you would put WDD 130-03 -->
  </header>
  <main>
    <!-- ------------------------Steps 2-5------------------------------ -->
    <hr />
    <h2>Overview</h2>
    <h3>Purpose</h3>
    <p>This website is creating for all people who wants to join Brigham young university and know everything they
        will need to know about web design and website, And it's also creating for Marketing services </p>
    <!-- change this -->

    <h3>Audience</h3>
    <p>Your are want to a good web designer? This website is creating for you, you will find everything you need to be want you design to be
    and If you want to grow up the service of your Entreprise,"DaddyJune Web Design services and Marketing" got the personal you need to help you on. </p>
    <!-- change this -->

    <hr />
    <h2>Branding</h2>
    <h3>Website Logo</h3>
    <!-- Replace this with some sort of logo for your site.  A logo can be as simple as the name of your site in a nice font :) -->
    <img src="C:\Users\Administrator\Documents\Wdd130\wrr\Images\Website-designer.png" alt="Logo image" />
    <hr />
    <h2>Style Guide</h2>
    <!-- ------------------------Steps 6-9------------------------------ -->

    <h3>Color Palette</h3>
    <!--  The colors you choose for a website are one of the most important decisions you will make. Follow the instructions on the activity in Canvas then return and replace the color codes below with the hex color codes (the 6 digit numbers that show at the bottom of each color) for the colors you have chosen below.  You should have at least 2 colors but do not have to fill in all 4 if you do not need them.  -->

    <!-- Copy and paste the URL to your finished palette below. Replace the href value that is there with yours. Make sure to paste it into both the href value and the content text of the <a> tag -->
    <p>Palette URL: <style>
      @import url('https://fonts.googleapis.com/css2?family=Courgette&display=swap');
      </style> </p>
    <a href="https://coolors.co/palette/396e94-e7c24f-a43312-381d2a-c6d2b1" target="_blank">https://coolors.co/396e94-e7c24f-a43312-381d2a-aabd8c</a>

    <table class="colors">
      <tr>
        <th>primary-color: #d4aa4d</th> <th>secondary: #E7C24F</th> <th> accent1-color: #f3bdb6 </th> <th> accent2-color: #33b939 </th>
      </tr>
      <!-- Replace the numbers in the boxes below with your hex color codes. Then switch to the site-plan.css file and change your colors there as well. -->
      <tr>
        <td class="primary-color":#d4aa4d</td> 
        <td class="secondary": #E7C24F</td> 
        <td class="accent1": #A43312</td> 
        <td class="accent2" #33b939</td>
      </tr>
    </table>
  

    <!-- ------------------------Steps 10-12------------------------------ -->

    <h3>Typography</h3>
    <!-- Choose a font for your paragraphs (body copy) and headlines. What font(s) have you chosen? Think also about which of your colors above you might use for background and font colors. -->

    <h4>
      Heading Font: "IM Fell French Canon"
      <!-- change this -->
    </h4>
    <h4>
      Paragraph Font: Lato, Helvetica, sans-serif;
      <!-- change this -->
    </h4>

    <nav>body {
      max-width: 960px;
      margin: 0 auto;
      padding: 4em;
      font-size: 18px;
      text-align: center;
    }
    img {
      display: block;
      margin: 0 auto;
      max-width: 300px;
    }
    h1, h2, h3, h4, h5, h6 {
      font-family: var(--heading-font);
      color: var(--headline-color-on-white);
    }
    h2 {
      text-align: center;
    }
    hr {
      height: 3px;
      margin: 35px 0;
      background: var(--accent1-color);
    }
    header {
      padding: 1em;
      text-align: center;
      color: var(--paragraph-color-on-color);
      background-color: var(--paragraph-background-color);
    }
    header > h1, header > h2 {
      color: var(--headline-color-on-color);
    }
    p {
      font-family: var(--paragraph-font);
      color: var(--paragraph-color);
      padding: 1em;
    }
    .colors {
      width: 100%;
      min-width: 350px;
      margin: 30px auto;
      text-align: center;
    }
    .colors th {
      background-color: #999;
    }
    .colors td{
      width: 25%;
      height: 3em;
    }
    .primary {
      background-color: var(--primary-color);
    }
    .secondary {
      background-color: var(--secondary-color);
    }
    .accent1 {
      background-color: var(--accent1-color);
    }
    .accent2{
      background-color: var(--accent2-color);
    }
    p.colored {
      background-color: var(--paragraph-background-color);
      color: var(--paragraph-color-on-color);
    }
    nav {
      background-color: var(--nav-background-color);
      line-height: 3em;
      text-align: center;
      font-size: 1.2em;
    }
    nav  {
      list-style-type: none;
      display: flex;
    }
    nav a {
      padding:1em;
      min-width: 120px;
      text-decoration: none;
      padding: 10px;
    }
    nav a:link, nav a:visited {
      color: var(--nav-link-color);
    }
    nav a:hover {
      color: var(--nav-hover-link-color);
      background-color: var(--nav-hover-background-color);
    }
    .sitemap {
      display: grid;
      justify-content: center;
    
      grid-template-columns: repeat(6, 15%);
      grid-template-rows: 3em 1.5em 1.5em 3em;
      grid-template-areas: ". . home home . ."
        ". . . top . ."
        ". left left right right ."
        "page2 page2 . . page3 page3";
    }
    .sitemap > div {
      text-align: center;
    }
    .sm-home {
      grid-area: home;
      background-color: #ccc;
      line-height: 3em;
    }
    .sm-page2 {
      grid-area: page2;
      background-color: #ccc;
      line-height: 3em;
    }
    .sm-page3 {
      grid-area: page3;
      background-color: #ccc;
      line-height: 3em;
    }
    .top {
      grid-area: top;
      border-left: 1px solid;
    }
    .left {
      grid-area: left;
      border-top: 1px solid;
      border-left: 1px solid;
    }
    .right {
      grid-area: right;
      border-top: 1px solid;
      border-right: 1px solid;
    }</nav>
    <hr />
    <h3>Normal paragraph example</h3>
    <p>
      The best Whitewater Rafting in Colorado, White Water Rafting Company
      offers rafting on the Colorado and Roaring Fork Rivers in Glenwood
      Springs. Since 1974, we have been family owned and operated, rafting the
      Shoshone section of Glenwood Canyon and beyond.
    </p>
    <h3>Colored paragraph example</h3>
    <p class="colored">
      Trips vary from mild and great for families, to trips exclusively for
      physically fit and experienced rafters. No matter what type of river
      adventures you are seeking, White Water Rafting Company can make it
      happen for you.
    </p>

    <!-- ------------------------Step 13------------------------------ -->

    <h3>Navigation</h3>
    <!-- Think about how you want your navigation bar to look. In the site-plan.css file change the colors to your colors to get the look you desire. -->
    <headline-color-on-white> headlin</headline-color-on-white>: #396E94;   
    <headline-color-on-color></headline-color-on-color>: #d3d03f;  
    
    <paragraph-color-on-white></paragraph-color-on-white>: #396E94;  
    <paragraph-color-on-color></paragraph-color-on-color>: white;  
    <paragraph-background-color></paragraph-background-color>: #396E94  ;
    
    <nav>
    nav-link-color: #396E94;
    nav-background-color: #D4AC0D;
    nav-hover-link-color: white;
    nav-hover-background-color: #396E94 </nav>
   <nav>
      <a href="#">Web Design services and Marketing</a>
      <a href="#">Page2</a>
      <a href="#">jonasdesrosiers91@gmail.com </a>
    </nav>
    <hr />
    <h2>Site Map</h2>
    <div class="sitemap">
      <div class="sm-home">Web Design services and Marketing</div>
      <div class="sm-page2">
        [Page2]
        <!-- this page will have a name later -->
      </div>
      <div class="sm-page3">jonasdesrosiers91@gmail.com </div>

      <div class="top">&nbsp;</div>
      <div class="left">&nbsp;</div>
      <div class="right">&nbsp;</div>
    </div>
    <hr />
    <h2>Wireframes</h2>
    <!-- Create an additional wireframe for your site. List it here below the Home page wireframe. -->

    <h3>Home</h3>

    <img src="C:\Users\Administrator\Documents\Wdd130\wrr\Images\Website-designer.png" alt="Logo image" />

    <h3>[Page 2]</h3>

  <!-- <img src="#" alt="page 2 wireframe"> -->

</main>
</body>

</html>
