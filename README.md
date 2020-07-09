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
    *  Features that will be implemented in the future
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
##### User 3: As a user I expect to be able to be able to apply to intern at the radio station.
##### User 5: As a user I expect to be able to add my event to the community calendar.
##### User 6: As a user I expect to be able to learn about other people in my community.

#### Site Owner Goals:
* Provide information to the community about upcoming events.
* Gather applications for internships.
* Accurately display the weather.

## User Requirements and Expectations:
##### Requirements:
* Navigate the site using the navbar.
* Be provided with community information.
* Be able to apply for internships.
* Be able to access the weather.
* Be able to contact the radio station.
* Website is displayed appealingly.

##### Expectations:
* Can tap/click on navbar links to direct around the site
* Community calendar is up to date
* Weather forecast is up to date
* Contact and application forms are functional
* Navbar condenses to drop down menu in mobile/table view
* Website is appealing and accurate

## Design Choices: 🎨

The theme of this project is holidays and vacations, therefore my design choices are heavily influenced by positive colours and motifs. Using the resources in <a href='https://www.crazyegg.com/blog/colors-proven-to-boost-sales/'>this</a> blog I was able to pick out a colour scheme that has been proven to boost sales/interaction with a web page.

##### Fonts: 
I chose to use the font <a href="https://fonts.google.com/?query=lato&selection.family=Lato">LATO</a> as it showcases a very simplistic style which compliments the minimalist nature of the overall site design. The focus of the content is to provide an informative experience for the customer, which heavily influenced my decision to choose a font that isn't too ambiguous.

##### Icons: 
The icons used are self explanatory so that the user does not need to struggle to interpret what the icon will actually do. I use the icon ‘bars’ from font-awesome icons, to display the classic ‘burger-button’ on tablet and mobile devices, this is well known in the industry as being a point for navigation. I had to make sure that the icon was big enough on smaller devices to ensure easy access.

##### Colours:
Using learned knowledge from prior research, bright and vibrant colours have a higher influence in terms of positivity and therefore more potential sales/leads and interactions: Using <a href='[Generate - Coolors.co](https://coolors.co/d9f0ff-5bc0eb-e55934-fa7921-fde74c)'>This</a> i was able to find a colour scheme that suited the afor mentioned points.

* Primary: #4ECDC4 <strong>“Moderate cyan”</strong> I chose this as the primary colour as the colour cyan is great to influence thoughts of trust, honesty and intelligence.
* Secondary: #264c5f <strong>“Very dark blue”</strong> I chose this as the secondary colour as this colour provides an eye catching variation to the primary blue, this is used in most places as a background colour.
* Tertiary: #1A535C <strong>“Arapawa”</strong> This tertiary colour will be used as an accent highlight on certain elements, this colour promotes happiness among the average person and therefore (hopefully) influence more sales/leads.
* Navigation Colour: #FF6B6B <strong>“Bittersweet”</strong> This bursting colour provides excellent contrast for the dark blues, with the added benefit of being a blend of orange/red which influences a hightened emotional response.
* Default Body Colour: #F7fff7 <strong>"Mint White"</strong> This off white colour will provide a discreet contrast from the blue theme i've got within this project, a subtle yet effective default body colour.
* Default Body Panel Colour: #2a3439 <strong>"Darkest Blue"</strong> This dark shade of blue will be used to provide backgrounds to specific panels of interest especially on the hero section of the website.

##### Styling: 

Thanks to SASS/SCSS I was easily able to set variables in my stylesheets that ask as the house style - this means that the styles can be used in multiple places without having to repeat code. Using SASS also allowed me to better structure my stylesheets, splitting them off into partial files for example, splitting the css into ‘component’ files, i.e map, buttons, headers (see assets/scss for all partial files). Using BEM allowed me to easily nest my SASS code and also making my HTML code much more readable.

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

BEM Stands for block element modifier, and is a way of writing CSS/SASS code in order to organise the code into a much more readable format. Head to the credits to read more about BEM style.


##### Background:
The background images I chose to use on the banner are sourced from royalty free websites, they showcase different types of ‘lifestyle’ shots on different holiday destinations. Arguably large images like the ones mentioned are great for encouraging sales and leads. I manually resize the images using a tool called Gimp, having accurately sized images reduces the load time of the website.

### Wireframes 

I used <a href="https://balsamiq.com/">Balsamiq</a> to build this project’s wireframe. You can view them <a href="wireframes/wireframeNCVR.pdf">here.</a>

## Features

* Site-wide consistent header and footer
* Community calendar
* Internship application form
* Communication form
* Link to instruct the user on how to add their event to the community calendar
* Weather video

## Technologies Used: 👨‍💻

### Languages:


### Tools & Libraries:


