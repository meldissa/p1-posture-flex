# Posture Flex

## Project Overview

Posture Flex is a site that aims to provide information about posture and exercises to improve it. This site has been created as part of my Portfolio Project 1 for Code Institute.

## Table of Contents

## User Experience (UX)

## Strategy

### Project Goals

The main business goal for Posture Flex is to teach about benefits of good posture, why posture is important and to provide various exercises a user can learn and implement to improve their posture daily. The site users are interested in learning about benefits of good posture and performing exercises to help improve it. 

The target audience for the site would include users who are office workers/remote workers constantly working at a desk, or spend their day using technology and sitting down restricting their movement. Such posture and back issues are a common problem for those whose work doesn’t allow for much movement during the day. Users who find the lack of mobility, exhibit poor form, and will find that over time this results in a poor posture and back pain, therefore the site aims to capture this target audience and provide easy and simple solutions via exercises to help alleviate this issue. In addition, the site is accessible to all fitness levels and tries to account for this by offering beginner friendly exercises to improve posture which a user of any fitness level can complete.

### User Stories

* __First Time Visitor Goals:__

    * I want to learn more about the site, the purpose, and the ethos of the company.
    * I want to learn why posture is important, what are the benefits of good posture and what are common posture mistakes.
    * I want to find information on the exercises available to improve my posture and how I can perform these.
    * I want to navigate easily through the site and find the relevant information with ease.
    * I want to locate their social media accounts so I can receive updates and see their following and how well they are known and reliable.
    * I want to be able to contact the company with any additional questions I may have regarding the information presented.

* __Returning Visitor Goals:__

    * I want to continue to perform the exercises to improve my posture.
    * I want to be able to contact the company with any further questions and/or be able to provide feedback.

* __Site Owner Goals:__

    * I want users to be able to find the information and exercises to improve their posture in an accessible and simple way.
    * I want users to be able to contact us with any questions or feedback of improvement regarding the content of the site.
    * I want users to be able to locate us on social media and follow us to increase the following.

## Scope

To achieve the strategy goals I want to implement the following features:

* A navigation bar fixed at the top of the screen which will allow the user to easily navigate and find the relevant sections even when the user scrolls down the page.
* A Home section that will focus on providing the user with the relevant information on posture to incentivise the user to stay on the site and continue without overwhelming with unnecessary information.
* An About Us section that will focus on providing the user with the company’s ethos and objective, this will act as additional marketing and legitimise the site to gain the user’s trust.
* An Exercises to provide the user with a list of exercises that can be performed to improve their posture, each exercise having detailed steps both written and visual to allow the user to follow these with ease.
* A Contact Us section which will allow the user to contact the organisation with any queries as well as provide feedback.
* A fully responsive design that will work on different devices including desktop, tablets, and mobile devices, allowing users to access the site anytime and anywhere.

## Design

### Colors

