# Night Vale Community Radio Website

!-- insert multi-device screenshot here --! put in wireframes too

Thank you for taking the time to come visit my project! I welcome any comments, questions, and suggestions, and can be reached with my GitHub contact details.

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

##### As a user I expect to be able to check the weather before leaving my house.
##### As a user I expect to know what the upcoming events in my community are.
##### As a user I expect to be able to be able to express interest in interning at the radio station.
##### As a user I expect to be able to add my event to the community calendar.

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

The color palette for this site is inspired by the color palette for the Welcome To Night Vale podcast logo and 
<a href='http://www.welcometonightvale.com/'>official website</a>, which relies heavily on different shades of purple. 
I used <a href='https://coolors.co/10002b-240046-3c096c-5a189a-7b2cbf-9d4edd-c77dff-e0aaff'>this palette</a> from 
<a href='https://coolors.co/'>Coolors</a>.

##### Fonts:

The two fonts I used for this site are <a href='https://fonts.google.com/specimen/Oswald?query=oswald'>Oswald</a> 
and <a href='https://fonts.google.com/specimen/Raleway?query=raleway'>Raleway</a>. I chose these two because they 
work smoothly together, and have a simplistic, sans-serif style similar to that of the podcast's official site. 
In addition to this, I chose the sans-serif style because it allowed the information to take the forefront rather
than the focus being on the text itself.

##### Icons: 

I chose to use only two kinds of icons: footer icons that serve as links to Night Vale Community Radio's other social 
media pages, and a hamburger icon that serves as a drop-down navbar menu on mobile devices and tablets. All icons used 
are widely recognizable for their use.

##### Colors:

As mentioned just under the Design Choices header, the 
<a href='https://coolors.co/10002b-240046-3c096c-5a189a-7b2cbf-9d4edd-c77dff-e0aaff'>color palette</a> I used was from 
<a href='coolors.co'>Coolors.co</a>. I attributed different colors to different sections in a gradient pattern, and named 
them after the sections or functions they were predominantely used for in the site.

![NVCR Color Palette](./wireframes/paletteNVCR.png "NVCR Color Palette")

* .contact-color: #240046 **“Russian Violet”** I decided to use this color as the color for the contact section, 
the navbar and the footer largely because it would make the navbar text really pop out, and because the I planned to have the 
contact section be at the bottom of the site. It being at the bottom of the site played out well for the plan to have the main 
section colors work in a gradient.
* .apply-color: #3c096c **“Persian Indigo”** I decided to use this color for the apply section because I planned it 
as the section above the contact section, and that was the next color for the gradient.
* .weather-color: #7b2cbf **“French Violet”** I decided to use this color for the weather section because I planned 
it as the section above the about section, and that was the next color for the gradient.
* .calendar-color: #9d4edd **"Dark Orchid"** I decided to use this color for the calendar section because I planned 
it as the section above the weather section, and that was the next color for the gradient.
* .btn-color and .link-color: #E0AAFF **"Mauve"** This color was perfect for the site's buttons, links and text as 
it was light enough to be clearly legible over even the lightest section color, and it really pops off of the dark navbar, footer, 
and contact section.
* .link-color:hover: #FFFFF **"White"** When link text is hovered over, it goes white. This color was chosen because it is easy to read,
and still looks clean.

##### Styling: 

<!-- Thanks to SASS/SCSS I was easily able to set variables in my stylesheets that ask as the house 
style - this means that the styles can be used in multiple places without having to repeat code. Using SASS also allowed me to better 
structure my stylesheets, splitting them off into partial files for example, splitting the css into ‘component’ files, i.e map, buttons, 
headers (see assets/scss for all partial files). Using BEM allowed me to easily nest my SASS code and also making my HTML code much more 
readable. -->


##### Background:

The <a href='../images/hero.jpg'>hero image</a> was selected because it was available for use without broaching usage rights, 
and depicted a scene from a desert town like Night Vale. I went for an old-school ghost town image because an aspect of the 
show is that nobody really knows when Night Vale exists, and it is often hinted that the citizens there are very, very old.

### Wireframes 

I used <a href="https://balsamiq.com/">Balsamiq</a> to build this project’s wireframe. You can view them 
<a href="wireframes/wireframeNCVR.pdf">here.</a>

## Features

