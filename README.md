<img src="https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png" style="margin: 0;">

Welcome Maggie McAlister,

This is the Code Institute student template for Gitpod. We have preinstalled all of the tools you need to get started. You can safely delete this README.md file, or change it for your own project.

## Gitpod Reminders

To run a frontend (HTML, CSS, Javascript only) application in Gitpod, in the terminal, type:

`python3 -m http.server`

A blue button should appear to click: *Make Public*,

Another blue button should appear to click: *Open Browser*.

To run a backend Python file, type `python3 app.py`, if your Python file is named `app.py` of course.

A blue button should appear to click: *Make Public*,

Another blue button should appear to click: *Open Browser*.

In Gitpod you have superuser security privileges by default. Therefore you do not need to use the `sudo` (superuser do) command in the bash terminal in any of the backend lessons.

## Updates Since The Instructional Video

We continually tweak and adjust this template to help give you the best experience. Here are the updates since the original video was made:

**April 16 2020:** The template now automatically installs MySQL instead of relying on the Gitpod MySQL image. The message about a Python linter not being installed has been dealt with, and the set-up files are now hidden in the Gitpod file explorer.

**April 13 2020:** Added the _Prettier_ code beautifier extension instead of the code formatter built-in to Gitpod.

**February 2020:** The initialisation files now _do not_ auto-delete. They will remain in your project. You can safely ignore them. They just make sure that your workspace is configured correctly each time you open it. It will also prevent the Gitpod configuration popup from appearing.

**December 2019:** Added Eventyret's Bootstrap 4 extension. Type `!bscdn` in a HTML file to add the Bootstrap boilerplate. Check out the <a href="https://github.com/Eventyret/vscode-bcdn" target="_blank">README.md file at the official repo</a> for more options.

--------

Happy coding!

------------------------------------------

# Night Vale Community Radio Website

Night Vale Community Radio is the radio station for the fictional desert town of Night Vale,
created by Joseph Fink and Jeffrey Cranor in their podcast _Welcome to Night Vale_. The station
is staffed by host Cecil Baldwin and a variety of interns, all of whom meet strange ends. While
there are parts of Night Vale that seem mundane, it quickly becomes apparent that the town is
comedically strange and dark - the daily weather is a song, the dog park is to be avoided at all costs, 
and the Sheriff's Secret Police will leave a carnation on your front porch when it is safe to come outside. 

The purpose of this project is to provide the citizens of Night Vale with a website for their beloved NVCR.
It will provide them with the monthly community calendar, the daily weather, the citizen of the month, 
and an opportunity to apply to intern at the radio station (applications are accepted on a rolling basis).

## UX
 
### Navigation and Design 
The site is designed so that the header is maintained throughout for ease of recognition and navigation. 
Rather than one long scrolling page, it is set up in seperate pages because the user base is likely older, 
and they may find this structure easier to navigate. The footer is similarly consistent, providing links to 
the town's Instagram, podcast, TripAdvisor, Twitter, and RSS Feed for ease of connecting with the town
on various platforms.

### User Stories
* User 1: I am a citizen of Night Vale who wants to know what today's weather is before I go outside.
* User 2: I am a citizen of Desert Bluffs who wants to know the best weekend to visit Night Vale.
* User 3: I am a citizen of Night Vale who wants to know more about my community so I can feel more connected.
* User 4: I am a citizen of Night Vale who wants to know more about my radio station, and potentially
about working there.
* User 5: I am a citizen of Night Vale who wants to add my event to the community calendar.

### Wireframes 

The wireframes will be linked in here.

## Features

### Existing Features
* Responsive design: This site is created with mobile-first design in mind,
and is responsive.
* Headers and footers maintain consistency sitewide.
* Community calendar events can be accessed.
* Under the community calendar is a link that says "Add my event!" Clicking this link
will take the user to the contact page form, where they are prompted to request that
their event be added.
* Users can communicate with the radio station with the form in the contact us page.
* Users can apply to work at the radio station with the form in the apply page

### Pages
* Home Page
* Community Calendar
* Today's Weather
* Citizen of the month
* Apply to intern
* Contact Us

### Features Left to Implement
- Another feature idea

### Features and Pages Not Used
* I chose not to include the widely-used about us page, as there is 
only one major staffer at NVCR, and the majority of users will be well-acquainted
with him already. I was also concerned that it would make the site too cluttered.

## Technologies Used

### Languages and Frameworks
* HTML5
* CSS
* Bootstrap

### Tools 
* Balsamiq
* GitHub
* Gitpod
* Google Fonts

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

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits

### Content
* The idea for this site came from the podcast _Welcome to Night Vale_ (http://www.welcometonightvale.com/) 
* The text for section Y was copied from the [Wikipedia article Z](https://en.wikipedia.org/wiki/Z)

### Media
* All images used in this site were found through advanced searching Google Images, and are 
fair use for the educational function of this project.

### Acknowledgements

* I would like to thank my mentor, Simen, and the Code Institute Slack Community for their ongoing
support. 