![Screenshot of the website in different screensizes](assets/images/readme-screenshots/view-different-devices.png)
# Japanese - Brazilian migration

Japanese - Brazilian Migration is a website designed to inform people about the rich history of connection between these two countries from across the planet. It will be targeted for those who are interested in the topic, including pupils, researchers and the history buff. 
The website will be useful to understand:
- The before - what pushed people to leave their homes
- During - how was the migration and settling process
- and after - how did the population integrate and change its new home 

## Features
- Navigation bar
    - It is fixed at the top of the page, allowing the user to always have access to the links, easing the navigation back and fourth through website.
    - It includes a link back to the top of the page on the left side.
    - It includes three links to the different sections of the website: Timeline, Culture and Subscribe.
    - The monochromatic and darker background provides contrast with the white text.
    - The links are clear on their meaning and connection with their respective sections.

    ![Screenshot of the navigation bar](docs/navbar.png)

- Banner
    - The banner show the name and theme of the website, informing the user what they can expect to find.
    - The font and color scheme are kept in correspondence with the rest of the page.
    - The image displayed is colorful and representative of the topic, showing a torii (traditional japanese gate) and the MASP (Sao Paulo Art Museum), conveying visually the connection between Japan and Brazil as soon as the page opens.

    ![Screenshot of the navigation bar](docs/banner.png)
- Historical Background
    - The "Historical Background" section of the page is a short introduction to the topic, improving understanding of the following timeline.
    - It displays two historical images that draw the user's attention.

    ![Screenshot of the history section](docs/history.png)
- Timeline
    - The timeline section provides historical information in a cronologic manner, taking advantage of the scrolling format of the page.
    - For each event on the timeline, there's a date, subtitle, text and one image of the period.
    - The timeline adjusts to the horizontal screens of desktops, while still keeping uniformity and flow.
    - The timeline is valuable to the user because it effectively provides a visual layout of the cronological events that would be so clear in plain text. 

    ![Screenshot of the timeline section](docs/timeline.png)
- Cultural Aspects
    - The "Culture" displays images and texts about different areas the japanese population influenced Brazil cultural scene.
    - It fits the cronological logic of the website, arriving on current topics.
    - This section is valuable to the user because it provides information beyond historical facts, it shows the consequences of the facts shown before, increasing their meaning.

    ![Screenshot of the culture section](docs/culture.png)
- Subscribe
    - The "Subscribe to out newsletter" section has a form to collect contact information from the users that are interested in receiving current information on the topic, cultural events and networking.
    - The form collect's the users' first and last name, email and in which language they would prefer to receive the newsletter in.
    - The form is valuable to the user as it gives the possibility of an extended contact with the Japanese Brazilian community beyond the website.

    ![Screenshot of the subscribe section](docs/subscribe.png)
- References
    - The "References" section is a smaller and simpler section with listed references from the text in the above sections.
    - The links are responsive and change color of text and background when hovered (when viewed on a laptop or desktop)
    - All links open in a new page
    - The Reference section is valuable to the user because it provides validation to the information presented on the website, particularly useful for students and researchers who need to go deep in the topic or find sources for their projects.

    ![Screenshot of the subscribe section](docs/references.png)
- Footer
    - The footer section includes links to the relevant websites within the topic of Japanese immigration to Brazil
        - Main Wikipedia article in English
        - Wikiwand article page
        - Japanese Embassy in Brazil 
    - The links will open to a new tab to allow easy navigation for the user.
    - The footer keeps the color scheme as the header, maintaining visual integrity.
    - The footer is valuable to the user as it encourages them to keep reading on the topic beyond the website.

![Screenshot of the footer section](docs/footer.png) 

## Testing
- I tested that this page works in different browsers: Chrome, Edge, Firefox and Safari, both on Windows 11 and MacOS.
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
    - Autocomplete works on Chrome 
    ![Screenshot of form autofilled](docs/form-autofill.png)

    ### Unfixed bugs
    - No known bugs were left unfixed.
## Bugs
- Solved bugs
    - After the first deployment, I noticed the placeholder in "First name" input field displayed "Last name".
    - I corrected the placeholder value in the HTML file to fix the problem.
    ![Screenshot of the form section displaying "Last name" as placeholder for the "First name" input](docs/error-form.png)
    - Banner image didn't load after substituting the file for a compressed version
    ![Screenshot of the main page without the banner image](docs/error-banner.png)
    - I corrected the file path on the CSS file, which solved the issue

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
     ![Screenshot of W3C website indicating no errors found on this project](docs/css-validation.png)

- Accessibility
    - Lighthouse in devtools indicated a high accessibility score
    ![Screenshot of Lighthouse score results displaying 100% in Accessibility](docs/lighthouse.png)
    - It also indicated a 69% "Performance" score, which was later barely increased. The low performance was mainly due to large image sizes
        - The banner image was the main responsible for slow loading time.
        - The banner image was subsequently compressed without visible visual quality loss and replaced in the assets folder.
        - The Performance score increased only 1%
## Deployment
The site was deployed to GitHub pages. 
The steps to deploy are as follows:
- In the GitHub repository, navigate to the Settings tab
From the source section drop-down menu, select the Master Branch
- Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.
- The live link can be found here 
    - https://arthur-vilela.github.io/PP1-japan-brazil-migration/

## Credits
### Content
- The content from the Cultural Background and Timeline section was summarized by me and originally taken from the [Wikipedia page on Japanese immigration to Brazil.](https://pt.wikipedia.org/wiki/Imigra%C3%A7%C3%A3o_japonesa_no_Brasil)
- The text was only later translated to English, since the Wikipedia article in Portuguese was much richer in content.
### Media
- The banner image is from this[ article by Juliana Gomes](https://blog.meudna.com/imigracao-japonesa-criando-raizes-no-brasil/)
    - I contacted the author, who let me use the image for this purpose. The image was created using IA tools, which render it copywrite free in Brazil.
- The other images used in this project are now in public domain and were all taken from Wikipedia.
- Historical background section
    - The poster presented is in the Japanese Immigration History Museum
    - The photo of Ryo Mizuno is in the Museu Histórico da Imigração Japonesa no Brasil (São Paulo) (Historical Museum of the Japanese Immigration in Brazil)
- Timeline section
    - The first three of the original images (photos and postcards) in this section are located in the Museu Histórico da Imigração Japonesa no Brasil (São Paulo) (Historical Museum of the Japanese Immigration in Brazil)
    - The fourth image was taken by Caio do Valle, Brazil, uploaded by him onto Wikipedia and released into public domain by the author.
- Cultural Aspects section
    - The images from this section were taken on the open source website [pexels.com](https://www.pexels.com/)

### Code
-  The original code for the dots and vertical line in the Timeline section was created using Copilot.
```
.timeline .event::before {
    content: "";
    position: absolute;
    left: -10px;
    top: 0;
    width: 10px;
    height: 10px;
    background-color: #333;
    border-radius: 50%;
}
```
- The line created did not align well so I modified it to actually align the dots' position to the line and adjust its size, fitting different screen sizes.
```    
.timeline .event::before {
        content: "";
        position: absolute;
        left: -39px;
        top: 55px;
        width: 35px;
        height: 35px;
        background-color: #333;
        border-radius: 50%;
    }
```
### Readme.md
- The base for the README.md file was taken from Code Institute readme template found on https://github.com/Code-Institute-Solutions/readme-template