* Site-wide consistent navbar and footer
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
* <a href="https://fontawesome.com/icons?d=gallery">Font-Awesome</a>
* <a href="https://git-scm.com/">Git</a>
* <a href="https://fonts.google.com/">Google Fonts</a>
* <a href="https://jquery.com/">jQuery</a>
* <a href='https://www.javascript.com/'>JS</a></a>

## Testing:

Since this was my first website, I wanted to make sure that I was thurough in my testing. Thankfully, I was able
to accomplish this with the help of the Slack community and my dedicated mentor. 

##### Test Planning: 

Before creating this site, I made wireframes that allowed me to plan out my testing methods. Essentially, I decided
that I would test as I went along, clearing interactive elements in particular before moving on. Of course, things
don't always go to plan and there were a few times where I hopped around in order to not burn myself out one single points.

##### Testing Stories:

* Originally, I had wanted to use a carousel for the weather videos. After implementing and testing this, I realized that
the only way I would be able to successfuly implement the carousel (so that videos would automatically stop when 
the user scrolled past to the next one) would require JS. So, I removed the carousel.

* My original plan for the apply section was to have a file upload button. However, again it seemed like JS would be the best
way to get it to sit on the page the way I needed it to. Again, I removed it and replaced it with a form check.

* I quickly became well aquainted with "target=_blank" for the links I created! 

* Figuring out the jumbotron took a bit longer than I had anticipated. I was confused as to why, even though I had been using
rem units, the text size wasn't responding well. In the end, media queries were what saved the day!


### Overall:

**Responsiveness - **
* **Plan**: Following the principle of mobile-first design, I knew that this had to be entirely responsive. 
Given this, my level of education, and the guidelines of this project, this meant Bootstrap as a core framework, with 
regular use of dev tools to run tests throughout and a post-peer-review test before submission.
* **Implementation**: As I wrote my code, I frequently pulled from Bootstrap, modifying as needed. Modifications
were almost entirely regarding aesthetic/design, and testing was fairly simple thanks to dev tools and being told by my
fellow students about ctrl+shift+r.
* **Result**: After some modifications (i.e., media query for .jumbotron-text), the site is fully responsive,
with no overflow or illegible information.
* **Verdict**: The site is responsive! The test passes.

**Design -**
* **Plan**: I wanted the site to be inline with the podcast's official color scheme, which lead to the use of
purples. Using the darkest shade in the header and footer allowed for a sense of bordering, while the lightest shade popped
well against all of the other colors, making it the perfect choice for text and links.
* **Implementation**: Creating classes for the colors allowed for very easy, understandable and smooth design. 
* **Result**: The color palette I chose to use works well.
* **Verdict**: Because the color palette works well, this test passes!

### Features:

**Navbar and Footer -**
* **Plan**: In the planning phase, I decided that I wanted the navbar to be fixed and for the links to shrink 
into a dropdown menu for mobile and tablet screens. I wanted the footer to only be visible when the user scrolls to the 
bottom of the page, and for it to have links to other Night Vale sites (Instagram, Tripadvisor, etc.)
* **Implementation** : I used Bootstrap to build these.
* **Result**: The navbar and footer are both positioned where I want them and are fully responsive.
* **Verdict**: Regarding these results, this test passes.

**Community Calendar -**
* **Plan**: I wanted this calendar to look something like a table, but was advised by Simen to not use an
actual Bootstrap table, as those are not very workable re: responsivness. I planned to have the different rows be different
colors in the reverse of the section color gradient rather than having borders, as I found this more aesthetically pleasing.
* **Implementation** : I used Bootstrap to build these rows.
* **Result**: The community calendar is responsive, clean and easily readable.
* **Verdict**: Regarding these results, this test passes.

**Application Form -**
* **Plan**: Originally, I wrote this part to include a file upload form. However, toying around with it I 
discovered that the only way to make it fit in the page the way that I wanted was to implement JS, which I am not
educated in yet. So, I reworked it a bit to have the two links, three input fields, two form-checks, and a submit button.
* **Implementation** : I used Bootstrap to implement the various form elements.
* **Result**: While the end result isn't what I had envisioned, it is clean, responsive, and understandable.
* **Verdict**: Regarding these results, this test passes.

**Communication Form -**
* **Plan**: What I planned for this section is exactly how it turned out! First name, last name, email, and
text input boxes with a submit button.
* **Implementation** : I used Bootstrap to implement the necessary form elements.
* **Result**: The end result is exactly what I had envisioned! It is clean, responsive, and understandable.
* **Verdict**: Regarding these results, this test passes.

