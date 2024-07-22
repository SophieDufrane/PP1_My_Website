# Sophie's Portfolio Website

## Website:

This website's purpose is to display my work as a full-stack developer, with a brief presentation, a skills set summary (at the moment, based on the programme syllabus!), a portfolio and a contact page to send a message and get in touch.

The "users" targeted with this website are recruiters, employers and also the web-development community.

![Responsive Mockup](https://github.com/SophieDufrane/project1-v2/blob/main/assets/media/my_website_mockup.png)

## Features:

### Existing features:

- __Navigation Bar__

    - At the top of the page, the navigation bar displays a Logo made from my name's initial letters, this logo is also linked to the top of the home page, as a shortcut when moving to the other pages.
    - The other pages have links into the navbar too, they are in the right corner of the navigation bar: "Portfolio" and "Contact".
    - As the background color is in a dark grey, the menu items are well contrasted and easy to read.

![Nav bar](/../project1-v2/assets/media/my_website_navbar.png)

- __Welcome section__

    - Under the navigation menu, an image that represents lines of code serves as a background. The image is a reference to programming.
    - A Welcome message overlays the background with a contrasted text color to make it visible.
    - This first section provides the user with a taste of my work / style.

![Welcome](/../project1-v2/assets/media/my_website_welcome.png)

- __About Me section__

    - This section starts with the job title "Full-Stack Developer".
    - Then there's a brief introduction, more like a pitch, and a picture (resume style). 
    - There's a button "Contact Me!" right below the text, as a shortcut to go to the contact page and access to the contact form.
    - There's a contrasted color to make it evident and easy to see as get in contact with users (potential recruiters) would be the main purpose of this website.

![About Me](/../project1-v2/assets/media/my_website_about_me.png)

- __Skills-set section__

    - Following the introduction, there's a summary of the main skills. The users can have an overview of my domain of expertise.
    - Skills are splits in 3 different categories or sets, there are a list of the skills and an icon that represent each category. All blocs have a different background color to make it catchy.

![Skills-set](/../project1-v2/assets/media/my_website_skills_set.png)

- __Footer__

    - The style of the footer is close to the navigation bar one, to make the website consistent.
    - There's a dark grey background and all the icons for social network are in white color to be visible.
    - All links open a new tab when clicked.

![Footer](/../project1-v2/assets/media/my_website_footer.png)

- __Portfolio Page__  

    - The portfolio page is composed with several blocs with a title and a visual for each "works".
    - The blocs will be linked to the websites pages as this has been done for the first one, which is the current Website.

![Portfolio](/../project1-v2/assets/media/my_website_portfolio.png)

- __Contact Page__ 

    - There's a background image in dark grey color, to illustrates the contact page.
    - A form overlays the image with a contrasted box and text, to make it visible. The weight of the characters has also been styled to make it easier to read.
    - This form's purpose is to get in touch with the owner of the website. It collects the visitor's name, email and displays a text area for the message.

![Contact](/../project1-v2/assets/media/my_website_contact.png)

### Features left to implement:

As this is too early to display many works, I've only added one (this Website) and added the link to the image. 

The other images come from Freepik and have the same link as the Project #1.

## Testing:

I've tested the website on Chrome and Firefox, I also used Chrome developer tools to check responsiveness.

I have also used mobile and different devises to see how the website looks on different screen sizes.

I have tested the form and check if all the required field are set-up correctly.

I confirmed that the Website and its functionnalities are working on all devises tested.

### Validator testing:

- HTML
  - Document checking completed. No errors or warnings to show. [W3C for Home page](https://validator.w3.org/nu/#textarea)

  - Document checking completed. No errors or warnings to show. [W3C for Portfolio page](https://validator.w3.org/nu/#textarea)

  - Document checking completed. No errors or warnings to show. [W3C for Contact page](https://validator.w3.org/nu/#textarea)

![Checkup HTML](/../project1-v2/assets/media/my_website_home_html_check.png)

- CSS
  - No errors were found when passing through the official [W3C CSS (Jigsaw)](http://jigsaw.w3.org/css-validator/check/referer)

![Checkup CSS](/../project1-v2/assets/media/my_website_css_check.png)

- Lighthouse
    - Performance is the main issue to be fixed on Portfolio and Contact pages (69%)
    - Accessibility is 95%. It was at 92% on the Home page (not enough contrast on the skills-set sectio) so I've changed the boxes colors to improve the score.
    - Best practices is 100%
    - SEO is 100%

![Checkup Lighthouse](/../project1-v2/assets/media/my_website_lighthouse_home.png)

### Unfixed Bugs:

The performance of the Portfolio and Contact pages is a too low (69%) due to the images sizing.
I've tried to reduce the size and worked on the style.css but wasn't able to improve more than the existing performance so far.

## Deployment:
- The site was deployed to GitHub following the steps below:
    - In the GitHub repository, navigate to the "Settings" tab.
    - In the "Pages" menu, from the "Source" dropdown list, select "Deploy from a Branch".
    - On the branch section select "main" Branch and "Root" Folder.
    - Go back to the "Code" tab and refresh.
    - THe ribbon at the top will display a green icon when it has been deployed correctly.
    - On Deployment section check the link for the deploid website.

- The live link can be found here: https://sophiedufrane.github.io/project1-v2/

## Credits:

### Content
- The icons in the footer and the "Menu" one were taken from Font Awesome.
- The fonts Abel and Montserrat were taken from Google Fonts.

### Media
- The pictures used on Home, Portfolio and Contact pages are from Freepick.

### Source code
- The code for navbar with toggle menu comes from the "Love Running" project of Code Institute.