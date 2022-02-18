![am i responsive](/assets/images/responsive.png)
<h1 align=center> Valley Gaming </h1>

Deployed Site - [Valley-Gaming](https://camerone14.github.io/Valley-gaming/)

This is my where you'll find my Gaming news/highlight website. The hope for this website is for it to become a hub for small indi game news, mostly grass roots developers. I will hopefully get dedicated writers with talent for capturing and conveying the scope of these big projects from little companies. In the mean time, there will be plenty of easy to digest lists on there.

This site is mainly targeted at core gaming audiences and people with a passion for indi game development.

---
<h1 align=center> User Stories </h1>

  - Visiting The Site
    1. I want to find interesting gaming topics
    2. I want to find relevant news
    3. I want to suggest new content

---
<h1 align=center> Features </h1>
  So, we've got our landing page which acts as a hub for the most recent headline article and there will be suggested content that will contain usually 2 articles.
  There's a contact section for suggestions, about page for some info on myself and finall there's the archive section which will hold all previous articles.
  
## Landing Page

  Here you'll find the main article and suggested content and a twitter feed of my selected "next big release" which will show a live feed of a large game developers twitter.

  Future versions of this page will hopefully contain more articles, as there's only techinically 3 on the front page as there's not a massive amount of consumable content on the site.

  ### - Header, Nav, Footer and Socials
   These carry over to every section of the website. While viewing on the desktop, users will notice the social buttons available on the top right in the header banner.
   While viewing on a mobile, the social buttons will only be available on the footer.
  
  I was trying to develop a burger menu, but I found myself spending too much time learning how to do it, and instead I took the advice of my Mentor and implimented a more traditional nav bar that scales outside of the header, instead of trying to fit it all into the header.
  
  ### - Suggested Content
   I spend quite alot of time getting this to work responsively as possible. I tried lots of ways to get the 2 or more thumbnails either inline or at rows. Ultimately, I decided to keep the suggested content on the right for larger screen sizes as per my orginal wireframe design.
   
![desktop contact wireframe](/assets/images/index-desktop.png)

## Archive

  This page will hold all articles held by Valley Gaming.
  There's currently a lot of blank area when opened in tablet and larger screen sizes. This is due to lack of articles to populate the space, but the plan would be to have them    wrap around and fill the page and a scoll element if needed.

  Each thumbnail links directly to articles on the advertised subject.

## Contact

  When this is fully functional, users will be able to submit requests for game reviews and feedback. They can inform me of the game and select the prefered console I should       play it on. They will even be able to tell me why I should play it.
  The front end of this form is complete, but the information submitted goes nowhere.

## About

  I've included this section for anyone that would be interested in reading my experience in playing games and the passion I have for the industry.
  I very much doubt this section will ever change, unless the site grows large enough for other people to become involved in the content.

## Articles
  I'm super proud of my work on these.
  While the "journalism" may not be top tier, I love the way the styling turned out. 
  I have also left a article template that can be easily copied across and you can add more article elements inside this template by copying the html provided.
  
## General Stlyes
- General colors: Gradient Red, Black/Dark Grey, White
- Font: Montserrat (Google Fonts)

<h1 align=center> Wireframes </h1>

### Software: Balsamiq
  - This software was used to 'build' my website before any html/css was ever wrote. I tried to stick as close as possible to these initial designs. I've included some images to support this.

![wireframe](/assets/images/contact-desktop-wireframe-ps.png)

<h1 align=center> Testing </h1>

- For my testing I used the W3C HTML Validator and CSS Validator.
  Please find links for both sites here - [HTML Validator](https://validator.w3.org/) & [CSS validator](https://jigsaw.w3.org/css-validator/)

- The HTML validator helped with debuging href links inside of images.
I now know that I need to wrap a <img> inside of an <a> tag to allow it to be a clickable link.
It also notified my of my use of H7. I then realised H7 onwards are not symantic and have no purpose.

- Thankfully, my CSS was free from any errors.
  
- This site has also achieved 90+ accessibilty on Lighthouse
  
- I did come across some issues while trying to deploy it through GitHub Pages. The issues I had, involved no images loading on my site. After lots of trouble shooting, I discovered that the issue came from incorrect paths in the directory. While it was working on the local host, when I actually deployed the site, thats when I picked up the issue.
  
## Testing User Stories
  
  - "I want to find interesting gaming topics"
      - The Landing Page has 2 suggested stories and 1 main article attached to the large thumbnail. At a responsive level, there will also be a more link that will send the user to the archive, here the user will find all articles stored on the website. The archive link can also be found in the nav bar and on the footer"
  
  - "I want to find relevant news"
      - While the main article will usually serve as relevant in the gaming news cycle, there is also a twitter feed for our most anticipated game found in the suggested section. This will also be updated periodically to a more relevant gaming release.
  
  - "I want to suggest new content"
     - Users have the option to suggest content for Valley Gaming to review. They have the option to suggest Games to be played, consoles to play it on and a reason for it to be reviews. All this can be found on the Contact page which is found on the Nav section in both the Header and Footer. A future feature will include a Module to appear on the archive page to inform users there is an option to suggest content if they wish.
  
### Tested Devices/Browsers
  - iPhone 12 Pro
  - Pixel 6
  - Chrome
  - Safari
  
### Known Bugs
 

 - I would also like to make note of a bug in the 'Contact' section. This seems to be only on mobile device, but when hitting submit on the form with incomplete required data. There seems to be a small lightly opaque black line that appears. I haven't quite had the time to figure out whats going on there yet.
---
# Credits

- Photoshop: Image resizing mostly
- Font Awesome: Twitter, Insta, Twitch icons
- [IGDB](https://www.igdb.com/): Presskit photos and videos to include in articles
- Chrome Developer Tools: This was extremely helpful for testing changes quickly without changing the workspace.
- [Am I Responsive?](http://ami.responsivedesign.is/): This was very helpful for seeing what my website looked after deployment.
- W3C HTML Validator & Jigsaw CSS Validator for testing and debugging.
- Google Fonts: This site uses Montserrat thanks to google fonts easy integration.
- Balsamiq Wireframes
  
# Lessons and Challenges
   
One of the biggest challenges I had was trying to get the Nav bar to be responsive inside the Header. I would of liked to have a drop down menu to include the nav links, but I found myself spending too much time trying to incorporate it. With that said, I think I prefer the design of my current nav bar while responsive.
  
Another challenge I had was trying to get the images to scale responsively. This is something I eventually overcome and you'll find most of the article images are fully responsive as these sections were designed at the latter half of the site building/styling.
  
Another challenge I learnt from would be the use of Flex. Thanks to this flexbox guide - https://css-tricks.com/snippets/css/a-guide-to-flexbox/ I became quite apt with styling and structuring using flex and Chrome Dev Tools
