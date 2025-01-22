# Project Name: Collab Dating App
### Description: 
There are many dating apps in the market nowadays, and every single one of them targets the audience in a different way by the way they approach possible users.
After doing some research and even interviewing people from different ages and interests, I came to the conclusion that the Dating App World still can be improved. Therefore, I consider this is a good idea for my Project.

## Project Structure
1. Navigation Bar
The Navigation Bar contains the menu with the following sections:
- Home
- AboutUs
- Media
- Stories
- Contact

    This is a hidden menu that can be accessed through the hamburger icon. The goal is a minimalist layout for the user.

2. Logo Section
The logo section is located at the top of the page, after the Navigation Bar, and contains the logo of the app.

3. Hero Header
This section introduces the user and the application, with a welcoming message and two buttons to download the mobile app.

4. Features Section

## Features
0. The project was created using Astro
1. Moving background
The background of the Logo Section was designed to create an effect of movement using the main colors of the website.
2. Dark/Light Mode
The website offers the option of changing between a dark and light mode, based on the user's preferences.
3. Use of GSAP:
    - The Navigation Bar uses GSAP to give personality to every link to the main section of the webpage. The effect takes place when the page is reloaded. 
    - The app title "Collab" rolls as the webpage is opened.
    - The subheadings have a background blur effect while the website is loaded. 
3. iOS and Android buttons
These buttons are located in the Hero Header section, and contain a link that simulates the downloading of the iOS and Android mobile version of "Collab".

## Project Structure Astro
/src
  /components
    DarkLightMode.astro
    Navbar.astro
    Header.astro
    Footer.astro
  /pages
    index.astro
  /styles
    styles.scss
/public
  /css
    styles.css
  /images
    logo.png
    welcome-img.jpg
  /js
    app.js


## Installation
1. Clone this repository
``` 
git clone https://github.com/MajitoBrinkitos/pitch-project.git 
```

2. Install dependencies
```
npm install
```

3. Node version
- Preferably a version number higher than v18.17.1 or v20.3.0
```
node -v
```
