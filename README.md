# Project-3

Treehouse Techdegree - An Online Registration Form

https://darshenpatel.github.io/Project-3-Online-Registration-Form/

Project Requirements
====================

### Build the layout using a mobile first design:
  * Make sure the HTML file includes the viewport meta tag in the head of the document, see Configuring the Viewport to understand why and how to add this tag.
  * Look at the provided mockup (mobile-form.png) and add the same content to your index.html file.
  * **NOTE:**
    - It's okay if your checkboxes and radio buttons don't match the look of those in the mockups. It's perfectly fine to use the standard default radio buttons and checkboxes.


### Create the form structure:
  * Only use one <form> tag. The <form> tag should contain all the form elements. Add a fieldset and legend for each of the following sections:
    - "Contact Information" section of the page
    - The "Newsletter" section of the page
  * **NOTE:**
    - You don't need to make a functioning form -- that is, it doesn't have to do anything when the form is submitted.
    To do that, you'd need to add some server-side programming to actually process the user's input.


### Make sure you include the following form field types:
  - [x] text input
  - [x] email input
  - [x] telephone input
  - [x] select menu
  - [x] checkboxes
  - [x] radio buttons
  - [x] textarea
  - [x] submit button


### Form fields should include the following attributes:
  - [x] input: should include id, type and name attributes.
  - [x] select and textarea: should include id and name attributes.
  * **NOTE:**
    - *Checkboxes* should have identical name attributes but unique value attributes
    - *Radio Buttons* should have identical name attributes but unique value attributes


### Add labels to each form element using the HTML <label> tag. The text inside the labels should match the names of the form fields in the mockups
  * Make sure you properly pair each <label> element with its corresponding form control via the for attribute.
  * See the link above for an example. And don't forget about the textarea element. That needs a functioning label too.
  * **NOTE:**
    - Remember that to associate a label with a form input element, the label’s “for” attribute should match the input’s unique id.


### Use the input field's placeholder attribute to add the text "required" to:
  - [x] the Full Name field
  - [x] the Email address field


### Once you have everything in place for the mobile layout, use a media query to add a breakpoint to adjust the layout for wider tablet and desktop screens.
  * Match the design as it should look on a tablet or desktop that is 768px wide using the desktop-form.png mockup.
  * Use a mobile-first approach by writing your media queries using the min-width property in your CSS.


### Once all your breakpoints are in place, double check your layout matches both the mockups.
  * Check that the label text position matches both mockups:
    - *Mobile*: Text should be above the form field.
    - *Desktop*: Text should be to the left side of the form field.


### Add :focus states to the form for when a user clicks or tabs into a text field.


### Make sure to check your code is valid by running it through an HTML and CSS validator:
  * Links to the validators can be found in the Project Resources. This will help you spot any errors that might be in your code.
  * *There are a few exceptions that you don’t need to fix:*
    - Don’t worry about any warnings, we just need you to check any errors that might be there.
    - If CSS validator flags use of calc, vendor prefixes or pseudo-elements/pseudo-classes these errors should be ignored.
    - If HTML validator flags use of pipe (‘|’) in Google font links/URLs this error can also be ignored.


### Extra Credit:
  * Additional placeholder text for other text fields.
  * Use the required attribute to add HTML5 validation to make sure that required fields are filled out and input is formatted correctly.
  * Add at least the following additional styling enhancements to the form, feel free to add extra styling but leave the basic layout the same as the mockup:
    - Change the background color for at least ONE of the main sections of the site.
    - Uses CSS transitions for focus states.
  * Use CSS transition effects for highlighting the look of the form fields.
    - For example, make a background color fade into view when the user clicks on a text field, and fade out when the user clicks or tabs out of the field.
