# Night Vale Community Radio Website

!-- insert multi-device screenshot here --!

Thank you for taking the time to come visit my project! I welcome any comments, questions, and suggestions, and can be reached with my GitHub contact details. Pleasant coding!

## Contents:

* UX 
    * Project Goals
    * Target Audience Goals
    * Site Owner Goals
    * User Requirements and Expectations
    * Design Choices 
        * Fonts
        * Icons
        * Colours
        * Styling
        * Images
        * Backgrounds
* Wireframes 
* Features 
    * Features that have been developed
    * Features that will be implemented in the future
* Technologies Used
* Testing 
* Bugs 
* Deployment 
* Credits 

Night Vale Community Radio is the radio station for the fictional desert town of Night Vale, created by Joseph Fink and Jeffrey Cranor in their podcast _Welcome to Night Vale_. The station is staffed by host Cecil Baldwin and a variety of interns, all of whom meet strange ends. While there are parts of Night Vale that seem mundane, it quickly becomes apparent that the town is comedically strange and dark - the daily weather is a song, the dog park is to be avoided at all costs, and the Sheriff's Secret Police will leave a carnation on your front porch when it is safe to come outside. 

The purpose of this project is to provide the citizens of Night Vale with a website for their beloved NVCR. It will provide them with the monthly community calendar, the daily weather, the citizen of the month, and an opportunity to apply to intern at the radio station (applications are accepted on a rolling basis).

## UX (User Experience)
### Project Goals
The goal of this project is to help users access community information and communicate with their radio station. It is aimed at citizens of Night Vale. The finished site should be clean and intuitive enough to be easily accessible, while also being appealing to the eye.

#### User Goals:
* A hub for community information that is easily accessible.
* Easy communication with the radio station through a contact form.
* Access to the day’s weather.
* Ability to apply for an internship at the radio station.
* Responsiveness to different devices.

#### User Stories:

##### User 1: As a user I expect to be able to check the weather before leaving my house.
##### User 2: As a user I expect to know what the upcoming events in my community are.
##### User 3: As a user I expect to be able to be able to express interest in interning at the radio station.
##### User 4: As a user I expect to be able to add my event to the community calendar.

#### Site Owner Goals:
* Provide information to the community about upcoming events.
* Gather application interest for internships.
* Open pathways for communications from community.
* Accurately display the weather, updated on a weekly basis.

## User Requirements and Expectations:
##### Requirements:
* Navigate the site using the navbar.
* Be provided with community information.
* Be able to apply for internships.
* Be able to access the weather.
* Be able to contact the radio station.
* Website is displayed appealingly.

##### Expectations:
* Can tap/click on navbar links to direct around the site.
* Community calendar is up to date.
* Weather forecast is up to date.
* Contact and application forms are functional.
* Navbar condenses to drop down menu in mobile/tablet view.
* Website is appealing and provides accurate information.

## Design Choices: 🎨

The color palette for this site is inspired by the color palette for the Welcome To Night Vale podcast logo and <a href='http://www.welcometonightvale.com/'>official website</a>, which relies heavily on different shades of purple. I used <a href='https://coolors.co/10002b-240046-3c096c-5a189a-7b2cbf-9d4edd-c77dff-e0aaff'>this palette</a> from <a href='https://coolors.co/'>Coolors</a>.

##### Fonts:

The two fonts I used for this site are <a href='https://fonts.google.com/specimen/Oswald?query=oswald'>Oswald</a> and <a href='https://fonts.google.com/specimen/Raleway?query=raleway'>Raleway</a>. I chose these two because they work smoothly together, and have a simplistic, sans-serif style similar to that of the podcast's official site. 


##### Icons: 

I chose to use only two kinds of icons: footer icons that serve as links to Night Vale Community Radio's other social media pages, and a hamburger icon that serves as a drop-down navbar menu on mobile devices and tablets. All icons used are widely recognizable for their use.

##### Colours:

As mentioned just under the Design Choices header, the <a href='https://coolors.co/10002b-240046-3c096c-5a189a-7b2cbf-9d4edd-c77dff-e0aaff'>color palette</a> I used was from <a href='coolors.co'>Coolors.co</a>. I attributed different colors to different sections in a gradient pattern, and named them after the sections they were predominantely used for in the site.

