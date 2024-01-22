# Mixology Society

# Project Overview

Welcome,

This is the Mixology Society website, which provides information about the University of Luketon's Mixology Society.

The following are high-level details of this project:

- The main technologies used are HTML5, CSS3 and Bootstrap version 5 (framework).
- The project consists of three separate web page sections (Home, About Us & Sign Up).
- A top navigation bar is established for information architecture.
- Git & GitHub are used for version control.
- Any external code sources used in the project are clearly identified in the code itself and in this README.md file
- The final version has been deployed via GitHub Pages.

The last update to this file was: **January 22nd, 2024**

# Table of Contents

- [Mixology Society](#mixology-society)
- [Project Overview](#project-overview)
- [Table of Contents](#table-of-contents)
- [UX](#ux)
  - [User Goals](#user-goals)
  - [User Stories](#user-stories)
  - [Site Owners Goals](#site-owners-goals)
    - [Requirements](#requirements)
    - [Expectations](#expectations)
- [UI / Design Choices](#ui--design-choices)
  - [Moodboard](#moodboard)
  - [Fonts](#fonts)
  - [Icons](#icons)
  - [Colours](#colours)
  - [Breakpoints](#breakpoints)
  - [Wireframes](#wireframes)
- [Features](#features)
  - [Existing Features](#existing-features)
    - [Navigation Bar](#navigation-bar)
    - [Home Section](#home-section)
- [Technologies used](#technologies-used)
  - [Languages](#languages)
  - [IDE](#ide)
  - [Libraries \& Framework](#libraries--framework)
  - [Tools](#tools)
- [Deployment](#deployment)
- [Credits](#credits)

# UX

## User Goals

1. Visually appealing, including images.
2. Easily navigated around.
3. Quality and valuable content.
4. Easily found contact details.
5. Form to directly contact the society club.

## User Stories

1. As a user, I want to know that the society club is well established.
2. As a user, I want to be able to easily contact the club.
3. As a user, I want to be able to make contact with the club via different methods, i.e. social media.
4. As a user, I want to be able to easily navigate through the website.
5. As a user, I want to know what events are taking place.
  
## Site Owners Goals

1. Promote the club.
2. Increase the number of members.
3. Increase rankings on search engines.
  
### Requirements

1. Easy to navigate on various screen sizes.
2. Clear information on the services provided.
3. Keep the user interested with the club's values to make them want to engage with the society club.
4. Simple methods of contacting the society club.
5. Visually inviting so users do not leave.
  
### Expectations

1. I expect to know if a form has been submitted properly and if items are not filled in, to be prompted.
2. I expect all links to social media sites to be opened in a new tab.
3. I expect all navigation links to work correctly.
4. I expect screen size not to affect the quality of the website.
5. I expect all information to be correct and accurate.

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

# UI / Design Choices

## Moodboard

One of the first milestones of this project was to create a moodboard to help envision the overall house style of the webiite and ensure that all of the sections and elements are cohesive. The software I used to create the moodboard for this website is [Mila Note](https://milanote.com/ "Mila Note").
Below, is the moodboard:
![Moodboard](assets/img/moodboard.png)

## Fonts

In order to move away from the basic fonts available, I have used
[Google Fonts](https://fonts.google.com/ "Google Fonts") to find a text that best suits the feel of the website. For the main text I have chosen [Glory](https://fonts.google.com/specimen/Glory "Glory font") as I feel it is has a sharp, simple and easy to read look. To make the navigation bar stand out form the text, I decided to use [Inter](https://fonts.google.com/specimen/Inter?query=inter "Inter font"). This font is complimentary to the Glory font, and will help be distinctive as navigation links in the header.

## Icons

I will use some icons for my website from the [Font Awesome library](https://fontawesome.com/ "Font Awesome"). These icons will be used in the About Us Section and also the social media links in the footer. All icons used will be styled and in keeping with the appearance of the website.

## Colours

The colour scheme of the website is inspired by the moodboard (previously depicted). I have used [Coolers](https://coolors.co/ "coolers") to retrieve the desired colour codes and generate the colour palette.

Below, is the color palette:
![Colour Palette](assets/img/colour_palette.png)

## Breakpoints

As a starting point, I will be building my website with a mobile first mindset using the iPhone 5/SE (320px) as the smallest screen size for styling to look good on. The screen size breakpoints that I will be using are from [Bootstrap breakpoints](https://getbootstrap.com/docs/5.0/layout/breakpoints/ "Bootstrap").

| Screen Size | Class Infix | Breakpoint |
| ----------- | ----------- | ---------- |
| x-small     | none        | <576px     |
| small       | sm          | => 576px   |
| medium      | md          | => 768px   |
| large       | lg          | => 992px   |
| x-large     | xl          | => 1200px  |

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

## Wireframes

I have used [Balsamiq](https://balsamiq.com/wireframes/ "Balsamiq") to develop my wireframes for my website. I initially created the mobile version and then the wireframes and then scalled it up for both tablet and desktop. The website is a one-pager, that is split up into 3 sections. This gets the user through the content and quickly to the contact form and details via scrolling or directly via the navigation bar.

The wireframes are below:

[Home Section - Desktop Wireframe](assets/wireframes/1-home-desktop-wireframe.png "home desktop wireframe")

[Home Section - Phone Wireframe](assets/wireframes/1-home-phone-wireframe.png "home phone wireframe")

[About Section - Desktop Wireframe](assets/wireframes/2-about-desktop-wireframe.png "about desktop wireframe")

[About Section - Phone Wireframe](assets/wireframes/2-about-phone-wireframe.png "about phone wireframe")

[Sign Up Section - Desktop Wireframe](assets/wireframes/3-signup-desktop-wireframe.png "signup desktop wireframe")

[Sign Up Section - Phone Wireframe](assets/wireframes/3-signup-phone-wireframe.png "signup phone wireframe")

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

# Features

## Existing Features

### Navigation Bar

The navigation bar is responsive for various screen sizes. It includes links to fast-track to the respective sections within the one-page site.

- Desktop (>=992px)
\
&nbsp;
    ![Navigation bar](assets/features/desktop-navbar.png)
  - Spanning the entire width of the device, the navigation bar presents all the links (Home, About Us, Sign Up) in an organized manner; this provides a straight-forward and convenient user experience.

  - In order for the user to identify which of the links their cursor is hovering over, the respective link text appears bold.

    ![Navigation bar link on hover](assets/features/desktop-nav-hover.png)
    \
    &nbsp;
  - For the convenience of switching sections, the desktop navigation bar is permanently fixed at the top of the screen, so even if the user scrolls down, they will have access to it.

    ![Navigation bar fixed at top](assets/features/nav-bar-scrolled.png)
    \
    &nbsp;

- Small devices (<992px)
\
&nbsp;
  - As the navigation bar would be too cramped as a row at the top of 'smaller' devices, it is set to be a column on the right side of screen.

    \
    &nbsp;
    ![Nav bar on small devices](assets/features/small-navbar.png)

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

### Home Section

- Background Image
  - The image immediately indicates what the club is about and fits the colour scheme.
  - The text informs the user on what the club is and what the website is about. The colours suit the colour scheme, the font style is appropriate for the club aesthetic. The text size and style is also easy to read and is eye-catching.
    \
    &nbsp;

    ![Home Section](assets/features/home-section.png)

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

# Technologies used

## Languages

- [HTML](https://en.wikipedia.org/wiki/HTML "HTML")
  
- [CSS](https://en.wikipedia.org/wiki/CSS "CSS")

## IDE

- [Codeanywhere](https://codeanywhere.com/ "Codeanywhere")

## Libraries & Framework

- [Google Fonts](https://fonts.google.com/ "Google Fonts")
  
- [Font Awesome library](https://fontawesome.com/ "Font Awesome")
  
- [Bootstrap](https://getbootstrap.com "Bootstrap")

## Tools

- [Mila Note](https://milanote.com/ "Mila Note")
  
- [Balsamiq](https://balsamiq.com/wireframes/ "Balsamiq")

- [CI Full Template]("https://github.com/Code-Institute-Org/ci-full-template" "CI Full Template")
  
- [Font Awesome library](https://fontawesome.com/ "Font Awesome")
  
- [Google Fonts](https://fonts.google.com/ "Google Fonts")

- [Coolers](https://coolors.co/ "coolers")

- [W3C HTML Validation Service](https://validator.w3.org/ "W3C HTML")
  
- [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/ "W3C CSS")

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

# Deployment

This project was deployed using GitHub Pages through the following steps:

1. Navigating to the repository on github and click 'Settings'.
2. Selecting 'Pages' on the side navigation.
3. Selecting the 'None' dropdown, and then clicking 'main'.
4. Clicking on the 'Save' button.
5. Now the website is live on [MixSoc Live Website](https://rachelcluke.github.io/mixology-society/ "MixSoc Website")
6. If any changes are required, they can be done, commited and pushed to GitHub and the changes will be updated.

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

# Credits

For mentoring, code advising and project reviewing:

- [Simen Daehlin](https://github.com/Eventyret "Simen Daehlin")

\
&nbsp;

For technical support and guidance:

- Tutors at Code Institute
  
- [Bootstrap Flex Doc](https://getbootstrap.com/docs/4.0/utilities/flex/ "Bootstrap Flex Doc")

\
&nbsp;

For content inspiration:

- [Cardiff Cocktail Society](https://www.cardiffstudents.com/activities/society/cocktailsociety/ "Cardiff Cocktail Society")
  
- [Aber Cocktail Society](https://www.abersu.co.uk/society/cocktailsociety/ "Aber Cocktail Society")

\
&nbsp;
[Back to Top](#table-of-contents)
\
&nbsp;

---

Thank you - from Rachel Luke!
