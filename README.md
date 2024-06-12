![Screenshot of the website in different screensizes](assets/images/readme-screenshots/view-different-devices.png)
# Japanese - Brazilian migration

Japanese - Brazilian Migration is a website designed to inform people about the rich history of connection between these two countries from across the planet. It will be targeted for those who are interested in the topic, including pupils, researchers and the history buff. 
The website will be useful to understand:
- The before - what pushed people to leave their homes
- During - how was the migration and settling process
- and after - how did the population integrate and change its new home 

## Features
- Navigation bar
    - The navigation bar sits at the top of the page.
    - It is fixed at the top, allowing the user to always have access to the links, easing the navigation through website.
    - It includes a link back to the top of the page on the left side.
    - It includes three links to the different sections of the website: Timeline, Culture and Subscribe.
    - The monochromatic and darker background provides contrast with the white text.
    - The links are clear on their meaning and connection with their respective sections.

- Banner
    - The banner show the name and theme of the website, informing the user what they can expect to find.
    - The font and color scheme are kept in correspondence with the rest of the page.
    - The image displayed is colorful and representative of the topic.
- Historical Background
    - The "Historical Background" section of the page is a short introduction to the topic, improving understanding of the following timeline.
    - It displays two historical images that draw the user's attention.
- Timeline
    - The timeline section provides historical information in a cronologic manner, taking advantage of the scrolling format of the page.
    - For each event on the timeline, there's a date, subtitle, text and one image of the period.
    - The timeline adjusts to the horizontal screens of desktops, while still keeping uniformity and flow.
- Cultural Aspects
    - The "Culture" displays images and texts about different areas the japanese population influenced Brazil cultural scene.
    - It fits the cronological logic of the website, arriving on current topics.
- Subscribe
    - The "Subscribe to out newsletter" section has a form to collect contact information from the users that are interested in receiving current information on the topic, cultural events and networking.
    - The form collect's the users' first and last name, email and in which language they would prefer to receive the newsletter in.
    - The form is valuable to the user as it gives the possibility of an extended contact with the Japanese Brazilian community beyond the website.
- References
    - The "References" section is a smaller and simpler section with listed references from the text in the above sections.
    - The links are responsive and change color of text and background when hovered (when viewed on a laptop or desktop)
    - All links open in a new page
## Testing
- I tested that this page works in different browsers: Chrome, Edge, Firefox and Safari.
- I tested that this page is responsive, functions and is comfortable to read in different screen sizes' widths:
    - 480px
    - 768px
    - 1208px
    - 1600px
- This was tested with mobile devices and laptops of different brands and sizes.
- I confirmed that all sections are readable and easy to understand.
- I confirmed that the form works:
    - Every input field is required.
    - The email input field will only accept an email.
    - One language is checked by default.
## Bugs
- Solved bugs
    - After the first deployment, I noticed the placeholder in "First name" input field displayed "Last name".
    - I corrected the placeholder value in the HTML file to fix the problem.
    ![Screenshot of the form section displaying "Last name" as placeholder for the "First name" input](assets/images/readme-screenshots/error-form.png)
    - Banner image didn't load after substituting the file for a compressed version
    ![Screenshot of the main page without the banner image](assets/images/readme-screenshots/error-banner.png)
    - I corrected the code on the CSS file

        ```background: url(../images/banner.webp) no-repeat left center/cover;```
- Accesibility (solved) issues
    - Lighthouse indicated that the checkbox input in the form didn't have a label
    - I changed the text from a span to a label to fix the problem.
## Validator Testing
- HTML
    - No errors were found when validating the HTML code on the official W3C validator.
- CSS
    - No errors were found when validating the CSS code on the official W3C validator.

     ![Valid CSS logo from W3C](https://jigsaw.w3.org/css-validator/images/vcss-blue)

- Accessibility
    - Lighthouse in devtools indicated a high accessibility score
    - It also indicated a middle (yellow)"Performance" score. The low performance was mainly due to large image sizes
        - The banner image was the main responsible for slow loading time.
        - The banner image was subsequently compressed without visible visual quality loss and replaced in the assets folder.

