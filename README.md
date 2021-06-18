# Bae Abermaw Hotel

## [The Live Website](https://martinbannister.github.io/CI_MS1_BaeAbermawHotel/)

![Mockup](https://github.com/martinbannister/CI_MS1_BaeAbermawHotel/blob/master/docs/mockup/mockup.png)

## Table of Contents
---
1. [Project Goals](#project-goals)
    1. [Business Goals](#business-goals)
    2. [User Goals](#user-goals)
2. [User Experience](#user-experience)
    1. [Target Audience](#target-audience)
    2. [User Stories](#user-stories)
        1. [First Time Visitors](#first-time-visitors)
        2. [Regular Visitors](#regular-visitors)
        3. [Website Owner](#website-owner)

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
#### Returning Visitors
6. As a returning visitor I want to book a room quickly and easily.
7. As a returning visitor I would like to read more information about the area that I might have overlooked on my first visit.
8. As a returning visitor I want to spend time looking at photo's of the room I've got booked so I can look forward to my holiday.
#### Hotel Owner
9. As the hotel owner I want customers to be able to book a room with the minimum amount of friction.
10. As the hotel owner I want to convey the quality of the hotel and rooms through the website.
11. As the hotel owner I want the website to reflect the style and brand of the hotel.

## Scope
Based on the goals, business and user requirements for this inital release I have opted for a simple tree structure with only 1 level of depth.  This means no information is hidden or burried, the user can't get lost and there is a strong call to action on every page.<br>
Based on that I have defined the following features:
- A Navigation header is present on all pages and does not collapse completely on mobile failitating rapid navigation.
- A fixed footer at the bottom of every page offers navigation when the header navigation is out of view and provides social media links.
- A *book now* button provides a modal form to book a room from whichever page.
- The home page includes key information about the facilities available.
## Design
### Colour Scheme
### Typography
### Images

## Wireframes

## Features
### Current Features
#### Feature 1
**User stories covered by this feature**


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

## Testing

### HTML Validation
I used the [W3C Markup Validation Service](https://validator.w3.org/) to validate the HTML of all the pages on the site. Initially the pages showed some errors and these were corrected.

Links to the inial report and the final result with no errors are in the table below.

Initial | Final
-|-
[index.html](docs/validation/html/index_html_validation_initial.pdf) | [index.html](docs/validation/html/index_html_validation_final.pdf) 
[rooms.html](docs/validation/html/rooms_html_validation_initial.pdf) | [rooms.html](docs/validation/html/rooms_html_validation_final.pdf)
[about.html](docs/validation/html/about_html_validation_initial.pdf) | [about.html](docs/validation/html/about_html_validation_final.pdf) 
[contact.html](docs/validation/html/contact_html_validation_inital.pdf) | [contact.html](docs/validation/html/contact_html_validation_final.pdf)
[404.html](docs/validation/html/404_html_validation_initial.pdf) | Passed 1st time


### CSS Validation
I used the [W3C CSS Validation Service](http://jigsaw.w3.org/css-validator/validator) to validate my style.css file of the site.

The CSS passed first time with [zero errors](docs/validation/css/W3C_CSS_Validation.png).

### Accessibility
I used the [WAVE WebAIM web accessibility evaluation tool](https://wave.webaim.org/report#/https://martinbannister.github.io/CI_MS1_BaeAbermawHotel/) to check that there we no issues with accessibility standards.  

All pages pass without errors except for about.html.

There is a contrast error on about.html due to the colour of the # of # ( x / y ) text in the corner of the image slideshow.  This is due to the colour of the text matching the background of the page.  However I chose this colour for consistency of design and because it provides the best contrast with the area of the images it overlays.  The contrast error caused by using the same colour as the background is on the basis that the text should still be visible should the image fail to load, however in this case without the loaded image the '#image of #images' is irrelevant anyway. So I decided that this error need not be resolved.

Click on the links to see each report:

[Wave index.html](docs/validation/accessibility/wave_validation_index.png)

[Wave rooms.html](docs/validation/accessibility/wave_validation_index.png)

[Wave about.html](docs/validation/accessibility/wave_validation_about.png)

[Wave contact.html](docs/validation/accessibility/wave_validation_contact.png)

[Wave 404.html](docs/validation/accessibility/wave_validation_404.png)

### Performance

### Performance Tests on Various Devices

#### Devices Tested
- Honor 10 (Chrome & Firefox)
- Honor Play
- Lenovo Thinkpad C13 Yoga (Chrome & Firefox)
- iPhone XS Max

#### Tests Performed

#### Results

### Browser Compatibility
- Google Chrome
- Mozilla Firefox

### Testing User Stories

## Bugs found and resolved during development

## Deployment

### GitHub Pages

### Forking the GitHub Repository

### Making a Local Clone

## Credits
*All credits included in code where applicable*

### Code
**W3C Schools** - For [Image Slideshow](https://www.w3schools.com/howto/howto_js_slideshow.asp)

**Stack Overflow** - [default select option as blank - Stack Overflow](https://stackoverflow.com/questions/8605516/default-select-option-as-blank)

### Media

### Acknowledgements

- To my husband Graham for coping on your own whilst I was shut away coding and for your help testing.
- To my testers:
    - Lawry Ward
    - Wendy Scott
- To the Code Institute and Portfolio Project, the always present navigation of which inspired the navigation for smaller screens on my site.
- To Millie Kat for keeping me company whilst I was coding.
- To Mo Shami my mentor for whipping me into shape.
- To my Code Institute peers, without whom I'd have never have submitted on time or known how.