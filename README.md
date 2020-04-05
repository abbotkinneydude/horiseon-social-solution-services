# horiseon-social-solution-services
20200404: Horiseon is your best solution for SEO, Reputation and Social Media Management.

Homework due for 04-04-2020

Changes / Optimizations to:

- HTML
- CSS
- JPG Files

- HTML
1)  Initial declaration: <!-- Added Left to Right direction for text, developer name -->
2)  Head section: <!-- Added compelling title for the page. title tag comes first, css comes second then added a bunch of meta intel for Google and SEO at large.-->
3)  Header section in <body>: <!-- Header section: Company Name + Menu Bar - Combined the li and the href on single lines. Added titles to href. I added a <title> to h1 so that it would read when the mouse hovers -->
4)  I replaced the CSS BG IMG with a true IMG for the reasons that follow: <!-- Hero Image. I ended up using a true img instead of css bg img as I wanted a <title> and a <alt> for the browser to read. The picture behaves very closely to the original element. Note: the original IMG was sized down and compressed to load faster. -->
5)  Content section:  <!-- I added the missing <div>: div id=search engine optimization. Note: all images below have been sized down and compressed for faster loading / render time -->
6)  Benefits section:  <!-- Added title + alt to all items below + used a < /> self-closing img tag instead of a separate closing img tag on "Cost Management" -->
7)  Footer section:  <!-- Changed 2019 to 2020 + added aria label to the heart symbol so that speech reader would read properly. Note: I did not use &hearts; as the speech reader misread it, "heart" instead of "love". -->

- CSS
1)  .header:    /* I re-organized and added position relative, z-index: 1 to stay above the new hero-img tag*/
2) .header div ul li:   /* I deleted <.header div ul> and applied <list-style-type: none;> to <.header div ul li> */
3) .hero:   /* I created separate classes for the <.hero div> and a new one for <.hero-img> so that I could have a picture in html vs a bg image which won't take a title. */
4) .hero-img:   /* Position Relative and Z-Index 0 to stay below header + margin top negative */

5) All 3 respectives instances of the classes below have been combined into one single declaration:
    .benefit-lead, .benefit-brand, .benefit-cost {
    .benefit-lead h3, .benefit-brand h3, .benefit-cost h3 {
    .benefit-lead img, .benefit-brand img, .benefit-cost img {
    .search-engine-optimization, .online-reputation-management, .social-media-marketing {
    .search-engine-optimization img, .online-reputation-management img, .social-media-marketing img {
    .search-engine-optimization h2, .online-reputation-management h2, .social-media-marketing h2 {
    
- JPG Files
Original "digital-marketing-meeting.jpg" 14,2MB -> New half sized version: 329Ko
Original "search-engine-optimization.jpg" 14,9MB -> New half sized version: 525Ko
Original "online-reputation-management.jpg" 6,7 MB -> New half sized version: 397Ko
Original "social-media-marketing.jpg" 14,2MB -> New half sized version: 568Ko

