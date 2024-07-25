# Sophie's Portfolio Website

## Website:

This website's purpose is to display my work as a full-stack developer, with a brief presentation, a skills set summary (at the moment, based on the Code Institute programme syllabus), a portfolio and a contact page with a form to get in touch.

The users targeted with this website are recruiters, employers and also the web-development community.

![Responsive Mockup](https://github.com/SophieDufrane/project1-v2/blob/main/assets/media/my_website_mockup.png)

## Features:

### Existing features:

- __Navigation Bar__

    - At the top of the page, the navigation bar displays a Logo made from my name's initial letters, this logo is also linked to the top of the home page, as a shortcut when moving to the other pages.
    - The other pages are linked to the navbar menu, items are in the right corner of the navigation bar: "Portfolio" and "Contact".
    - The background color is in a dark grey color, the menu items are well contrasted and easy to read.

![Nav bar](https://github.com/SophieDufrane/project1-v2/blob/main/assets/media/my_website_navbar.png)

- __Welcome section__

    - Under the navigation menu, an image refers to programming and serves as a background.
    - A Welcome message overlays the image with a contrasted text color to make it visible.
    - This first section provides the user with a taste of the website's style.

![Welcome](https://github.com/SophieDufrane/project1-v2/blob/main/assets/media/my_website_welcome.png)

- __About Me section__

    - This section is structured as a resume and starts with a job title "Full-Stack Developer".
    - Then there's a brief introduction or pitch, and finally a picture. 
    - There's a button "Contact Me!" right below the text, it's also a shortcut to go to the contact page and access to the form.
    - The button has a contrasted color to make it evident and easy to see. Getting in contact with users (potential recruiters) would be the main purpose of this website.

![About Me](https://github.com/SophieDufrane/project1-v2/blob/main/assets/media/my_website_about_me.png)

- __Skills-set section__

    - Following the introduction, there's a summary of the main skills. The users can have an overview of the domain of expertise.
    - Skills are splits in 3 different categories or sets. Under each set, there's a list of skills and an icon to illustrate the category. 
    - All blocs have a different background color to make it catchy.

![Skills-set](https://github.com/SophieDufrane/project1-v2/blob/main/assets/media/my_website_skills_set.png)

- __Footer__

    - The footer style is similar to the navigation bar, to make the website consistent.
    - There's a dark grey background and all the icons for social network are in white color to be visible.
    - All links open a new tab when clicked.

![Footer](https://github.com/SophieDufrane/project1-v2/blob/main/assets/media/my_website_footer.png)

- __Portfolio Page__  

    - The portfolio page is composed with several blocs with a title, a short sentence to introduce the project and a visual.
    - The images will open the project pages when clicked (website page).
    - The first project is the current Website and the only real project. The others are only visuals from **Freepik** to illustrate how the page will look.

![Portfolio](https://github.com/SophieDufrane/project1-v2/blob/main/assets/media/my_website_portfolio.png)

- __Contact Page__ 

    - There's a background image in dark grey color, to illustrates the contact page. The style is consitent with the home page.
    - A form overlays the image with a contrasted box and text, to make it visible. The weight of the characters has also been styled to make it easier to read.
    - This form's purpose is to get in touch with the owner of the website. It collects the visitor's name, email and displays a text-area for the message.

![Contact](https://github.com/SophieDufrane/project1-v2/blob/main/assets/media/my_website_contact.png)


### Other tools used:
- The footer icons and the Menu icon on the navbar were taken from **Font Awesome**.
- The fonts Abel and Montserrat were taken from **Google Fonts**.

### Features left to implement:

As this is too early to display many projects, I've only added one (this Website). 
The other images are not linked to other website pages, they are just visuals and will be replaced by real projects in the future.

## Testing:

- I've tested the website on Chrome and Firefox, I also used Chrome developer tools to check responsiveness.
- I have used a mobile and different devises to see how the website looks like on different screen sizes.
- I have tested the form and check if all the required fields are set-up correctly.
- I have clicked on all footer icones to see if the correct pages open in a new tab. Same with the Menu, and buttons.
- I confirmed that the Website and its functionnalities are working on all devises tested.

### Validator testing:

- HTML
Document checking completed. No errors or warnings to show.

![Checkup HTML](https://github.com/SophieDufrane/project1-v2/blob/main/assets/media/my_website_home_html_check.png)

- CSS
No errors were found when passing through the official CSS W3C Jigsaw.

![Checkup CSS](https://github.com/SophieDufrane/project1-v2/blob/main/assets/media/my_website_css_check.png)

- Lighthouse
    - Performance was the main issue that had to be fixed on both "Portfolio" and "Contact" pages. It was at 69% first, then resizing the images improved the performance that is now 90%
    - Accessibility was at 92% on the "Home page". To fix the issue, I've changed the boxes colors and this has improved the score that is now 95%.
    - Best practices is 100%
    - SEO is 100%

![Checkup Lighthouse](https://github.com/SophieDufrane/project1-v2/blob/main/assets/media/my_website_lighthouse_home.png)

### Improvements:

The About-me section could have a better look on screens 768px and bigger, the title "About Me" looks slightly disconnected from the rest of the section. 
I remove the bottom-margin of the h2 on bigger screens to improve the visual, however I think this can be improved to make the visual more consistent.

## Deployment:
- The site was deployed to GitHub following the steps below:
    - In the GitHub repository, navigate to the "Settings" tab.
    - In the "Pages" menu, from the "Source" dropdown list, select "Deploy from a Branch".
    - On the branch section select "Main" Branch and "Root" Folder.
    - Go back to the "Code" tab and refresh.
    - The ribbon at the top will display a green check when it has been deployed correctly.
    - On Deployment section check the link for the deploid website.

- The live link can be found here: https://sophiedufrane.github.io/project1-v2/

## Credits:

### Content
- The skills-set items (lists) are from the **Code Institute "FullStack Software development" brochure**.

### Media
- The pictures are from **Freepick**.

### Source code
- The design and functionnality of the navbar, using a toggle menu, comes from the **Code Institute "Love Running" project**.