The palette was created using the [Coolors Website](https://www.coolors.co).

[Original Posture Flex Color Palette](assets/images/posture-flex-color-palette.png).

The original color pallete created using the coolors website consisted of 5 colors, however for my final idea I only opted for 3 main colors to use for my website.

The colors used in hex form are white (#fff), dark grey (#202020), and blue (#52daf1). The white color was used as the main background for the website, the dark grey was used for the header and footer and the blue was used for links and buttons. I kept it minimal and simple so this does not distract the user from the main content of the site or overwhelm them with excessive use of different colors.

### Typography

The fonts were obtained from [Google Fonts](https://fonts.google.com/).

For my logo text and heading I have used Lato. Lato is a sans serif typeface family, it is easy to read, and the strong structure provides a good base for the logo text and headings to capture the user’s attention.

For the main text I have selected Montserrat which complements Lato used for my headings and logo. 

I have avoided using overly stylised fonts, which can be difficult to read for users, therefore ensuring the website is more accessible to users with visual impairments.

In the event the font fails to load, I have used sans-serif as a back-up font.

### Imagery

Images are obtained from the [Freepik](https://www.freepik.com/) and [Unsplash](https://unsplash.com/) websites.

I have used imagery appropriate to the website’s content to entice the user and provide visual examples in conjunction with the text for the different exercises.

Please see further details in the __Credits__ section for the specific images used within the project.

## Skeleton

### Wireframes

Wireframes were created using [Balsamiq Wireframes](https://www.balsamiq.com/).

The wireframes have examples of desktop, tablet and mobile phone displays.

* [Posture Flex Wireframe](assets/images/Wireframe.png)

Originally, I wanted to create a website with 4 pages inlcuding Home, About Us, Exercises and Contact Us. However, for my final submission of the project I opted for a single paged website which consists of all these 4 pages split up into sections which can be accessed via the user scrolling down the page or selecting the section from the navigation bar.

## Features

### Current Features

For this project I opted for a single page website, this is fully responsive and consists of a header, footer and 4 main section; Home, About Us, Exercises and Contact Us.

* __Header__: In the header section I have included a fully responsive navigation which is accessible at different screen sizes. On larger screens for desktops, the navigation bar consists of the Posute Flex logo on the left hand side. The navigation buttons for Home, About Us, Exercises and Contact Us are locate on the right hand side. The user is able to hover over the logo and each of the navigation section buttons which has the hover CSS style applied to change color so user is aware that this can be selected. The logo can be clicked which will take user back to the top and each of the navigation buttons will take the user to the relevant section of the website. The navigation is also fixed, so when the user scrolls down the page, this is still accessible and the user does not need to scroll back up to the top to access this. There is also the Bootstrap scrollspy element implemented for the navigation so when the user scrolls down the page the relevant section is highligted to indicate to the user which section they are currently viewing. At smaller screen sizes the nagivation for each of the section is collapsed in a burger menu and can be accessed once the user selects the burger menu to display the drop down for each of the section which the user can select. The header section also includes the Bootstrap carousel layout which consists of 3 slides cycling through automatically, if the user does hover over the slide then this stops from moving forward. The slides also include buttons so the user can cycle through this on their own and at the bottom it display which slide is currently displayed out of 3 in the form of bars. The purpose of the carousel slider was to capture the user with the use of imagery and captions on each slider with a relevant link to take the user to the desired section. 

* __Home__: The Home section consists of content which provides the user an introduction of why posture matters, then proceeds to list the benefits of good posture and common posture mistakes. For the latter two sections I have used the Font Awesome icons and applied CSS style to add color to display the benefits in green and mistakes in red. This provides the user with further visual guidance on what these sections represent. I have kept the content simple and minimal so this does not overwhelm the user with too much information.

* __About Us (Learn More About Us)__: The About Us section has the Bootstrap featurette template style applied with text on the left and an image on the right. The text is brief and provides the user with information about Posture Flex and the company's goal. Once again this is kept simple to not overwhelm the user with information overload. The image used fits in with the general color scheme of the website and adds visual for the user to break up the section so this is not just covered with text.

* __Exercises (Try These Exercises)__: The Exercises section contains a list of 5 exercises the user can perform to improve their posture. Each exercise type is split up using a heading to indicate to the user that this is the start of a new section. This is followed by an image to represent what the exercise would look like, the duration of the exercise and the instructions on how to complete this which has an ordered list applied. For lager screens, the text is displayed on the right of the image so the user can view this side by side, and for smaller screens the text is displayed underneath the image so the user can scroll down to view this information without having to zoom in on the text or image. The duration and instruction sub-headings also have a Font Awesome icon applied to provide further visual display to the user.

* __Contact Us (Get In Touch With Us)__: The Contact Us section is the last section the user is able to access once having scrolled down the webpage, once the user has fully viewed the information they are then able to fill out a contact form. The contact form has a basic layout and gives the user the option to either provide feedback or submit a question via the dropdown option. The form is kept simple and easy to fill out so this does not disinterest the user from submitting feedback or questions by having additional barriers such as exessive amount of required fields and information from user to be able to submit the form.

* __Footer__: The Footer section allows the user to access the social media links, these links are displayed using the Fontawesome icons. The user is also able to hover over the links which have the CSS hover style applied to signal to the user which link they are selecting and opening up. I have also added code to open the links in a new tab so the user is not taken away from the main website and can easily return back, which would also improve the overall UX.

### Future Features

Due to time constraints I was unable to apply additional features, in the future I would like to implement the following:

* A sign up to newsletter option, to allow the user to be able to get frequent updates.
* Improve upon the Exercises section, by seperating the exercises by posture concern. The user will then be able to select the relevant posture concern that they have and follow the set exercises making this more specialised. Add video to each exercise to allow the user the option to view this on how to complete the exercise.
* Add a blog section where the site will post up to date news, suggestions and tips in relation to posture.

## Technologies Used

For this project the main languages used are __HTML5__ and __CSS3__.

I have also utilised the following frameworks, libraries and tools:

* [Bootstrap v5.0.1](https://getbootstrap.com/): Bootstrap has been used for overall responsiveness of the website, and for the layout to include navigation, carousel, featurette and forms within the relevant sections of the website.
* [GitPod](https://www.gitpod.io/): I used GitPod as the IDE for this project and Git has been used for Version Control.
* [GitHub](https://www.github.com/): GitHub has been used to create a repository to host the project and receive updated commits from GitPod.
* [Balsamiq](https://balsamiq.com/): I used Balsamiq to create the wireframe for the website for the basic structure and layout.
* [Coolors](https://coolors.co/): I used Coolors website to create the color palette for my project to use this as a reference.
* [Freepik](https://www.freepik.com/): Freepik has been used for copyright free images for this project.
* [Unsplash](https://unsplash.com/): Unsplash has been used for copyright free images for this project.
* [Google Fonts](https://getbootstrap.com/): I have used Google Fonts to import fonts for styling purposes for this project.
* [Font Awesome](https://fontawesome.com/): Font Awesome was used to apply icons in the Home, Exercises and Footer sections.
* [GIMP v2.10](https://www.gimp.org/): GIMP image manipulator program was used to re-size images for this project.
* [Chrome Dev Tools](https://developers.google.com/web/tools/chrome-devtools): Chrome Dev Tools was used to test the site, assist with debugging issues and run reports from Lighthouse.
* [W3C Markup Validation Service](https://validator.w3.org/): The W3C Markup Validation Service was used to validate the HTML document for this project and to identify any issues with the code.
* [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/): The W3C CSS Validation Service was used to validate the CSS document for this project and to identify any issues with the code.

## Testing

## Deployment

## Credits

### Content

For the Benefits of Good Posture section, the content was used from the following source:

* [Dr.BodyGadget Article](https://www.drbodygadget.com/how-to-improve-posture/)

For the Common Posture Mistakes section, the content was used from the following source:

* [NHS](https://www.nhs.uk/live-well/exercise/common-posture-mistakes-and-fixes/)

For the Exercises section, the content was used from the following sources:

* [healthshots](https://www.healthshots.com/fitness/staying-fit/try-these-5-simple-exercises-at-home-to-fix-your-bad-posture/)
* [tfliving](https://tfliving.com/2019/12/06/11-yoga-poses-to-help-correct-posture-and-alignment/)
* [classpass](https://classpass.com/movements/seated-spinal-twist#:~:text=Hook%20your%20left%20arm%20around,repeat%20on%20the%20other%20side.)
* [msn](https://www.msn.com/en-us/health/exercise/pilates/arm-and-leg-extension-on-knees/ss-BBtOhs2)

### Media

The images used for this project we obtained from the following sources:

* Carousel Slide 1 - from [Unsplash](https://images.unsplash.com/photo-1493224533326-630c89563300?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1050&q=80)
* Carousel Slide 2 - from [Unsplash](https://images.unsplash.com/photo-1549576490-b0b4831ef60a?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1050&q=80)
* Carousel Slide 3 - from [Unsplash](https://images.unsplash.com/photo-1565728744382-61accd4aa148?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1052&q=80)
* About Us - from [Freepik](https://image.freepik.com/free-photo/close-up-portrait-attractive-young-woman-isolated_273609-36522.jpg)
* Exercise 1 (Cobra) - from [Freepik](https://image.freepik.com/free-photo/yoga-girl-doing-cobra-asana-as-her-morning-exercise-home_1098-20279.jpg)
* Exercise 2 (Opposite Arm Leg Extension) - from [Freepik](https://image.freepik.com/free-photo/picture-happy-charming-young-female-with-hair-bun-doing-physical-training-light-room-performing-plank-raising-opposite-leg-arm-preparing-body-summer-people-active-lifestyle_344912-1075.jpg)
* Exercise 3 (Cat-Cow) - from [Freepik](https://image.freepik.com/free-photo/young-woman-practicing-yoga-doing-asana-paired-with-cat-pose_23-2148047405.jpg)
* Exercise 4 (Seated Twist) - from [Freepik](https://image.freepik.com/free-photo/young-woman-ardha-matsyendrasana-pose-against-city-river_1163-2402.jpg)
* Exercise 5 (Downward Dog) - from [Freepik](https://image.freepik.com/free-photo/full-length-view-flexible-young-woman-with-slim-fit-body-working-out-fitness-center-hall-doing-yoga-exercising-with-mat-wooden-floor-doing-downward-facing-dog-adho-mukha-svanasana-pose_344912-1080.jpg)

## Acknowledgements