# Kitty Den 
(Developer: Hannah Bowles)

![Mockup image](-need to add)

[Live webpage](https://hanmb17.github.io/CI_MS1_CATTERY/)

Welcome to the website for Kitty Den (a cat care company) it's been designed to provide a user-friendly experience for all visitors, with a responsive layout that adapts seamlessly to any device. The site gives easy access to information on their cat care services, staff profiles, customer testimonials and contact details.

## Table of Content

1. [Project Goals](#project-goals)
    1. [User Goals](#user-goals)
    2. [Site Owner Goals](#site-owner-goals)
2. [User Experience](#user-experience)
    1. [Target Audience](#target-audience)
    2. [User Requirements and Expectations](#user-requirements-and-expectations)
    3. [User Stories](#user-stories)
3. [Design](#design)
    1. [Design Choices](#design-choices)
    2. [Colours](#colours)
    3. [Fonts](#fonts)
    4. [Structure](#structure)
    5. [Wireframes](#wireframes)
4. [Technologies Used](#technologies-used)
    1. [Languages](#languages)
    2. [Frameworks and Tools](#frameworks-and-tools)
5. [Features](#features)
6. [Testing](#testing)
    1. [HTML Validation](#HTML-validation)
    2. [CSS Validation](#CSS-validation)
    3. [Accessibility](#accessibility)
    4. [Performance](#performance)
    5. [Device testing](#performing-tests-on-various-devices)
    6. [Browser compatibility](#browser-compatibility)
    7. [Testing user stories](#testing-user-stories)
8. [Bugs](#bugs)
9. [Deployment](#deployment)
10. [Credits](#credits)
11. [Acknowledgements](#acknowledgements)

## Project Goals

The main goal is to provide a responsive, fun-looking and informative website for Kitty Den that encourages users to enquire and hire them for cat care services.  

### User Goals
- A well-displayed and easy-to-navigate website
- Clear and informative information on what services are on offer
- Clear pricing information
- Easy to find contact information
- Easy to distinguish call-to-action buttons that make sense
- Find out information about the staff and their experience
- Find out the location of Kitty Den

### Site Owner Goals
- Increase in the number of customers
- Promote the business
- Provide multiple ways for customers to contact Kitty Den
- Display clear pricing information
- Provide a simple breakdown of services on offer
- Provide information about our staff and our history

### Developer Goals


## User Experience

### Target Audience
- Cat owner looking for cat care - overnight, home visits and daycare
- Cat owner looking for a dedicated cat-only care service
- Cat owner going away on holiday in need of cat care

### User Requirements and Expectations
- A simple and intuitive navigation system
- Quickly and easily find relevant information
- Links and functions that work as expected
- Good presentation and a visually appealing design regardless of screen size
- An easy way to contact the business
- Simple content that the user can skim read
- Accessibility

### User Stories

#### First-time User 
1. As a first-time user, I want to know where the Kitty Den is located.
2. As a first-time user, I want to know their prices.
3. As a first-time user, I want to know more about their services.
4. As a first-time user, I want to know what staff are there and what qualifications they have.
5. As a first-time user, I want easily find out how to contact them.
6. As a first--time user, I want to see what type of environment the cattery has to offer and if it is suitable, safe and stimulating for my cat.

#### Returning User
7. As a returning user, I want to know the opening times.
8. As a returning user, I want to find a phone number to call for a booking.
9. As a returning user, I want to see the pricing.
10. As a returning user, I want to know what the services are.
11. As a returning user, I want to get directions to Kitty Den.

#### Site Owner 
12. As the site owner, I want to promote my business online via a company website to increase my online visibility.
13. As the site owner, I want the users to see the cost of our services and what each service includes.
14. As the site owner, I want to make it easy for users to contact us via a variety of methods.
15. As the site owner, I want the users to get introduced to our skilled staff.

## Design

### Design Choices
I wanted to choose colours for Kitty Den from Megatron as he was the inspiration for the website. From a picture of him as a kitten, I picked out his beautiful blue eyes and pink nose as a starting point for the website colours.

<details><summary>Inspiration Image - Megatron as a kitten</summary>
<img src="">
</details>

### Colours
Using these colours as a base: 
I chose an off-white for background to help reduce too much glare.

I chose dark blue to allow for good contrast as the primary colour.
Blue is also great for a care company as it gives the feeling of trustworthiness.

I chose a bright dark pink to pop against the white background and the dark blue while giving a playful feel to the site.

Feeling I needed another colour, a bright orange that works as a complementary colour to the blue while working well with the pink was chosen. I used [ColorSpace](https://mycolor.space/) to help find the right orange for the pink. Orange is also great for getting the playful nature of the site across.

The colours I chose were:

- Blue: primary colour: #2E266D
- Pink: secondary colour: #DE1D8D
- Orange: tertiary colour: #FF735C
- Off White: white colour: #FAFAFA;
- Overlay Off White: rgba(250, 250, 250, 0.7) - They off white colour at 70% opacity
- White: #FFFFFF - Used for contrast against the pink and off-white background
- Opaque Pink: rgba(222, 29, 141, 0.5) - Used for style elements to give a pop of colour
- Light Orange: #ffd6d0 a shade of the orange tertiary colour to brighten areas.

I tested multiple options of blue and pink before choosing them and building the full-colour scheme around them to ensure I was happy with the colours and felt I had the best colours to match the site's requirements while remaining accessible. 
 
I used the abode colour wheel and ColorSpace to decide on the final colours and test the contrast of the colours with the Abode's accessibility tools and tested on the live site with the WebAIM Wave tool.

<details><summary>Branding Colour Ideas</summary>
<img>
</details>

### Fonts
Google Fonts is used to import the 'Indie Flower and Urbanist' font used throughout the website:
-[Indie Flower]() link font
-[Urbanist]() link font
<br> 
Indie Flower is predominantly used for headers and areas selected for styling, such as people's names. It helps them stand out and appear different from the other text on the site to make an instant impact as the user lands on the page.
<br>
Urbanist is used for the body of the text to make it easy to read and provides a modern look while offering a visual contrast against Indie Flower.
<br>
I picked these fonts as Indie Flower offers a playful and personal feel to the site, while Urbanist provides a clean, easy-to-read font with a sleek appearance. Together they work in harmony to portray the playful and professional feel of the company.

### Structure
The page's structure is in well-known, user-friendly and visually attractive way. On arriving, the user sees a recognisable navigation bar which on smaller displays is a hamburger menu to the right and the company's logo on the left. The website consists of six separate pages:
 
- Homepage - with the following sections unique selling points, intro to Kitty Den and customer testimonials. 
- About Us - Includes an intro into what they are, the history and conception of the company in a timeline style and a meet-the-staff carousel.
- Gallery - With information about the resident cats and images showcasing cats enjoying Kitty Den services
- Services - Simple and clean pricing cards with service detail included.
- Contact Us - Map of Kitty Den's location, Contact form and other contact and business information. 
- 404 - An image depicting the landing on a 404 page with a redirection button to help users find their way back.

### Wireframes

<details><summary>Home</summary>
Add Image
<img>
</details>
<details><summary>About Us</summary>
Add Image
<img>
</details>
<details><summary>Services / Prices</summary>
Add Image
<img>
</details>
<details><summary>Gallery</summary>
Add Image
<img>
</details>
<details><summary>Contact Us</summary>
Add Image
<img>
</details>

## Technologies Used

### Languages
- [HTML](https://en.wikipedia.org/wiki/HTML)
- [CSS](https://en.wikipedia.org/wiki/CSS)

### Frameworks and Tools
- [Bootstrap v5.3](https://getbootstrap.com/)
- [Git](https://git-scm.com/)
- [Github](https://github.com/)
- [GitPod](https://www.gitpod.io/)
- [Tiny PNG](https://tinypng.com/)
- [Balsamiq](https://balsamiq.com/wireframes/)
- [Google Fonts](https://fonts.google.com/about)
- [Font Awesome](https://fontawesome.com/search)
- [Code Pen]()
- [Affinity Developer 2 and Photo 2]()
- [Grammarly]()
- [W3C validator](https://validator.w3.org/)
- [Jigsaw CSS validator](https://jigsaw.w3.org/css-validator/)
- [WAVE Web Accessibility Evaluation Tool](https://wave.webaim.org/)

## Features
The page consists of six pages and ?? features.

### Logo and Navigation Bar
- Featured on all six pages
- The navigation bar is designed to be fully responsive for all screen sizes. It changes to a toggler (hamburger menu) on smaller screens. The following links are included: About Us page, Services & Prices page, Gallery Page and the Contact Us page.
- Users can easily navigate the site with its user-friendly interface.
- The link for the page the user is currently on is bold and underlined in pink.
- On smaller devices, the hamburger menu animates to a pink cross button to easily identify how to close the menu.
- The left includes Kitty Den's logo, which acts as a home button.
- User stories covered: 1, 2, 3, 5, 6, 8, 9, 10, 13.

### Call to Action Buttons
- Each button looks the same and is labelled clearly, allowing the users to know they are a button and where they go.

### Hero Image / Landing Page
- Header and tagline to make it clear what Kitty Den is and offers
- The background image of Megatron in black and white with only his blue eyes and pink nose in colour to not distract too much from the text but reinforce the branding colours.
- A clear call to action button to direct the users to the services on offer. 
- User stories covered: 

### Unique selling points 
- Introduces the user to the benefits of using Kitty Den.
- Icons are used to visually display the benefits with a header and short sentences to reinforce what Kitty Den offers.
- User stories covered:

### Carousel


### Reviews


### Map



### Footer


### About


### The Team


### Prices 


### Get In Touch

### 404


## Testing

### HTML Validation

The W3C Markup Validation Service was used to validate the HTML of the website. All pages pass with no errors.



### CSS Validation
The W3C Jigsaw CSS Validation Service was used to validate the CSS of the website.


### Accessibility


### Performance 
Google Lighthouse in Google Chrome Developer Tools was used to test the performance of the website. All aspects performing well.



### Performing tests on various devices 


### Browser compatibility


### Testing user stories

#### First-time User

#### Returning User



#### Site Owner 



## Bugs



## Deployment
The website was deployed using GitHub Pages by following these steps:
1. In the GitHub repository navigate to the Settings tab
2. On the left-hand menu select Pages
3. For the source select Branch: master
4. After the webpage refreshes automatically you will see a ribbon on the top saying: Your site is live at 

You can for fork the repository by following these steps:
1. Go to the GitHub repository
2. Click on Fork button in upper right-hand corner

You can clone the repository by following these steps:
1. Go to the GitHub repository 
2. Locate the Code button above the list of files and click it 
3. Select if you prefer to clone using HTTPS, SSH, or Github CLI and click the copy button to copy the URL to your clipboard
4. Open Git Bash
5. Change the current working directory to the one where you want the cloned directory
6. Type git clone and paste the URL from the clipboard ($ git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY)
7. Press Enter to create your local clone.

## Credits


### Media




### Code 



### Acknowledgements

