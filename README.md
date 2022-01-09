
# The Meditation Space

The Meditation Space is a simple one-page site for a fictitious independent teacher of transcendental meditation (TM) who currently offers online training courses. They would like to appeal to individuals and groups who are intrested in meditation and in learning the TM technique.

Users will be able learn more about TM, how easy it is to practice and some of the demonstrated benefits. They can also see how the course is structured, the time commitment and cost, and are able to contact the teacher directly, either by phone or email, or can provide their details to find out more about upcoming course dates. 

## Design

The colour scheme was chosen following recommendations in an article on the site [99 Designs](https://99designs.co.uk/blog/tips/website-color-schemes/) in order to create a calm but modern feel to the site but also to maximise accessibility. The Oswald and Roboto sans serif fonts were also chosen to make the site easy to read.

## Features

### *Responsive design*

Users may access the site on a range of device sizes, from mobile to desktop, and the design reflects this. Media queries ensure that the site remains easy to read and use on mobile. 

### *Navigation* 

![nav bar screenshot](/DOCS/Logo-and-nav-bar-screenshot.png)

The navigation bar is fully responsive and includes links to each of the main sections of the page (About Us, Learn, Sign Up and Contact). This allows users to navigate quickly to their area of interest. Whilst a first time user might wish to scroll down the whole page, a returning user might wish to just visit one particular section, eg to remind themselves of the course structure, to sign up for more information or to find the teacher's contact details.

### *Image*

![hero image screenshot](/DOCS/Hero-image-and-text-screenshot.png)

The image conveys the theme of the site and also indicates that it is possible to meditate anywhere, which is referred to in the About Us section. The tag line references the fact that a typical TM session is 20 minutes long and also that site visitors are most likely to be looking for a way to find a sense of calm in their lives but without needing a huge commitment of time.

### *About Us*

![about us screenshot](/DOCS/About-us-screenshot.png)

This section provides the user with some information about TM, what it is and how it is practised, together with the benefits of regular practice.

### *Learn*

![learn screenshot](/DOCS/Learn-section-screenshot.png)

Users can see how they can learn online, how the course is structured and the time commitment, as well as the cost.

### *Sign Up*

![sign up screenshot](/DOCS/Sign-up-form-screenshot.png)

Users can start their learning journey by signing up for further information on the course and dates offered. They also have the option of leaving a short message if they have a specific query.

### *Contact*

![contact screenshot](/DOCS/Contact-section-screenshot.png)

This section provides the user with the teacher's phone number and email and allows for direct contact. 

### *Footer*

![footer screenshot](/DOCS/social-media-icons-screenshot.png)

The social media links open in a new tab to allow easier navigation for the user. Having these available encourages users to keep connected to the teacher.

### *Features to implement*

An actual teacher of TM could add:

- More course information, to include in-person training
- Dates of courses
- Booking and payments system
- A blog
- Testimonials for social proof

## Testing

*Manual testing of the site:* 

- All navigation elements link to the appropriate sections of the site.
- Sign up form: the form cannot be submitted if the name and email fields are empty or the text in the email input box is not an email address. Submission is to the Code Institute form dump.  
- The social media icons in the footer open up in new tabs.
- The site opens and functions as expected in Chrome and Firefox browsers.

*Responsiveness:*

- Chrome and Firefox dev tools were used to check the site responsiveness at various browser sizes.
- The [amiresponsive](http://ami.responsivedesign.is/) website was used to create a multi-device mock-up of the site as an additional check on how the site displays across various media. 

![amiresponsive screenshot](/DOCS/amiresponsive-screenshot.png)

In addition, the Lighthouse feature of Chrome dev tools was used to assess the site accessibility and received a score of 100.

![Lighthouse screenshot](/DOCS/Lighthouse-screenshot.png)

*Validator Testing*

- HTML

No errors were returned when passing through the official [W3C validator](https://validator.w3.org/)

![W3 validator screenshot](/DOCS/W3-validator-screenshot.png)
- CSS

No errors wer returned when passing through the official [(Jigsaw) validator](https://jigsaw.w3.org/css-validator/)

![Jigsaw screenshot](Jigsaw-validator-screenshot.png)

## Deployment

The site was deployed to GitHub pages. The steps followed are:

- In the GitHub repository, navigate to the Settings tab.
- From the source section drop-down menu, select the Master branch.
- Once this has been selected, the page will be automatically be refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found here: <https://gbell94.github.io/Meditation-Space>

## Credits

### *Content*

- Information about TM was taken from the following sites: [TM UK](https://uk.tm.org/), [The Meditation Trust](https://www.meditationtrust.com/) and [Twenty Minutes Meditation](https://www.twentyminutesmeditation.co.uk/)
- Information on using flexbox was taken from a [W3 schools tutorial](https://www.w3schools.com/css/css3_flexbox.asp)

### *Media*

- The image is by Mediensteurmer on [Unsplash](https://unsplash.com/)
- The social media icons are from [Font Awesome v5](https://fontawesome.com/)
