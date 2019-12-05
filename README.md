# First milestone project - "Uplift Training Center gym website"

This project website is for a fictional gym named Uplift Training Center.  The site provides prospective gym clients with the basic information they might want
when considering joining a gym. i.e. classes, open hours, contact information and price plans.  The site is comprised of 3 static webpages and can be viewed in desktop, tablet and
mobile devices.   

 
## UX
 
The UX design for this project was mainly influenced by the gym websites fitnessfactorymaine.com and burnpilates.com.  The idea was to produce a concise, 3 page site that presented the user with the basic information they would want when considering joining a gym. After laying the foundation of the site, the final design and implementation was reached essentially via trial and error until i found a layout that provided a simple look and feel and ease of use across all screensizes.


## Features

### Existing Features
- **Home icon** - This is a fontawesome icon displayed on the left of the header that links to the homepage when clicked
- **Header links in desktop view** - The Classes and Plans links  are displayed in the header and link to their respective pages.
- **Hamburger menu in mobile view** - A hamburger menu is displayed in mobile view.  When clicked a dropdown menu displays the Classes and Plans links. The dropdown is a bootstrap component, but several styling and positional edits were made to fit the project look and feel.
- **Intro section** - THe intro section contains a short intro message about the gym, two images,  and a button that links to the plans screen. 
- **The Footer** - the footer section contains info on the gyms opening hours, contact info and functioning social media links.
- **Classes images and the timetable overlay** - for each gym class there is an image that displays the class timetable when hovered.
- **Plans** - there are 3 membership plans.  Gold, silver and bronze. Each plan displays the plan's monthly price, and a list of the features included in the plan.

## Technologies Used

- [Bootstrap](https://getbootstrap.com/)
    - Bootstrap was used for the site layout and for the hamburger menu dropdown that's displayed in mobile view. 

- [JQuery](https://jquery.com)
    - The hamburger menu dropdown that's displayed in mobile view requires **JQuery**
    
- [Font Awesome](https://fontawesome.com/)
    - Font Awesome icons were used for the homepage icon,  the contact icons, and the dumbell and medal icons that are displayed in the plans.


## Testing

The following tests were manually executed and passed in Chrome, Microsoft Edge,Firefox and on a Samsung mobile device.  The chrome dev tools device emulator
was used for responsive breakpoint testing.

**Header section**
1. Open the Home page in desktop view and verify that the Home icon is displayed at the top left of the screen.
2. Verify that the Classes and Plans links are dislplayed at the top right of the screen.
3. Click the Classes and Plans links and verify that you're taken to the correct page.
4. Click the Home icon and verify you are returned to the home page.
5. Reduce the window size to 767px and verify that a hamburger menu replaces the links.
6. Click on the hamburger menu and verify that a dropdown is displayed with the Classes and Plans links.
7. Click on the each link a verify that you're directed to the correct screen.
8. Increase the screen size to greated than 767px and verify that the hamburger menu is no longer displayed and the Classes and Plans links are again displayed in the header.

**Home page intro section**
1. Click the View Plans button and verify that you're directed to the Plans screen.
2. Return to home screen and gradually reduce the window size to 991px or less. Verify that intro images are now displayed below the yellow text section.
3. Continue to reduce the screensize down to mobile view, and verify that there are no rendering issues.

**Classes screen**
1. Open the Classes screen and hover the cursor over any of the class images. Verify that timetable overlay is displayed.
2. Move the cursor away from the image and verify that the timetable overlay is no longer displayed.
3. Reduce the screensize to 991px and verify that the class images are now displayed in 2 columns.
4. Reduce the screensize to 767px and verify that the class images are now displayed in 1 column.

**Plans screen**
1. Open the Plans screen and verify that there are 3 plans displayed, each with its own column.
2. Reduce the screensize to 991px and verify that the plans are displayed over 2 rows. The gold plan should be centered in the first row. The silver and bronze plans
3. should be in the row below on either side of the gold plans, making an pyramid formation.
4. Reduce the screensize to 767px and verify that the plans are now all displayed in 1 column.

**Footer section**
1. Scroll down to the footer section and click on each of the social media links. Verify that correct site is open in a new browser tab.
2. Reduce the screensize to 991px and verify that the Connect section is moved below the Contact section.
3. Reduce the screensize to 767px and verify that all the Connect and Contact section are now displayed below the Opening hours section in one column.

## Deployment

This is a static website and is hosted on github pages. There are no backend services for the site.

The version deployed on github pages is the final version.



## Credits

### Content
- The intro section text on the homepage was partially taken from the homepage of fitnessfactorymaine.com

### Media
- All photos used in this site were obtained from https://unsplash.com/

### Acknowledgements

- The classes timetable overlay that is displayed on hover was inpsired by the classes timetable on fitnessfactorymaine.com. However, no code was copied, and the implementation is not the same.
- The general layout of the site was inspired by the gym websites fitnessfactorymaine.com and burnpilates.com.
- The Hamburger menu's transparent dropdown was inspired by the dropdown at https://code-institute-solutions.github.io/StudentExampleProjectGradeFive/index.html