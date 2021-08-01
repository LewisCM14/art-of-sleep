# The Art of Sleep

The Art of Sleep is a static front-end site, designed to be a guide to the right mattress firmness based on how the user sleeps. Built on behalf of a fictitious mattress manufacturing company, its primary goal is to educate its users on: different sleeping positions, the health implications of how they sleep and measures that can be taken to improve their health. 

The secondary goal of the site, is to build a positive relationship between the user and the mattress company, encouraging them to sign up for the newsletter and consult the ‘sleep-experts’ at Martin Mattress Co. On the products they offer. 

![readme hero image](/assets/images/readme-hero.png)
## User Experience (UX)

- **User Stories**

    + **First Time Visitor Goals**
    
        A. A first-time visitor to the site should instantly see that the sites goal is primarily to educate the user on the best mattress firmness dependant on sleep position.   

        B. The educational information should be clear and concise, encouraging the user to interact with the navigational options presented to them.  

        C. The user should be encouraged, through a positive experience, to sign up to the company's newsletter. 

    + **Returning Visitor Goals**

        A. A returning visitor should be encouraged to request a consultation with a sleep expert on what product's the company offer.

    + **Frequent Visitor Goals**

        *Due to the nature of the product being sold, a frequent visitor would be defined as someone who previously brought a mattress that has now reached the end of its lifespan.* 
        
        A. To briefly re-educate the user on the best mattress dependant on their sleep position.

        B. Encourage the user to request a call back from a sleep expert with the company they have now built a relationship with. 

    - **Owners Story**

        A. The primary goal of the owner is to educate their users on the importance of choosing the correct mattress based on how the user sleeps. 

        B. Pursuit of the primary goal is intended to build a positive relationship between owner and client. 

        C. The end goal of the owner is to have the user sign up for the newsletter and request a consultation. 

- **Market Research**

    *Research into competing mattress sellers within the UK, showed that only two are designated bed stores, the remaining three being superstores. Focusing on these two more direct competitors the following pros and cons of their websites should be considered moving forward with the project.*

    + **Pros**

        A. Customer testimonial's easy to find.  
        
        B. Wide range of products on offer with competitive pricing and finance options.

        C. Distinct branding and evidence of company history.   

    + **Cons**

        A. Vast range of products and information on offer can be hard to navigate.  

        B. A personal connection between user and company cannot be developed easily, only evident goal is the sale of products.

        C. The colour pallets used has a wide range, making it hard to find familiarity across the pages for the user. 

    - **Features**

        *The website should be responsive across all devices*

        1. Interactive educational articles/hyperlinks   

        2. Newsletter sign up.  

        3. Form for requesting a consultation on products. 

        4. About Us/Contact page. 

        5. Customer testimonials. 

## Design

- **Colour Scheme**

    *Research into colour theory surrounding sleep, showed that people with blue bedrooms enjoyed the most sleep in hours per night. Based on this and market research into competing bed stores, I chose a limited colour pallet developed with https://mycolor.space/ Designated colours are as follows:* 
            
    1. #0000FF (Blue)
    2. #9A89B4 (Light Purple)
    3. #FDF7FF  (Off-White)
    4. #1E1926  (Off-Black)

        ![color scheme image](/assets/images/colors.png)

- **Typography**

    *I chose **Comfortaa** with a weight of 300 as the font for the main bodies of text and **Varela Round** for headings and any text which required additional impact. Both these fonts are ‘rounded’ and I felt this was emotive of the websites goal and products being sold.*

- **Imagery**

    * All imagery for the website is based off the pre-determined colour pallet, in order to try avoid the negative impact I felt the large colour pallet's had on the competing websites.  

    * It is strictly limited to images of inside a home, with an attempt to incorporate as many interior design styles as possible in order to appeal to a large target audience. 

    * No people or animals are to be displayed in the imagery in order for the user to be able to imagine themselves within the depicted scene.

- **Layout**

    * I decided on a multi-page website because I felt like each section deserved it's own dedicated page.

## Existing Features

- **Header Bar**

    * Featured on all pages, the full responsive header/navigation bar includes links to the: Home, About, Contact and the three sleep style pages. It is identical on each page to allow for easy navigation.

    * The header also allows the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button. 

        ![header bar image](/assets/images/header.png)

-  **The Index Page Image**

    * The landing includes a photograph with text overlay to instantly inform the user of the sites purpose

        ![index page hero image](/assets/images/landing-page.png)

- **The Positions Section**

  * The positions section is designed to educate the user on the different sleep positions, allowing them to identify with their style. 

  * The heading, designed to look like a button, uses icons to encourage the user to interact with it and learn more about their sleep style. 
    
    ![positions section image](/assets/images/positions.png)

 - **The Footer** 

    - The footer section includes links to the relevant social media sites for Martin Mattress Co. The links will open to a new tab to allow easy navigation for the user.This is valuable as it encourages them to keep connected via social media.

    - The footer is also responsive and styled the same across all pages for uniformity, also containing copyright information.

    ![footer image](/assets/images/footer.png)

