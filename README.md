# Sully's Kitchen
![Am i Responsive image](/assets/docs/responsive.png)

[View Live Project Here](https://shahid129.github.io/sully-s-kitchen/index.html)

## TABLE OF CONTENTS

- [Description](#description)
- [Themes](#themes)
- [Features](#features)
- [Testing](#testing)
- [Responsivity](#responsivity)
- [Issues and Bugs](#issuesandbugs)
- [Technology](#echnology)
- [Deployment](#deployment) 
- [Credits](#credits)
- [Acknowledgement](#acknowledgement)
- Author Info

A very Comprehensive and easy to navigate restaurant menu is created to give the audience full comfort while using the restaurant menu. It is a fine dining restaurant where people will have to book in advance to ensure the availability of the seat-in capacity. in this way the customers will get 100% attention of the staff, and proper guest care would be taken. customer satisfaction and quality of the food is our main aim.

## DESCRIPTION
This project was created with the intention of making a user friendly website, where customers can easily navigate between the pages and be able to find their required documents. The site is simple enough even for a person with no or little experience would be able to use it.
  
## THEMES
The themes chosen for this project was a restaurant and I wanted to make the page as simple as possible. Only two types of font I used and they are 

 - Raleway for logo and heading
 - Mmooch Sans for body

 I used only two minimum colors all throughout the project and they are
 - rgb(221, 214, 214) for background.
 - black for text.
 - #F3F3F3 for background.
 - rgba221,214,214 for form.
 - rgb(38, 1, 1) for buttons
 - #888888 for button shadow.

The color contrast between the foreground and the background is well maintained throughout the project.

## FEATURES

 <details>
 <summary> Navigation Menu</summary>
[See Image](/assets/docs/navigation.png)
The Navigation Menu is inside the header section and stays on the right hand side of the laptop screen. As the screen becomes smaller, or on small mobile device the menus comes down the logo. I did not use the hamburger menu because I tried to stick to course module as much as I could, even though I used css flexbox.
</details>

 
<details>
<summary>Logo</summary>

[See Image](/assets/docs/logo.png)
Logo is simply the name of the restaurant with a sub heading underneath it. The logo creates a link to the home page and can be accessed from anywhere within the site.
</details>


<details>
<summary>Favicon</summary>

[See Image](/assets/docs/favicon.png)
Favicon is simply  the first two letters of Sully's Kitchen. Blue background with white text gives a nice, clean professional look Favicon is created using the [favicon](https://favicon.io/favicon-generator/) website.
</details>

<details>
<summary>Hero</summary>

[See Image](/assets/docs/hero.png)

The Hero image was chosen very carefully to give a good flavour of curry and Indian restaurant. Different types of spices and seeds gives a proper indication about what type of restaurant is this.
</details>


<details>
<summary>Footer</summary>

[See Image](/assets/docs/footer.png)

The footer section includes all the social media links that Sully's Restaurant is connected with. The name of the social media is specified along with its logo so that anyone can understand. the layout stays same for even smaller devices up to 252px. Footer is situated at the bottom of all the pages.
</details>

<details>
<summary>Our Menu</summary>

[See Image](/assets/docs/our-menu.png)

The our menu section is placed in the first page without creating a menu option. I thought it would be easier for customers to see the menu as soon as the visit the site. They do not have to look for menu in navigation bar. At the bottom of the menu there is a [FULL MENU](/assets/docs/more-menu.png) button which will take them to the rest of the menu. The full menu page has two sections. First section has the rest of the main course. The second section has sides, drinks and desserts with their price indicated in the menu.
</details>

<details>
<summary>Find Us</summary>

[See Image](/assets/docs/find-us.png)

Find us section is situated at the bottom of the main page just above the footer. It includes a map with exact location on it, an imaginary address of the location and message us section. In the message us section a customer can contact us directly by putting their details in it.
</details>

<details>
<summary>Sign Up</summary>

[See Image](/assets/docs/sign-up.png)

Sign Up section can be accessed from the navigation menu. Background shadow is added to the sign up form so it looks like the form is floating. it also has transparent look. Customers can sign up with the restaurant to keep themselves updated with seasonal promotion and changes in menu.
</details>

<details>
<summary>About Us</summary>

[See Image](/assets/docs/about-us.png)

About Us page multiple section. A short description about our company followed by what are the services we do. Few pictures of curry, desserts and images of our fine dining restaurant. At the bottom it has opening hours for lunch and dinner.
</details>

## TESTING

Testing for this website was done several people in several ways. My brother checked the website and suggested a lot small changes to make it look better.My mentor Seun played a vital role for building this.

Online testing for html and css was done using the online validator websites and they are -

- W3C Validator
- Jigsaw css validator

Screenshots of all these results are below-

[Home](/assets/docs/home.png) [Full Menu](/assets/docs/full-menu.png) [Sign Up](/assets/docs/signup.png) [About Us](/assets/docs/aboutus.png) [Css](/assets/docs/css.png)

Google Lighthouse was used to check the Performance, Accessibility, Best Practice and SEO for all the pages. 

Screenshots of all these results are below -

[HOME PAGE](/assets/docs/lightouse-home.png)
[FULL MENU](/assets/docs/lightouse-fullmenu.png)
[SIGN UP](/assets/docs/lightouse-signup.png)
[ABOUT US](/assets/docs/lighthouse-aboutus.png)


## RESPONSIVITY
[Am I Responsive](http://ami.responsivedesign.is/#) is the website that allowed me to check how responsive my website is. Minimum viewport is 320x480px scaled down to scale(0.219) which is great to check if the site is suitable for small devices along with larger screens. 

## ISSUES AND BUGS

Bugs and issues are very common while making a webpage. Exactly like that I ran into few of them. 
- Font Awesome 
    - In the meet us section, I tried to add an icon for the address, The icon would not appear. But the icons appears at the other places.

- Google Lighthouse
    -  `Links do not have a discernible name`
    I tried to fix it but i think this beyond the capacity of this project and it has something to do with js.
     
- Navigation Bar
    - Navigation bar for small devices was not working even though the code for media query was right. After spending few hours on it, i figured out a (.) sign in a class was missing.
- Iframe 
    - After running the lighthouse, i figuired out that the name attribute was missing for iframe.

I wrote most of the html and css in vs code and copied and pasted it. that was a mistake. Hence git add, commit and push is missing in the beginning.

## TECHNOLOGY
- HTML
- CSS
- Gitpod
- Github
- Vs Code
- Font Awesome
- Google Font
- Markdown
- Balsamic

### RESOURCES
- Code Institute Curriculum
- Google Search Engine
- Stackoverflow
- Youtube
- Udemy
- W3Schools.com
- MDN Web Docs

## DEPLOYMENT

The project was made using gitpod and was pushed to github using gitpod's terminal. The project was pushed after each section or whenever there was a change in the code.

### Deploying on github pages
1. Log in to Github or create an account.
2. Locate the Github repository on the left.
3. Select setting for the repository.
4. On the left hand side select Pages.
5. Under Source click dropdown menu and select Main.
6. Once the selection is done, the page will refresh automatically, meaning the page is deployed.


## CREDITS
The main idea and the layout of the page was my idea. my brother and wife helped me with this.

>The images for this project was taken from [Unsplash](https://unsplash.com/)

>The Favicon for this project was taken from [Favicon](https://favicon.io/)

>The Icon for this project was taken from [Font Awesome](https://fontawesome.com/)

>The Font for this project was taken from [Google Fonts](https://fonts.google.com/)

> To better understand the code and a lot of help was taken from
- [Stack Overflow](https://stackoverflow.com/)
- [W3Schools](https://www.w3schools.com/)
- [CSS Tricks](https://css-tricks.com/)

## ACKNOWLEDGEMENT


> I would like to thank you my wife for making time for me so i can study while she minds the kids. Hats off to her.

> I would like to thank my tutor, Kasia, and my mentor, Seun, for their invaluable help and guidance throughout the process. The slack group Jan-2022-lwetb, and all the fellow mates from slack