**Add Event Button -**
* **Plan**: While in the planning phase, I wanted a button that would lead the user from the calendar down to 
the contact section, because I figured that that would be a primary user need.
* **Implementation** : I used Bootstrap to add in this button.
* **Result**: The end result is responsive and clean.
* **Verdict**: Regarding these results, this test passes.

**Weather Videos -**
* **Plan**: While in the planning phase, I wanted this to be a carousel of videos. However, I learned that
in order to command the videos to stop playing once the user scrolled by, I would need to use JS, which is currently out of 
my paygrade. So, I reworked the layout so all videos were on display. In mobile, they line up down the screen. While I wanted
the lines of text to reorder between mobile and tablet+, I was informed by a tutor that this can only be completed with JS, 
so I decided to leave it be.
* **Implementation** : I used Bootstrap to make this new layout responsive and clean.
* **Result**: While the end result isn't what I had envisioned, it is clean, responsive, and understandable.
* **Verdict**: Regarding these results, this test passes.

## Bugs:
#### Bugs During Development:

Over the process of creating this site, I ran into a few bugs, but thankfully between Simen, Slack, and the tutors, 
I sorted these out! Here are a few examples:

**Jumbotron text overflow:**
* Bug: The text over the jumbotron wasn't behaving like I wanted it to. It wasn't responsive enough to small screens.
* Fix: Creating media queries!
* Verdict: Simen reminded me of this - I didn't end up using it in the spot he originally suggested because it felt like 
I had less control than I wanted in that area, but it was perfect for this bug.

**Footer icon alignment:** 
* Bug: I was struggling to align the icons in the footer in a way that was aesthetically pleasing.
* Fix: Using flex rules in the css #footer id.
* Verdict: Simen had me take some time playing with <a href='boxfroggy.com'>Flexbox Froggy</a>, which is what gave me 
the tools to fix this!

**Navbar hamburger size:**
* Bug: In small screens, the navbar dropdown hamburger icon was inconveniently small.
* Fix: Overrode .container in style.css by applying font-size: 2vw;
* Verdict: I found this fix on the internet, thanks 
<a href='https://generatepress.com/forums/topic/change-hamburguer-menu-icon-size/'>David</a>!

#### Known Bugs: 

Sometimes, when in dev tools the site works smoothly. Other times, the screen doesn't automatically fit, and there is a horizontal scroll.

## Deployment:

Night Vale Community Radio was developed in GitPod, hosted by GitHub and using git.

The following steps were followed to deploy Night Vale Community Radio through GitHub Pages:

* Loaded **GitHub** in Chrome web browser.
* Signed into GitHub.
* Clicked on my **repositories**.
* Navigated to **'mcalistm/NightValeCommunityRadio'**.
* Selected **'settings'**.
* Navigated to the **GitHub Pages** area of the page. 
* Selected **'Master Branch'** from the **'Source'** dropdown menu.
* Confirmed my selection.
* Night Vale Community Radio is now live on GitHub Pages.

#### Running Night Vale Community Radio Locally: 

Cloning Night Vale Community Radio from GitHub:
* Navigate your screen to '/mcalistm/NightValeCommunityRadio'.
* Click on the green 'Copy' button.
* Copy the provided URL.
* Start up the terminal of your choice with the IDE of your choice.
* Navigate to the file location of your choice.
* To clone, copy this code and input it into your terminal: 

```
https://github.com/mcalistm/NightValeCommunityRadio.git
```

## Closing Notes:

This project has encouraged me to think about how I think in order to provide information in a clean, 
concise and friendly way to users. It has also helped me get a better grasp on bootstrap, 
and has increased my confidence in my abilities as a very junior web developer. I very much look 
forward to continuting to build my skills! There were a few times where problems I came across 
could easily be solved by javascript, so I am particularly excited to learn this. Creating this website 
has been incredibly fun and rewarding, while also being one of the more challenging 
undertakings I've committed to in quite a while. I'm so, so glad I did it.

## Credits: 
* <a href="http://www.welcometonightvale.com">Welcome to Night Vale</a>
* <a href="https://github.com/Eventyret">Simen Daehlin</a>
* Code Institute Slack Community
* Code Institute Tutors
* <a href='https://github.com/Geomint'>George Pyott</a>'s 
<a href='https://github.com/Geomint/holiday-destinations/blob/master/README.md'>Holiday Destinations README.md file</a>, 
shown to me by Simen.