- **Sleep Style Pages**

  - All sleep style pages are styled minimalistically so to highlight the key information surrounding the health implications of different sleeping positions. 

  - Responsive across various device sizes, it encourages the user to scroll by suggesting at information outside of the viewing size.

    ![sleep style image](/assets/images/sleep-style.png)

- **Contact Page**

    - The contact page is designed to look like a typical form type you would see on paper, using whitespace to keep it narrow. 

    - The page holds all the key contact information for the company and allows the user to request a consultation at their convivence. An image of the fictitious company headquarters is used to compliment this. 

- **About Us Page**

    - The about us page uses a predominantly white background image with slight opacity to bring the key information surrounding The Martin Mattress Company to the forefront.

        ![about us image](/assets/images/about.png)

    - The newsletter sign up section on the about us page is designed to be responsive and loosely mimic the appearance of a folded newspaper. 

        ![newsletter image](/assets/images/newsletter.png)

## Features Left to Implement

- Customer Testimonials 

- Detailing of specific products Martin Mattress Co. offer.

## Testing 

- I tested my site on: Chrome, Firefox and Internet Explorer. It performed as intended on all three browsers. This testing was done on the pc I built the site on. 

- I also tested the site on my own iPhone x. upon testing on this device the site did not perform as intended. The breakpoint I chose for mobile devices was 320x470, however an iPhone x is 375x812. I corrected this bug by defining a specific iPhone x Media Query.

- I also tested the site on my laptop, the only noticeable bug was the height of the textarea section for the form on the contact page took it outside of the designated container. I fixed this bug by reducing the rows/cols value on it.  
## Validator Testing 

- HTML
    - No errors were returned when passing through the official [W3C validator](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html)
- CSS
  - No errors were found when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css)

## Unfixed Bugs

- The only major unfixed bug I was aware off upon final deployment was that, although redefining my mobile device breakpoint to 375, fixed the site not preforming as intended on an iPhone x on Chrome Developer Tools. When opening the site on my actual device, it still didn’t perform as intended. I was unable to fix this problem due to time constraints and lack of knowledge as to understanding the route cause. 

- Although I used Chrome Developer Tools to ensure my site preformed as intended at my predetermined breakpoints, which I felt covered a wide spectrum, I noticed slight issues with display of the: Header, Footer and the landing page hero image/cover text. I would have liked to widen my range of breakpoints to help address this problem, however time constraints prevented me from doing so. 
  
## Deployment

- The site was deployed to GitHub pages. The steps to deploy are as follows: 

  - In the GitHub repository, navigate to the Settings tab 
  - From the source section drop-down menu, select the Master Branch
  - Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment. 

The live link can be found here - https://lewiscm14.github.io/art-of-sleep/

## Technologies Used

- **Languages Used**

    * HTML5
    * CSS3

- **Frameworks, Libraries & Programs Used**

    1. Balsamiq. 
            * Balsamiq was used to create the wireframes during the design process.

    2. mycolour.space.
            * Used to define my  colour pallet for the project based of my primary colour choice.

    3. Google Fonts. 
            * Used to import the Comfortaa and Varela+Round font into the style.css file which is used on all pages throughout the project.

    4. Font Awesome.
            * Font Awesome was used on all pages throughout the website to add icons for aesthetic and UX purposes.

    5. Git.
            * Git was used for version control by utilizing the Gitpod terminal to commit to Git and Push to GitHub.

     6. GitHub.
            * GitHub is used to store the projects code after being pushed from Git.

    7. Am i Responsive
            * Used to create hero image for readme.

## Credits 

* A special thank you to my mentor Can Sucullu. 

* Thanks to my peers on Slack who responded to my questions.  

- **Content** 

    * The text for the position classes on the home page was developed off the core information located on https://www.onhealth.com/content/1/best_sleeping_positions_sleep 

    *  The text for the different sleep style was developed off the core information located on https://sleepopolis.com/blog/firm-vs-soft-mattresses-pros-cons/ 

    * I used the guide on https://coder-coder.com/background-image-opacity/ to help me make use of the ::before psudo class used on the about page

    * I used the breakpoints listed on https://www.freecodecamp.org/news/css-media-queries-breakpoints-media-types-standard-resolutions-and-more/ for me media queries

- **Media**

    * All images are taken from: 
        * https://www.pexels.com/ 
        * https://pixabay.com/
        * https://www.rawpixel.com/?sort=shuffle&page=1&feed=creative-feed