* .contact-color: #240046 <strong>“Russian Violet”</strong> I decided to use this color as the color for the contact section, the navbar and the footer largely because it would make the navbar text really pop out, and because the I planned to have the contact section be at the bottom of the site. It being at the bottom of the site played out well for the plan to have the main section colors work in a gradient.
* .apply-color: #3c096c <strong>“Persian Indigo”</strong> I decided to use this color for the apply section because I planned it as the section above the contact section, and that was the next color for the gradient.
* .weather-color: #7b2cbf <strong>“French Violet”</strong> I decided to use this color for the weather section because I planned it as the section above the about section, and that was the next color for the gradient.
* .calendar-color: #9d4edd <strong>"Dark Orchid"</strong> I decided to use this color for the calendar section because I planned it as the section above the weather section, and that was the next color for the gradient.
* .btn-color and .link-color: #E0AAFF <strong>"Mauve"</strong> This color was perfect for the site's buttons, links and text as it was light enough to be clearly legible over even the lightest section color, and it really pops off of the dark navbar, footer, and contact section.

##### Styling: 

Ask about this! What should I put here? Thanks to SASS/SCSS I was easily able to set variables in my stylesheets that ask as the house style - this means that the styles can be used in multiple places without having to repeat code. Using SASS also allowed me to better structure my stylesheets, splitting them off into partial files for example, splitting the css into ‘component’ files, i.e map, buttons, headers (see assets/scss for all partial files). Using BEM allowed me to easily nest my SASS code and also making my HTML code much more readable.

##### Example Variables:

Colours: 

```scss
$primary-color: #4ECDC4;
$secondary-color: #264c5f;
$tertiary-color: #1A535C;
$navigation-color: #FF6B6B;
$default-body-color: #F7fff7;
$default-body-panel-color: #2a3439;
$white-color: #fff;
```

Default Styling:

```scss
$default-text-shadow: 1px 1px #000;
$default-transition: all 0.2s ease-in-out;
$default-box-shadow: 1px 1px 1px rgba(0,0,0,0.4);
```

##### BEM:

Ask abou this! BEM Stands for block element modifier, and is a way of writing CSS/SASS code in order to organise the code into a much more readable format. Head to the credits to read more about BEM style.


##### Background:

The <a href='../images/hero.jpg'>hero image</a> was selected because it was available for use without broaching usage rights, fit the panoramic image shape, and depicted a scene from a desert town like Night Vale. 

### Wireframes 

I used <a href="https://balsamiq.com/">Balsamiq</a> to build this project’s wireframe. You can view them <a href="wireframes/wireframeNCVR.pdf">here.</a>

## Features

* Site-wide consistent header and footer
* Community calendar
* Internship application form
* Communication form
* Link to instruct the user on how to add their event to the community calendar
* Weather videos for the week

## Technologies Used: 👨‍💻

### Languages:
* <a href="https://developer.mozilla.org/en-US/docs/Web/HTML">HTML</a>
* <a href="https://developer.mozilla.org/en-US/docs/Web/CSS">CSS</a>

### Tools & Libraries:
* <a href="https://getbootstrap.com/">Bootstrap</a>
* <a href="https://git-scm.com/">Git</a>
* <a href="https://fonts.google.com/">Google Fonts</a>

## Testing:
##### Test Planning: 
##### Testing Stories:
### Overall:
### Features:

## Bugs:
#### Bugs During Development:
#### Known Bugs: 


## Deployment:

Night Vale Community Radio was developed in GitPod, hosted by GitHub and using git.

The following steps were followed to deploy Night Vale Community Radio through GitHub Pages:

* Loaded <strong>GitHub</strong> in Chrome web browser.
* Signed into GitHub.
* Clicked on my <strong>repositories</strong>.
* Navigated to <strong>'mcalistm/NightValeCommunityRadio'</strong>.
* Selected <strong>'settings'</strong>.
* Navigated to the <strong>GitHub Pages</strong> area of the page. 
* Selected <strong>'Master Branch'</strong> from the <strong>'Source'</strong> dropdown menu.
* Confirmed my selection.
* Night Vale Community Radio is now live on GitHub Pages.

#### Running Night Vale Community Radio Locally: 

## Closing Notes:

## Credits: 
* <a href="http://www.welcometonightvale.com">Welcome to Night Vale</a>
* <a href="https://github.com/Eventyret">Simen Daehlin</a>
* Code Institute Slack Community
