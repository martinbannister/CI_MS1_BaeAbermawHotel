# Bae Abermaw Hotel

![Mockup](https://github.com/martinbannister/CI_MS1_BaeAbermawHotel/blob/master/docs/mockup/mockup.png)

## [The Live Website](https://martinbannister.github.io/CI_MS1_BaeAbermawHotel/)

## Table of Contents
---
1. [Project Goals](#project-goals)
    1. [Business Goals](#business-goals)
    2. [User Goals](#user-goals)
2. [User Experience](#user-experience)
    1. [Target Audience](#target-audience)
    2. [User Stories](#user-stories)
        1. [First Time Visitors](#first-time-visitors)
        2. [Returning Visitors](#returning-visitors)
        3. [Hotel Owner](#hotel-owner)
3. [Scope](#scope)
    1. [Design](#design)
    2. [Colour Scheme](colour-scheme)
    3. [Typography](#typeography)
    4. [Images](#images)
4. [Wireframes](#wireframes)
5. [Features](#features)
6. [Technologies Used](#technologies-used)
7. [Testing](#testing)
    - [Bugs During Development](#Bugs-found-and-resolved-during-development)
8. [Deployment](#deployment)
9. [Credits](#credits)
10. [Acknowledgements](#acknowledgements)

## Project Goals
---
### Business Goals
The business goals of Bae Abermaw Hotel are:
- Convert more site visitors by making it quick and easy to book a room from any page.
- Increase guests by conveying the quality and luxury of the hotel through their website.
- Showcase the quality of hotel.
- Showcase the local area and amenities accessible from the hotel.
### User Goals
- Find a high quality hotel that also accepts pets.
- Be able to book quickly and easily without having to navigate around the site, regardless of the device on which it's used.
- See the rooms and facilities on offer.
- See what the local area has to offer when staying.

[Back to Index](#table-of-contents)

## User Experience
---
I have designed this site with a mobile first approach so the site is clear, easily navigable and the content collapses well and still looks good on smaller screens.

The user experienced is based around the main business goal of converting more website visitors by making it easy to book from any page.  This is why I chose not to hide the navigation in a collapsible menu on smaller devices.  All pages retain the header navigation, albeit styled differently, with the "Book Now" button featuring prominently on all devices.

### Target Audience
- Holiday Makers
- Pet Owners
- Families
- Business People
- Casual Diners
### User Stories
I have chosen to break down my user stories into three separate sections based on how a user will interact with the website.  **First time visitors** will invariably want more information than **returning visitors** who are more likely to know exactly where to go or in the case of Bae Abermaw Hotel book a room.  Finally we have the **hotel owner's** perspective of how they want the site to be used.
#### First Time Visitors
1. As a first time visitor I want know what the hotel offer and whether it can cater for my family and dog.
2. As a first time visitor I want to be able to access the hotel's social media accounts so I can see what real people think of the place.
3. As a first time visitor I want to be able to see the rooms to establish if they're suitable for my needs.
4. As a first time visitor I want to find the location of the hotel so I can check if it's close to other attractions in the area.
5. As a first time visitor I want to be able to book a room easily if I like that I see.
6. As a first time visitor I want to be able to contact the hotel to check if they meet any requirements I have not apparent on the site.

[Back to Index](#table-of-contents)

#### Returning Visitors
7. As a returning visitor I want to book a room quickly and easily.
8. As a returning visitor I would like to read more information about the area that I might have overlooked on my first visit.
9. As a returning visitor I want to spend time looking at photo's of the room I've got booked so I can look forward to my holiday.

[Back to Index](#table-of-contents)

#### Hotel Owner
10. As the hotel owner I want customers to be able to book a room with the minimum amount of friction.
11. As the hotel owner I want to convey the quality of the hotel and rooms through the website.
12. As the hotel owner I want the website to reflect the style and brand of the hotel.

[Back to Index](#table-of-contents)

## Scope
Based on the goals, business and user requirements for this inital release I have opted for a simple tree structure with only 1 level of depth.  This means no information is hidden or burried, the user can't get lost and there is a strong call to action on every page.<br>
Based on that I have defined the following features:
1. A Navigation header is present on all pages and does not collapse completely on mobile failitating rapid navigation.
2. A fixed footer at the bottom of every page offers navigation when the header navigation is out of view and provides social media links.
3. A *book now* button always present in the footer provides a modal form to book a room from whichever page the visitor is on.
4. The home page includes key information about the facilities available.
5. The rooms page allows visitors to see what's available before booking.
6. The about page tells potential customers about the hotel and the currounding area and facilities.
7. The contact page provides a means of getting in touch before booking and allows visitors to find the hotel.

## Design
The design of the site was inspired by a visit to the hotel. The colour scheme used in the public areas and rooms was very modern, appealing and gave a feeling of luxury.  I was inspired to create a site that reflected that same design asthetic and colour scheme and conveyed a sense of luxury. The view from our room was spectacular and given the hotels tag line, "A View To Luxury", I felt this was the perfect image to greet people with.

### Colour Scheme
The colour scheme was inspired by the hotel itself, the teal colour used on their walls was derived from a [photo I took](docs/images/dining_01_small.png) of the dining room, and the gold colour from their [logo](assets/images/logo.png).

### Typography
I selected the Parisienne font for the home screen circle heading because I wanted something that was legible but also conveyed a sense of style and class.  

I used the Raleway font because I wanted a sans-serif font that was also easy to read but again was somewhat classy and not pedestrian.

Both fonts are served from [Google Fonts](https://fonts.google.com/)

### Images

All images were either taken by myself or taken from the hotel's existing website.

#### My Images

[A view to luxury](assets/images/a_view_to_luxury.png)

Bay images [1](assets/images/bay_img_1.jpg) [2](assets/images/bay_img_2.jpg) [3](assets/images/bay_img_3.jpg) [4](assets/images/bay_img_4.jpg) [5](assets/images/bay_img_5.jpg)

[Double Sea view room](assets/images/double_sea_view_small.png)

[Double Sea view room ensuite](assets/images/ensuite_small.png)

[The bay](assets/images/the_bay.jpg)

#### Hotel's own images

All other images were obatained from the [hotels current website](https://www.baeabermawhotel.co.uk/en-GB/homepage)

[Double Standard Room](assets/images/double_standard_room_small.png)

[Double Standard Ensuite](assets/images/double_standard_ensuite_small.png)

[Family Room Sea View](assets/images/family_room_sea_view_small.png)

[Family Room Sea View Ensuite](assets/images/family_room_sea_view_ensuite_small.png)

[Logo](assets/images/logo.png)

## Wireframes
### Desktop
[Index](docs/validation/wireframes/wireframe-desktop-home.png)

[Rooms](docs/validation/wireframes/wireframe-desktop-rooms.png)

[About](docs/validation/wireframes/wireframe-desktop-about.png)

[Contact](docs/validation/wireframes/wireframe-desktop-contact.png)

[Modal Booking Form](docs/validation/wireframes/wireframe-desktop-book-modal.png)

### Tablet
[Index](docs/validation/wireframes/wireframe-tablet-home.png)

[Rooms](docs/validation/wireframes/wireframe-tablet-rooms.png)

[About](docs/validation/wireframes/wireframe-tablet-about.png)

[Contact](docs/validation/wireframes/wireframe-tablet-contact.png)

[Modal Booking Form](docs/validation/wireframes/wireframe-tablet-book-modal.png)

### Mobile
[Index](docs/validation/wireframes/wireframe_mobile_home.png)

[Rooms](docs/validation/wireframes/wireframe_mobile_rooms.jpg)

[About](docs/validation/wireframes/wireframe_mobile_about.jpg)

[Contact](docs/validation/wireframes/wireframe_mobile_contact.jpg)

[Modal Booking Form](docs/validation/wireframes/wireframe_mobile_book_modal.jpg)


## Features
### Current Features
1. A Navigation header is present on all pages and does not collapse completely on mobile failitating rapid navigation.

**User stories covered by this feature**
2 to 5
[Navigation on all sizes](docs/user_story_images/nav_on_all_sizes.png)

2. A fixed footer at the bottom of every page offers navigation when the header navigation is out of view and provides social media links.

**User stories covered by this feature**
2 and 3
[Footer on all pages](docs/user_story_images/footer_with_book_all_pages.png)

3. A *book now* button always present in the footer provides a modal form to book a room from whichever page the visitor is on.

**User stories covered by this feature**
5, 7 and 10
[Footer on all pages](docs/user_story_images/footer_with_book_all_pages.png)

4. The home page includes key information about the facilities available.

**User stories covered by this feature**
1
[Hope Page Features](docs/user_story_images/home_page_features.png)

5. The rooms page allows visitors to see what's available before booking.

**User stories covered by this feature**
3, 5 and 9

6. The about page tells potential customers about the hotel and the surrounding area and facilities.

**User stories covered by this feature**
4 and 8

7. The contact page provides a means of getting in touch before booking and allows visitors to find the hotel.

**User stories covered by this feature**
4 and 6
[Contact page](docs/user_story_images/contact_page.png)


### Future Features
Below is a list of features I would like to implement in the future.

- More comprehensive booking options and the ability to book without simply sending a request (Requires backend system integration).
- More image slidwshows of the hotel and its facilities.
- A more comprehensive and detailed list of the facilities and services offered.
- A full list of the rooms available.

## Technologies Used

### Languages
- [HTML5](https://en.wikipedia.org/wiki/CSS)
- [CSS3](https://en.wikipedia.org/wiki/CSS)
- [Javascript](https://en.wikipedia.org/wiki/JavaScript) (From W3C How To)

### Frameworks, libraries and other tools
[Halfmooon Framework](https://www.gethalfmoon.com/docs/modal/)

[Google Fonts](https://fonts.google.com/) Site fonts

[Font Awesome](https://fontawesome.com/) Used for social media icons

[Am I responsive](http://ami.responsivedesign.is/)

[Pic Resize](https://picresize.com/)

[Unicode Table](https://unicode-table.com/en/sets/)

[Gitpod](https://www.gitpod.io/)

[Google Maps](https://maps.google.com)


## Testing

### HTML Validation
I used the [W3C Markup Validation Service](https://validator.w3.org/) to validate the HTML of all the pages on the site. Initially the pages showed some errors and these were corrected.

Links to the inial report and the final result with no errors are in the table below.

- [index.html](docs/validation/html/index_html_validation_final.pdf) 

- [rooms.html](docs/validation/html/rooms_html_validation_final.pdf)

- [about.html](docs/validation/html/about_html_validation_final.pdf) 

- [contact.html](docs/validation/html/contact_html_validation_final.pdf)

- [404.html](docs/validation/html/404_html_validation_initial.pdf)

[Back to Index](#table-of-contents)

### CSS Validation
I used the [W3C CSS Validation Service](http://jigsaw.w3.org/css-validator/validator) to validate my style.css file of the site.

The CSS passed first time with [zero errors](docs/validation/css/W3C_CSS_Validation.png).

[Back to Index](#table-of-contents)

### Accessibility
I used the [WAVE WebAIM web accessibility evaluation tool](https://wave.webaim.org/report#/https://martinbannister.github.io/CI_MS1_BaeAbermawHotel/) to check that there we no issues with accessibility standards.  

All pages pass without errors except for about.html.

There is a contrast error on about.html due to the colour of the # of # ( x / y ) text in the corner of the image slideshow.  This is due to the colour of the text matching the background of the page.  However I chose this colour for consistency of design and because it provides the best contrast with the area of the images it overlays.  The contrast error caused by using the same colour as the background is on the basis that the text should still be visible should the image fail to load, however in this case without the loaded image the '#image of #images' is irrelevant anyway. So I decided that this error need not be resolved.

Click on the links to see each report:

- [Wave index.html](docs/validation/accessibility/wave_validation_index.png)

- [Wave rooms.html](docs/validation/accessibility/wave_validation_index.png)

- [Wave about.html](docs/validation/accessibility/wave_validation_about.png)

- [Wave contact.html](docs/validation/accessibility/wave_validation_contact.png)

- [Wave 404.html](docs/validation/accessibility/wave_validation_404.png)

[Back to Index](#table-of-contents)

### Performance

[Google Lighthouse](https://developers.google.com/web/tools/lighthouse/) produced a rating of 100 on Accessibility, Best Practices and SEO on all pages.  All pages except rooms.html rated between 97 and 99.  

rooms.html only rated 72 due to the size of the images that the page serves, some of which are hidden on initial page load.  The image sizes should be reduced however given the time constraints on this project I have decided to leave this for a future release since the inital user experience isn't significantly reduced.

- [Lighthouse index.html](docs/validation/performance/lighthouse_index.png)

- [Lighthouse rooms.html](docs/validation/performance/lighthouse_rooms.png)

- [Lighthouse about.html](docs/validation/performance/lighthouse_about.png)

- [Lighthouse contact.html](docs/validation/performance/lighthouse_contact.png)

- [Lighthouse 404.html](docs/validation/performance/lighthouse_404.png)

[Back to Index](#table-of-contents)

### Tests on Various Devices

#### Devices Tested
- Honor 10 (Chrome & Firefox)
- Honor Play
- Lenovo Thinkpad C13 Yoga (Chrome & Firefox)
- iPhone XS Max

#### Tests Performed

1. All links, including page naviagation and modal popup triggers arrive at the correct page and no links are broken.
2. External links open in a new tab on all devices and do not navigate away from the main site.
3. Content collapses neatly and continues to look tidy and be clearly visible on all devices.
4. Modals popup correctly, can be scrolled where necessary and dismissed easily.
5. The Book Now modal popup displays correctly on all pages, will not submit unless all required fields are completed and warns the user on error.
6. The contact us form displays correctly on all devices and will not submit unless all required fields are complete.
7. The map on the contact us page still functions at all screen sizes and correctly shows the location of the hotel.

#### Results

3. After removing the button around the *a* tag for the Book Now link following HTML validation the Book Now link spans the width of it's containing column at certain breakpoints, which on the **Kindle Fire HDX Lunix** (as identified in Firefox's inspector tool) specifically, does not look good.

---

5. The Book Now modal on Firefox for Android does not provide any validation warning when pressing the Book button and required fields have not been completed.  This is regardless of the field type left incomplete.  

Although an old thread the comment by user Simone on [Stack Overflow](https://stackoverflow.com/questions/43868163/required-attribute-does-not-work-on-firefox) suggests this could be because something is overridden by a stylesheet.  This will require further investigation.

---

6. The contact form suffers from the same problem on Firefox for Android as the Book Now modal.

### Browser Compatibility
- Google Chrome
- Mozilla Firefox

### Testing User Stories
Due to time contstraints I have not been able to document specific user testing scenarios.  However the images documented in [Features](#features) show a number of different scenarios related to each user story on different screen sizes and pages.

## Bugs found and resolved during development

- Couldn't makse single set of navigation itmes responsive in the way I wanted to.
    - Fix: added a second set of nav items that are hidden on smaller screen sizes whilst hiding the original nav items on larger sceens

- Custom hover CSS being ignored.
    - Fix: applied specific calsses to elements in question and this seemed to apply custom hover styles correctly.

- No social media icons in Google's Material Icons library.
    - Fix: resorted to Font Awesome's social icons.

- Vertical align footer nav elements.
    - Fix: referred to article on dev.to **(code reference 5)** on various ways of centreing elements.  Settled on using margins and chose to use view hight over pixles for more responsive margins.

- Looked up unicode checkmark character from unicode-table.com.
    - Used Ryan Sechrest **(code reference 3)** to find out how to insert a symbol as a custom bullet point.

- Found error on Honor Play when opening the link from WhatApp the booking form Date and Select elements did respond when tapped.
    - When using Chrome browser on the same device the input boxes worked as expected.  No spcific fix for the WhatApp error was identified.

- When viewing images on rooms.html in the modal popup on mobile the modal and subsequently images appeared small.
    - Fix: Changed the width utility class to display modal as full screen on smaller devices.

- Dots not scylcing with image after adding autocycling code from W3C.
    - Fix: Copied the dot cylcing code from the base function into the autoSlides() function.

## Deployment

### GitHub Pages
I have used GitHub pages to deploy this page.  If you would like to do the same you can follow these steps:

1. Log into your GitHub account and find the [repository](https://github.com/martinbannister/CI_MS1_BaeAbermawHotel). 
2. Click on 'Settings' in the repository. 
3. Click 'Pages' in the left-hand menu once you're in Settings. 
4. Click 'Source'.
5. Click the dropdown menu which says 'None', then select 'Master Branch'.
6. Wait for page to refresh automatically. 
7. Under GitHub pages you can now find a link to the published live website. 

### Forking the GitHub Repository
If you would like to fork this respository so you can make changes without affecting the original please follow these steps:

1. Log into your GitHub account and find the [repository](https://github.com/martinbannister/CI_MS1_BaeAbermawHotel).
2. Click 'Fork' (last button on the top right of the repository page).
3. You will then have a copy of the repository in your own GitHub account. 

### Making a Local Clone
In order to make a clone of this repository to work on locally, follow these steps:

1. Log into your GitHub account and find the [repository](https://github.com/martinbannister/CI_MS1_BaeAbermawHotel).
2. Click on the 'Code' button (next to 'Add file'). 
3. To clone the repository using HTTPS, under clone with HTTPS, copy the link.
4. Then open Git Bash.
5. Change the current working directory to where you want the cloned directory to be made.
6. In your IDE's terminal type 'git clone' followed by the URL you copied.
7. Press Enter. 
8. Your local clone will now be made.

## Credits
*All credits included in code where applicable*

### Code references
#### 1. **W3C Schools** - For [Image Slideshow](https://www.w3schools.com/howto/howto_js_slideshow.asp)

#### 2. **Stack Overflow** - [default select option as blank - Stack Overflow](https://stackoverflow.com/questions/8605516/default-select-option-as-blank)

#### 3. **Ryan Sechrest** - [Change your list bullet to a custom character in CSS](https://ryansechrest.com/2012/11/change-your-list-bullet-to-a-custom-character-in-css/)

#### 4. **W3c Schools** - For [hover overlay](https://www.w3schools.com/howto/howto_css_image_overlay.asp)

#### 5. **dev.to** - For [CSS Centreing methods](https://dev.to/elijahtrillionz/how-to-center-align-items-in-css-with-4-solid-methods-31c3)

### Media

All images used were taken by myself or from the existing hotel website.

Please see [Design - Images](#images) for further details.

### Acknowledgements

- To my husband Graham for coping on your own whilst I was shut away coding and for your help testing.
- To my testers:
    - Lawry Ward
    - Wendy Scott
- To the Code Institute and Portfolio Project, the always present navigation of which inspired the navigation for smaller screens on my site.
- To Millie Kat for keeping me company whilst I was coding.
- To Mo Shami my mentor for whipping me into shape.
- To my Code Institute peers, without whom I'd have never have submitted on time or known how.