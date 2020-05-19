# Marketing Web-page

The site was created to introduce and create expectations for a new company service.

The page doesn't include any concrete detail about the service, like pricing or technical specifications, but it gives
a general overview of what to expect and it hints to future things.

A contact form is provided to allow anyone interested request more information.
 
## UX


Use this section to provide insight into your UX process, focusing on who this website is for, what it is that they want to achieve and how your project is the best way to help them achieve these things.

In particular, as part of this section we recommend that you provide a list of User Stories, with the following general structure:
- As a user type, I want to perform an action, so that I can achieve a goal.

This section is also where you would share links to any wireframes, mockups, diagrams etc. that you created as part of the design process. These files should themselves either be included as a pdf file in the project itself (in an separate directory), or just hosted elsewhere online and can be in any format that is viewable inside the browser.

## Features

### Existing Features
- Responsive navigation bar - Allow the user to jump directly between sections.
- Contact form - Allow the users interested to request more information filling the form.
- Links to social networks - Allow the users to visit the social sites for the company.

In addition, you may also use this section to discuss plans for additional features to be implemented in the future:

### Features Left to Implement
- Another feature idea

## Technologies Used

- [Hypertext Markup Language (HTML)]
	- **HTML** is used to create the structure of the web-page and to add content.
	
- [Cascading Style Sheets (CSS)]
	- **CSS** is used to provide styles for the web-page.

- [Bootstrap](https://getbootstrap.com/)
    - The project uses **Bootstrap** to implement a responsive navigation bar, help with the layout of some elements and provide classes for styles.

- [Fontawesome]	(https://fontawesome.com/)
	- **Fontawesome** is used to provide font icons in the shape of social networks.
	
- [Google fonts] (https://fonts.google.com/)
	- The page use several fonts for text from **Google Font** service.


## Testing

1. The HTML and CSS code were tested with [CSS Validation Service](https://jigsaw.w3.org/css-validator/) and [Markup Validation Service](https://validator.w3.org/).
   The test found two small errors that were fixed, following tests mark the code as okay.
  
2. During development the site has been checked in a regular basis with the developer tools of the browser to ensure that it worked as intended in desktop and mobile enviroments.

3. The site has been tested with the browsers Brave and Firefox.

4. Navigation bar:
	1. Desktop version, try to click in any option to verify that the page scrolls to the right section.
	2. Mobile version, verify that the navigation bar options gets collapsed when the size of the screen is reduced.
	3. Mobile version, verify that the menu options had the same behavior that in desktop mode.
	4. Mobile version, verify that the menu open/close correctly when is push.

5. Contact form:
	1. Test: Not filling one or more of the required shows an error message asking the user to fill the field.
	2. Test: Not ticking the acknowledge for the privacy policy shows an error message.
	3. Test: Trying to submit with an incorrect email address shows an error message asking the user to fill the field with the right content.
	
6. Social networks links:
	1. Click in every of the three links to test the social networks open in a new browser tab.



### Bugs

- The links to the **privacy policy** and the **terms of use** point to nothing.
- The form returns and error "Error code: 501", since "action" is not defined.


## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits

### Content

- The Privacy Policy text is a modification over the privacy policy from [trumpipsum.net own policy](https://trumpipsum.net/privacy-policy/)
- The Term of Use text is from an archived version of [placeholder.com](https://web.archive.org/web/20200216231943/https://placeholder.com/about/privacy/#content)
- All the rest of text is original, and no real information has been used. If that's the case it just pure coincidence.

### Media

- Image for the overview section:
	- [Panumas Nikhomkhai](https://www.pexels.com/photo/bandwidth-close-up-computer-connection-1148820/)
	
- Image for the message section:
	- [Fauxels](https://www.pexels.com/photo/photo-of-people-sitting-near-wooden-table-3183188/)
	
- Images for the feature section:
	- [Carl Heyerdahl](https://unsplash.com/photos/KE0nC8-58MQ)
	- [Sander Weeteling](https://unsplash.com/photos/4I41IQtmSs0)
	- [Luis Villasmil](https://unsplash.com/photos/4V8uMZx8FYA)

### Acknowledgements

- I received inspiration for this project from X