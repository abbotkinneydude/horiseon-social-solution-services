## #hw1-horiseon-social-solution-services

<h3>HoriSEOn Marketing - Refactored Code, Optimized HTML / CSS / Media Assets.</h3>
<p>Github Repository Page: https://github.com/palowenstein/code-refactor-horiseon-social-media</p>
<p>Github Deployment Page: https://palowenstein.github.io/code-refactor-horiseon-social-media/</p>

![HoriSEOn Marketing (Screenshot)](./assets/images/hw1-code-refactor-horiseon-social-media.jpg?raw=true "HoriSEOn Marketing (Screenshot)")

## HTML Optimizations
<ol>
<li>Initial declaration: <span style="color: green;">Added Left to Right direction for text, developer name</span></li>
<li>Head section: <span style="color: green;">Added compelling title for the page. title tag comes first, css comes second then added a bunch of meta intel for Google and SEO at large.</span></li>
<li>Header section in <body>: <span style="color: green;">Header section: Company Name + Menu Bar - Combined the li and the href on single lines. Added titles to href. I added a <title> to h1 so that it would read when the mouse hovers</span></li>
<li>I replaced the CSS BG IMG with a true IMG for the reasons that follow: <span style="color: green;">Hero Image. I ended up using a true img instead of css bg img as I wanted a <title> and a <alt> for the browser to read. The picture behaves very closely to the original element. Note: the original IMG was sized down and compressed to load faster.</span></li>
<li>Content section:  <span style="color: green;">I added the missing <div>: div id=search engine optimization. Note: all images below have been sized down and compressed for faster loading / render time</span></li>
<li>Benefits section:  <span style="color: green;">Added title + alt to all items below + used a < /> self-closing img tag instead of a separate closing img tag on "Cost Management"</span></li>
<li>Footer section:  <span style="color: green;">Changed 2019 to 2020 + added aria label to the heart symbol so that speech reader would read properly. Note: I did not use &hearts; as the speech reader misread it, "heart" instead of "love".</span></li>
</ol>

## CSS Optimizations
<ol>
<li>.header: <span style="color: green;"> I re-organized and added position relative, z-index: 1 to stay above the new hero-img tag</span></li>
<li>.header div ul li: <span style="color: green;"> I deleted <.header div ul> and applied <list-style-type: none;> to <.header div ul li></span></li>
<li>.hero: <span style="color: green;">I created separate classes for the <.hero div> and a new one for <.hero-img> so that I could have a picture in html vs a bg image which won't take a title.</span></li>
<li>.hero-img: <span style="color: green;">Position Relative and Z-Index 0 to stay below header + margin top negative</span></li>
<li>All 3 respectives instances of the classes below have been combined into one single declaration:
    <ul>
    <li>.benefit-lead, .benefit-brand, .benefit-cost</li>
    <li>.benefit-lead h3, .benefit-brand h3, .benefit-cost h3</li>
    <li>.benefit-lead img, .benefit-brand img, .benefit-cost img</li>
    <li>.search-engine-optimization, .online-reputation-management, .social-media-marketing</li>
    <li>.search-engine-optimization img, .online-reputation-management img, .social-media-marketing img</li>
    <li>.search-engine-optimization h2, .online-reputation-management h2, .social-media-marketing h2</li>
    </ul>
</ol>

## JPG Optimizations
<ul>
<li>Original "digital-marketing-meeting.jpg" 14,2MB -> New half sized version: 329Ko</li>
<li>Original "search-engine-optimization.jpg" 14,9MB -> New half sized version: 525Ko</li>
<li>Original "online-reputation-management.jpg" 6,7 MB -> New half sized version: 397Ko</li>
<li>Original "social-media-marketing.jpg" 14,2MB -> New half sized version: 568Ko</li>
</ul>

 ## License
<p>
<a href="./MITlicense.txt">MIT License</a> | Copyright © [2020] Pierre André Lowenstein
</p>

 ## Contact
<p>
<a href="http://pierreandrelowenstein.com" title="[www] Pierre Andr&eacute; Lowenstein" target="_blank">[www] pierreandrelowenstein.com</a>
&nbsp;|&nbsp;
<a href="mailto:soundtrackspecialist@gmail.com" title="Courriel">Send me a 'courriel'</a>
</p>