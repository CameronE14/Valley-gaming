<h1 align=center> Valley Gaming </h1>

[Valley-Gaming](https://camerone14.github.io/Valley-gaming/)

This is my where you'll find my Gaming news/highlight website. The hope for this website is for it to become a hub for small indi game news, mostly grass roots developers. I will hopefully get dedicated writers with talent for capturing and conveying the scope of these big projects from little companies. In the mean time, there will be plenty of easy to digest lists on there.

This site is mainly targeted at core gaming audiences and people with a passion for indi game development.

***insert site picture***
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
  ***add details about colour and font***

<h1 align=center> Wireframes </h1>

***************Needs to be inserted**************

<h1 align=center> Testing </h1>

***insert responsive photo***

- For my testing I used the W3C HTML Validator and CSS Validator.
  Please find links for both sites here - [html validator](https://validator.w3.org/) & [css validator](https://jigsaw.w3.org/css-validator/)

- The HTML validator helped with debuging href links inside of images.
I now know that I need to wrap a <img> inside of an <a> tag to allow it to be a clickable link.
It also notified my of my use of H7. I then realised H7 onwards are not symantic and have no purpose.
The only warning I have currently are for my use of aria-labels for my twitter,insta and twitch icons. The HTML validator is suggesting these may not need to be used, but the icon text I have used are symbols, so I believe the aria-label is needed for these.

- Thankfully, my CSS was free from any errors.
  
- I did come across some issues while trying to deploy it through GitHub Pages. The issues I had, involved no images loading on my site. After lots of trouble shooting, I discovered that the issue came from incorrect paths in the directory. While it was working on the local host, when I actually deployed the site, thats when I picked up the issue.

### Known Bugs
 - While testing on a mobile device, I have noticed the "FRESH NEWS" text attached to the title image seems to be quite close the the bottom of the container.

 - I would also like to make note of a bug in the 'Contact' section. This seems to be only on mobile device, but when hitting submit on the form with incomplete required data. There seems to be a small lightly opaque black line that appears. I haven't quite had the time to figure out whats going on there yet.
---
# Credits

  mention photophop, IGDB for presskit photos, google devoloper tools, Am I responsive, W3C HTML Validator & Jigsaw CSS Validator, google fonts
  
# Learnings and Challenges
  
******mention learning flexbox and talk about struggling with getting the nav bar to work for quite a while and image resizing********
