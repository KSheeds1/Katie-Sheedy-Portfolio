# Katie Sheedy - Portfolio Website

Milestone Project One: User-Centric Front-end. 

The purpose of this website is to showcase myself and my abilities, to recruiters and potential employers. The website contains brief snippets of information about me, my skill set, a showcase of six project that use a variety of skills and technologies, and contains a means of contact, through a form, as well as a downloadable CV.

My goal as an owner, is to increase my visibility within the tech world and provide an eye-catching, user-friendly website to gain interest from potential employers and recruiters.

## Demo
Access the live site [here](https://ksheeds1.github.io/Katie-Sheedy-Portfolio/). 

# UX
### User Stories: 
>As a recruiter, I want to find a way to contact Katie directly, to speak about a potential employment opportunity.

>As a potential employer, I want to be able obtain information regarding her skillset, view her latest projects and find links to relevant accounts such as GitHub and LinkedIn, so that I can assess whether she is viable candidate for an available position. 

### Strategies:
* A portfolio website is an imperative asset for a newly qualified developer to increase visibility and cultivate a brand image for oneself. 

* The objective of the site is to proivde a well-structured, accessible webiste that is both, aesthetically pleasing and user-friendly in design.

* The owner goal is to provide users with access to my portfolio, skillset, links to relevant accounts, and a means of contact, clearly laid out in a logical structure.

### Scope:
The **functional requirements** put in place help aid users to access the content they are looking for quickly and easily.

The required content for the website is: 
* General personal information and career specific information
* Showcase of latest work
* Examples of technical skillset
* Contact form
* Downloadable CV.pdf

### Structure:
* The website is designed to foster intuitive learning, the aim is to provide an intuitive interaction between the user and the website.
* Content is structured logically and grouped categorically. 
* Users can quickly identify and access the information they are looking for.

### Skeleton:
 About wireframes:
 
   * [About desktop](https://github.com/KSheeds1/Katie-Sheedy-Portfolio/blob/master/assets/wireframes/images/about-me-desktop.png)
   * [About mobile](https://github.com/KSheeds1/Katie-Sheedy-Portfolio/blob/master/assets/wireframes/images/about-me-mobile.png) 
   * [About tablet](https://github.com/KSheeds1/Katie-Sheedy-Portfolio/blob/master/assets/wireframes/images/about-me-tablet.png)
 
 Portfolio wireframes:

   * [Portfolio desktop](https://github.com/KSheeds1/Katie-Sheedy-Portfolio/blob/master/assets/wireframes/images/portfolio-desktop.png)
   * [Portfolio mobile](https://github.com/KSheeds1/Katie-Sheedy-Portfolio/blob/master/assets/wireframes/images/portfolio-mobile.png)
   * [Portfolio tablet](https://github.com/KSheeds1/Katie-Sheedy-Portfolio/blob/master/assets/wireframes/images/portfolio-tablet.png)

 Skills wireframes:

   * [Skills desktop](https://github.com/KSheeds1/Katie-Sheedy-Portfolio/blob/master/assets/wireframes/images/skill-set-desktop.png)
   * [Skills mobile](https://github.com/KSheeds1/Katie-Sheedy-Portfolio/blob/master/assets/wireframes/images/skill-set-mobile.png)
   * [Skills tablet](https://github.com/KSheeds1/Katie-Sheedy-Portfolio/blob/master/assets/wireframes/images/skill-set-tablet.png)

 Contact wireframes:

   * [Contact desktop](https://github.com/KSheeds1/Katie-Sheedy-Portfolio/blob/master/assets/wireframes/images/contact-desktop.png)
   * [Contact mobile](https://github.com/KSheeds1/Katie-Sheedy-Portfolio/blob/master/assets/wireframes/images/contact-mobile.png)
   * [Contact tablet](https://github.com/KSheeds1/Katie-Sheedy-Portfolio/blob/master/assets/wireframes/images/contact-tablet.png)

### Surface:
The light theme with dark accents was chosen to create an eye-catching first impression. The fonts are clear and legible and contrast nicely against the color scheme. 

# Features
**Navigation Bar:** 
* Fixed, in the default position, allows users to quickly identify the different sections. The font color of each section changes when hovered over. On mobile screen widths, sections are available in a collapsible menu to provide a cleaner layout on smaller screens.

**Bootstrap Cards:**
* Are utilized in the portfolio section to present my projects in bitesized chunks, they contain a link to the live site and to the github repository which are represented through buttons. 

**Progress-bars:**
* Provide a visual representation of my skills, displaying my proficiency in different languages and frameworks. 

**Embedded iframe:**
* Contains a video of the Girls in Tech Hackathon, Dublin. It provides users with a chance to see me put my skills in action within the tech arena.

## Features left to implement
**Filter option:**
* I intent to implement a filter option for the portfolio section, allowing users to filter their search of projects by technology, language, or framework. I plan to implement this feature once my portfolio grows in size.

**Navbar transitions:**
* I plan to implement a hover in/out transition for the navbar sections, where the text is replaced by an icon.

**Contact form functionality:**
* Once I have developed the skills to put in place the back-end structures needed to submit the form and provide interaction 
feedback I will put this in place for the contact form. 

# Technologies Used
* HTML5
* CSS3
* Bootstrap (4.5)
* Autoprefixer

# Testing 
**Functionality:**

Both the potential employer and recruiter user stories have been successfully fufilled.
All sections of the website are clearly 
laid out in the naviagation bar, if viewing on mobile devices, the navigational links collapse into a dropdown menu. While the footer contains a downloadable copy of my CV and links to relevant accounts such as GitHub and Linkedin. 

The about section provides brief snippets of information about me, a photo, if viewed on a desktop or tablet,
my qualilfications and highlights that I am currently available for employment opportunitites. 

My portfolio provides a snapshot of my most recent projects presented in Bootstrap's cards, 
the live site and the GitHub repository for each, can be accessed through the buttons provided. For the time being, the 'live site' buttons link to my GitHub account until a time when, they will be replaced with links to actual projects. 

In regards to my skills, the progress-bars showcase my proficiency in the various languages and frameworks I am familiar with, to users. While, the embedded iframe
provides then with an opportunity to see how I perform within a tech-orientated setting and portrays my skills through a different medium. 

If users would like to contact me, they can simply fill out the contact form provided. 

**Manual testing & Repsonsiveness:**
* The site's 'style.css' was parsed and has had vendor prefixes added by autoprefixer.github.io
* Both the HTML and CSS were validated by W3C Validation Service and passed without error.
* Cross-browser testing was achieved using browserling.com. The site's compatibility was tested across:
    * Chrome            
    * Safari
    * Opera
    * Firefox
    * Internet Explorer


* Testing also took place on multiple mobile devices, such as:
    * iPhone 5, 6, 7, 8, X (Chrome & Safari)
    * Huawei P30 Pro 

* All navigational links will open to the correct section of the site when clicked on. 
* All links will open on to a new tab as a result of 'target="_blank"', each link has been tested to ensure it reaches the desired destination.
* Contact form testing was achieved by:
    * Go to the 'Contact' section.
    * Attempt to submit the empty form and an error message is received to 'please fill in the required field'. 
    * Attempt to submit the form with an invaild email and an error message is received to 'please include an '@' symbol in the email address'.
    * Attempt to submit an empty text area and an error message is received to 'please fill in the required field'.
    * Due to the 'required' attribute, all fields must be filled out for the form to be submitted, once all fields are filled out correctly the page will reload - this is 
    because the back-end structure has not been put in place yet. 

**Manual testing & usability:**

The site was tested by three individuals post-development stage. Testing took place on both on desktop and mobile to ensure
the site: fosters intuitive learning, provides an intuitive interaction and ilicits a positive emotional response from the user.

The test users reported that the context and purpose of the site was clear. Intuitive learning was achieved, as the users found navigating through different sections of the site easy,
due to the structured and logical layout provided by the navbar. Its fixed position also allowed them to switch between sections quickly and easily, achieving the owners goal for an intuitive
interaction. Users also reported a positive emotional response to the site after the interaction.  

**Fixed bugs:**
* A bug was found while testing on 'internet explorer'. The background-color of the portfolio cards was not supported as it was provided using RGBA.
Adjusting the background color from using RGBA to RGB resolved the issue.


**Known bugs & issues:**
* The contact form does not yet have the back-end technology in place to send the form, filling out the required fields and clicking 'send' will just reload the page, until a time, when the back-end structure needed 
can be put in place and the form will work functionally.

* The site was flagged for an issue in Chrome 'Dev Tools' concerning the setting of the 'SameSite attribute' for a cross-site request to send cookies pertaining
to the embedded iframe. At first, this was believed to be a result of an 'Ad Blocker' extension however, on further expection and research of 'SameSite' attributes, it is the resonsibility of the API owner to set such attributes, in this case, YouTube. 

# Deployment 
This site is hosted by GitHub Pages, the publishing source chosen was the 'master' branch. To choose a publishing source and deploy the site:
* Navigate to the site's repository
* Under the repository name, click **settings**
* Under **GitHub Pages** use the **branch drop-down menu** and select **'master'** as the publishing source
* Click **'Save'** 

To run locally, you can clone this repository, or pull the code from this GitHub repository:
* Navigate to the main page of the repository
* Click the green **code** button
* To clone the repository **using HTTPS**, under **'Clone with HTTPS'** click the clipboard symbol

* Open Git Bash
* Change the current working directory to the loction where you want the cloned directory
* Type  ```git clone``` and paste in the copied URL  
``` $ git clone https://github.com/KSheeds1/Katie-Sheedy-Portfolio.git```
* Press **Enter** to create your local clone
  
# Credits
## Content
All content for the 'About', 'Portfolio', and 'Skills' sections was written by me. 

## Media
**About-Me image:**

This image is my own personal property.
 
**About-Me background:**

This image was obtained from unsplash.com, a stock photography library.

**Skills background:**

This image was obtained from unsplash.com.

**Girls in Tech video:**

This video was obtained from youtube.com, provided by user [No Name Here](https://www.youtube.com/channel/UCNNW3D4yqruKNBtdrG0n2zg).

## Acknowledgements

The column structure for the 'about-me' points of information was sourced and adapted from Code Institute Module 5: 'User Centric Front-end Devlopment'
(Putting It All Together | Mini Project with Bootstrap 4 > Three Reasons To Hire Me) the column structure was modified to fit the structure and style of this site.  