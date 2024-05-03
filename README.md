# Esports Ascendancy

Welcome to Esports Ascendancy, a dedicated platform offering insights into the history and evolution of Esports over the years. Our platform is tailored for users seeking a deeper understanding of this dynamic industry.

Esports Ascendancy, where we uncover the roots and significant moments that have elevated esports giants into the global juggernauts they are today. Navigate effortlessly through our pages to uncover vital moments in history about Esports and find insights about their most iconic esports titles. With the aid of visuals, showing the growth of the industry and how far it has come.

The live link can be found here - [Esports Ascendancy](https://esteban-jr.github.io/EsportsAscendancy/)

![Esports Ascendancy Am I Responsive Image](/documents/read-me-images/responsive.PNG)

## Site Owner Goals 

- To become a go-to educational resource for esports enthusiasts, providing in-depth information about the history, evolution, and current state of esports.
- To provide accurate and well-researched information about the origins and early development of esports, ensuring that users can trust the content as a reliable source of information.
- To prioritize user experience by ensuring the website is easy to navigate, visually appealing, and accessible across different devices and platforms.

## User Stories
- ### First time user
  - As a first time user I want to learn about the origins of esports and how it has evolved over the years.
  - As a first time user I want to find introductory content that explains what esports is, how it differs from traditional sports, and why it has become so popular.
  - As a first time user I want to learn about major esports tournaments and competitions, including their formats, prize pools, and significance within the esports ecosystem.

- ### Returning User
  - As a returning user I want to find the information they're looking for quickly and intuitively, with clear navigation and well-organized content sections. 
  - As a returning user I want to revisit previously explored content and gain new insights or perspectives on the history and evolution of esports.
  - As a returning user I want to appreciate the visual elements of the website, such as photographs,that enhance the presentation of esports history and evolution.

- ### Frequent User
  - As a frequent user I want to find inspiration for their own projects, articles, or discussions related to esports history and evolution by revisiting favorite sections or discovering new content.

## Design

### Imagery
The images have a powerful visual impact that can convey a lot of information quickly and effectively. They capture the essence of a moment or era in a way that text alone often cannot, making them ideal for showcasing the evolution of esports over time.

### Colours
The color scheme of white, black, #262626 (Dark Gray), and #23f89e (Turquoise/Green) creates a modern, sophisticated, and visually appealing aesthetic for the website. It balances simplicity with vibrancy, professionalism with personality, and ensures that the content is presented in a clear and engaging manner for users.

### Fonts
The Inter font is the main font used throughout the whole website. This font was imported via [Google Fonts](https://fonts.google.com/). I'm using Sans Serif as a backup font, in case for any reason the main font isn't being imported into the site correctly.

## Wireframes
Wireframes were produced using Balsamiq. 

 <details>

 <summary>Mobile Wireframe</summary>

![Desktop Wireframe](/documents/read-me-images/esports-ascendancy-phone-wireframes.png)
 </details>

 <details>
    <summary>Website Wireframe</summary>

![Mobile Wireframe](/documents/read-me-images/esports-ascendancy-web-wireframes.png)
 </details>


 ## Features
- ### Navigation

    - The fully responsive navigation bar includes links to the Logo, Home, Events and Gallery page.
    - Also a fully responsive drop down menu.

![Nav bar image](/documents/read-me-images/header.PNG)

- ### Landing Page Image

    - The landing page includes an image with the websites name and text decribing the goal of the site
    - This section provides the user with a clear visual representation of the purpose of the site.

![Landing page](/documents/read-me-images/landing-page-image.PNG)

- ### What is Esports section

    - This section succinctly introduces esports as a professional field, tracing its exponential growth and outlining its global impact and promising future.

![What is section image](/documents/read-me-images/what-is-esports.PNG)

- ### History Section

    - Within this section, significant milestones in the Esports history are curated, offering invaluable insights.
    - This segment holds great value as users are presented with key events that have shaped the Esports industry into what it is today, providing a deeper understanding of its evolution.

![History section image](/documents/read-me-images/history-section.PNG)

- ### Footer

    - The footer section includes links to our Facebook, Instagram, Twitter and Youtube pages.
    - The links will open to a new tab to allow easy navigation for the user. 
    - The footer is valuable to the user as it allows them to find and follow us on social media.

![Footer image](/documents/read-me-images/footer.PNG)

### Features Left to Implement

- Form to allows user to sign up, or submit information
- More information about more events

## Validator Testing

- #### HTML

    - No errors were returned when using official W3C Markup Validator.
    - [W3C Validator Results](https://validator.w3.org/nu/?doc=https%3A%2F%2Festeban-jr.github.io%2FEsportsAscendancy%2F)

- #### CSS

    - No errors were found when using the official W3C CSS Validator. 
    - [W3C CSS Validator Results](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Festeban-jr.github.io%2FEsportsAscendancy%2F&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#warnings)

- #### Accessibility 

    - The site achieved a Lighthouse accessibility score of 100% which confirms that there will be no issue in readability.

![Lighthouse score](/documents/read-me-images/accessibility.PNG)

### Links Testing

- All navigation links were tested manually to ensure the user will be directed to the correct pages of the website.
- Social Media links in the footer of each page were tested manually to ensure they direct the user to the appropriate link in a new tab.

### Device Testing

- The website was viewed on a variety of devices to ensure responsiveness on various screen sizes. The website performed as it was made to. The responsive design was also checked using Chrome developer tools across multiple devices.
- I also used the following webiste to double the responsiveness:
    - [Am I Responsive](https://ui.dev/amiresponsive?url=https://esteban-jr.github.io/EsportsAscendancy/)

### Friends and Family User Testing

Friends and family members were asked to review the site and documentation to point out any bugs and/or user experience issues.

## Fixed Bugs

### Multiple ID's used

- I had used the same id's multiple times.
- To fix this i replaced the id's used with classes instead.

### Gallery images

- The images in the gallery were not responsive across all screen sizes.
- To fix the issue i used flexbox to be able to have the responsiveness across all screens.

## Technologies Used

### Languages
- HTML5
- CSS

### Frameworks - Libraries - Programs Used
- [Am I Responsive](http://ami.responsivedesign.is/) - Used to verify responsiveness of website on different devices.
- [Balsamiq](https://balsamiq.com/) - Used to generate Wireframe images.
- [Chrome Dev Tools](https://developer.chrome.com/docs/devtools/) - Used for overall development and tweaking, including testing responsiveness and performance.
- [Font Awesome](https://fontawesome.com/) - Used for Social Media icons in footer.
- [GitHub](https://github.com/) - Used for version control and hosting.
- [Google Fonts](https://fonts.google.com/) - Used to import and alter fonts on the page.
- [TinyPNG](https://tinypng.com/) - Used to compress images to reduce file size without a reduction in quality.
- [W3C](https://www.w3.org/) - Used for HTML & CSS Validation.

## Deployment

The project was deployed using GitHub pages. The steps to deploy using GitHub pages are:

1. Go to the repository on GitHub.com
2. Select 'Settings' near the top of the page.
3. Select 'Pages' from the menu bar on the left of the page.
4. Under 'Source' select the 'Branch' dropdown menu and select the main branch.
5. Once selected, click the 'Save'.
6. Deployment should be confirmed by a message on a green background saying "Your site is published at" followed by the web address.


The live link can be found here - [Esports Ascendancy](https://esteban-jr.github.io/EsportsAscendancy/)

## Credits

### Media
All images and their url's will be below:
- 1972: (https://twitter.com/vg_history/status/1378200123616882689/photo/1)
- 1980: (https://steemit.com/retrogaming/@darth-azrael/space-invaders-championship-1980)
- 1997:(https://whatculture.com/gaming/8-strangest-things-ever-won-at-a-video-game-event?page=8)
- 2000s: (https://en.wikipedia.org/wiki/World_Cyber_Games_2005)
- 2010s: (https://www.redbull.com/int-en/eg-universe-mvp-the-international-5)
- 2020s: (https://newsaf.cgtn.com/news/2021-11-07/Edward-Gaming-wins-2021-League-of-Legends-World-Championship-14YMbS1xCAE/index.html)
- Present: (https://www.esports.net/news/dota/the-international-stats-and-records)
- The International Championship: (https://www.google.com/search?q=The+international+dota+2&sa=X&sca_esv=260407b5166ebe05&rlz=1C1GCEU_en-GBCO1060CO1060&biw=2133&bih=1021&sxsrf=ACQVn09WqUoYSkH97hSg3BhB6EVig42miw:1714587755985&udm=2&source=iu&ictx=1&vet=1&fir=PgqW8iFIOLmwCM%252CGFfy3_hiCvcZHM%252C_%253BvJuonGEiWpEutM%252CJm8a-Znr129zEM%252C_%253BOp-w_eMJJNZMvM%252CqrL6D2MlgI6yFM%252C_%253B-FQIDDbHRW2C8M%252ChOR0r3__wMNOdM%252C_%253B0SJf_yYbKIWBQM%252CE6I8bYAMV4H5QM%252C_%253BH95w_n95agR7XM%252Ch07udbEIRV-cbM%252C_%253BxGkpIIftrPfHUM%252C_1__MFz28Hqt4M%252C_&usg=AI4_-kStaJk3EvYYDEy7clELnIzRSr_BMQ&ved=2ahUKEwjIwYaRie2FAxXlUUEAHQnxCrUQ_h16BAg8EAE#vhid=tGD7PFc4zKvVzM&vssid=mosaic)
- Katowice: (https://nerdstreet.com/news/2023/2/csgo-g2-esports-win-iem-katowice-2023)
- Esports 1: (https://www.sportspromedia.com/insights/opinions/esports-gaming-market-2022-faze-clan-streaming-acquisitions-microsoft-activision/)
- Esports 2: (https://www.mckkatowice.pl/pl/aktualnosci/g2-esports-wygrywa-iem-katowice-2023,2537.html)
- Esports 3: (https://www.oneesports.gg/dota2/team-spirit-wins-ti12/)
- Esports banner: [Canva](https://www.canva.com/)

### Acknowledgements

- I would like to thank my Code Institute mentor, Chris Quinn (https://github.com/10xOXR) for their support throughout the development of this project.
- I would like to thank Code Institute for giving me the opportunity to complete the 5P course.
- I would like to thank the Code Institute Slack community for moral support and helpful advice.
