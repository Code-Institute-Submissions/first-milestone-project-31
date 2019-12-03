# First milestone project - "Uplift Training Center gym website"

One or two paragraphs providing an overview of your project.

Essentially, this part is your sales pitch.
 
## UX
 
Use this section to provide insight into your UX process, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

In particular, as part of this section we recommend that you provide a list of User Stories, with the following general structure:
- As a user type, I want to perform an action, so that I can achieve a goal.

This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included as a pdf file in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.

## Features

In this section, you should go over the different parts of your project, and describe each in a sentence or so.
 
### Existing Features
- Home icon - This is a fontawesome icon displayed on the left of the header that links to the homepage when clicked
- Header links in desktop view - The Classes and Plans links  are displayed in the header and link to their respective pages.
- Hamburger menu in mobile view - A hamburger menu is displayed in mobile view.  When clicked a dropdown menu displays the Classes and Plans links. The 
- dropdown is a bootstrap component, but several styling and positional edits were made to fit the project look and feel.
- Intro section - THe intro section contains a short intro message about the gym, two images,  and a button that links to the plans screen. 
- The Footer - the footer section contains info on the gyms opening hours, contact info and functioning social media links.
- Classes images and the timetable overlay - for each gym class there is an image that displays the class timetable when hovered.
- Plans - there are 3 membership plans.  Gold, silver and bronze. Each plan displays the plan's monthly price, and a list of the features included in the plan.

For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement
- Another feature idea

## Technologies Used

For each, provide its name, a link to its official site and a short sentence of why it was used.

- [Bootstrap](https://getbootstrap.com/)
    - Bootstrap was used for the site layout and for the hamburger menu dropdown that's displayed in mobile view. 

- [JQuery](https://jquery.com)
    - The hamburger menu dropdown that's displayed in mobile view requires **JQuery**
    
- [Font Awesome](https://fontawesome.com/)
    - Font Awesome icons were used for the homepage icon,  the contact icons, and the dumbell and medal icons that are displayed in the plans.


## Testing

In this section, you need to convince the assessor that you have conducted enough testing to legitimately believe that the site works well. Essentially, in this part you will want to go over all of your user stories from the UX section and ensure that they all work as intended, with the project providing an easy and straightforward way for the users to achieve their goals.

Whenever it is feasible, prefer to automate your tests, and if you've done so, provide a brief explanation of your approach, link to the test file(s) and explain how to run them.

For any scenarios that have not been automated, test the user stories manually and provide as much detail as is relevant. A particularly useful form for describing your testing process is via scenarios, such as:

1. Contact form:
    1. Go to the "Contact Us" page
    2. Try to submit the empty form and verify that an error message about the required fields appears
    3. Try to submit the form with an invalid email address and verify that a relevant error message appears
    4. Try to submit the form with all inputs valid and verify that a success message appears.

In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

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
- The general look and feel of the site was inspired by gym websites fitnessfactorymaine.com and burnpilates.com.