# Project 1 - Static Front-End Website Development
## Background
This project focuses on the development of a static website that deploys the use of HTML, CSS and responsive frameworks.

For this project, a website for a real estate company simply named "HOMES" was established as a building point. 

HOMES' website's main objective is to serve as a focal point where home owners and home buyers can browse available properties for transaction and, connect with a suitable real estate agent.

Overall, the website was designed with a simple, non-sophisticated feel. Not wanting to display too much content, yet, displaying sufficient information to entice potential customers to connect with the company. 

## Demo 
Here is a live demo of the website: https://juzcrap.github.io/milestone-1/

## Project Strategy
Site is currently defined into 3 active pages:
1. Home/Index page - a brief outline to sell what the company does
2. Agents page - an image gallery of the top agents
3. Contacts page - for contact/queries direct to the company

A common navigation bar is always visible at the top of the site.
- Through the navigation bar, users can select on what their options of "Buy", "Sell" or "Contact"
The House icon/company logo at the top left of the site will take you back to the landing page.
At the foot of each page, there is a call for newsletter sign-up to be notified whenever there are news/updates associated with the company.

### User Stories

| User Stories        | Description           | Features  |
| ------------- |:-------------| :-----|
| 1 | User wants to find a reliable property agent. | Implementation of a section for agent testimonials. |
| 2 | User browses through image gallery and is interested in a property | Implementation of a direct link to an agent through property image and or contact page |
| 3 | User wants to browse different types of property      |   Implementation of image galleries or property listings differentiated by property types.  |
| 4 | User is interested in the market value for a certain property | Implementation of a property value evaluation input form. |
| 5 | User is merely interested in being kept up to date with property news | Implementation of a newsletter sign-up form function. |

## Project Structure
### Existing Features

#### Navigation Bar
 - Holds all links to active pages of the site
 - Set to fixed top so user never loses sight of the navigation bar wherever he/she is, on the site
 - The Navigation Bar collapses on mobile and is available through a drop-down toggler

#### Home Page
 - First page that the website's address will bring the user to
 - The page is not meant to be fancy but with sufficient information to get the user's attention
 - A submit form allows the user to input a location address for the company to assess the market valuation of the provided address
 - Cards are used to highglight the company's strengths and key service objectives
 - A carousel of images and short paragraphs is used to summarize success stories

#### Agents Page
- Brings the user to a page where the company's top 6 agents are featured
- There are 2 buttons on this page
  * Agents - Profile of all other agents in the company can be accessed through this button
  * Testimonials - Following each transaction, customers are encouraged to send in testimonials of the agent who has served them. Testimonial write-ups will be available through this button
  
#### Contact
- Brings the user to a page where the company contact number, email address and physical site location can be found
- Clicking on the phone number will allow direct call access when assessing the site on a mobile device
- Clicking the email address will prompt a new mail/message window from Outlook
- Map of physical site location will not be visible on mobile

#### Footer
- A common footer exists on all pages of the current site
- A call to sign-up for the company's newsletter exists in this footer
- Javascript is used to activate sign-up button only when the correct email format is in place
---
### Features to implement
* Links to buy/sell selections in navbar
* Improvement of carousel layout on homepage for ipad device
* Including a back-to-top navigation
* Inclusion of links to agent testimonials and separate page displaying all the company's agents
* Inclusion of a search function and displaying results based on user input of search criteria

## Project Surface
A simple minimalistic design was used to create the website. Not wanting to have too much colour and design and have users forget their purpose in visiting the site.

## Technologies Used
- HTML5 
  * Used to structure the content of the website
- CSS
  * Used to style the website
- Bootstrap framework 
  * Used for overall responsiveness of site pages
- Javascript
  * Used for input validation function in page footer

## Testing
### Manual Testing
| Test Case        | Test Description           | Pass/Fail  |
| ------------- |:-------------| :-----|
| 1 | On each page, user should see a navbar with a House icon and 4 selection buttons | Pass |
| 2 | On hover over active navbar buttons, a white bottom border appears | Pass |
| 3 | Clicking on Buy, Sell buttons will show a drop-down list with 3 options  | Pass  |
| 4 | When page is collapsed, navbar collapses to display a hamburger toggler | Pass |
| 5 | Selections in collapsed toggler should line up in the center of the page | Pass |
| 6 | Navbar remains visible at the top of the page regardless of how far down the user scrolls  | Pass |
| 7 | Clicking on the house icon in the navbar will bring you back to the landing page  | Pass |
| 8 | Clicking on Agents button in the navbar will bring you to The Team page  | Pass |
| 9 | Clicking on Contact button in the navbar will bring you to Contact page  | Pass |
| 10 | Text in jumbotron of The Team and Contact pages will remain in the center of the page regardless of page size  | Pass |
| 11 | Text in jumbotron of Home page will remain aligned to the left of the page regardless of page size  | Pass |
| 12 | Jumbotron images will fill entire width of page regardless of page size  | Pass |
| 13 | Container text on each page will always align to the center of the page regardless of page size  | Pass |
| 14 | Deployed bootstrap card components will stack-up on each other when page is in mobile mode or when window is minimized on laptop/desktop  | Pass |
| 15 | Image of houses on Home page will not be displayed when page is accessed in mobile mode or when window is minimized on laptop/desktop  | Pass |
| 16 | Map on Contact page will not be displayed when page is accessed in mobile mode or when window is minimized on laptop/desktop  | Pass |
| 17 | Clicking on contact number on Contact page will prompt user for call function  | Pass |
| 18 | Clicking on email address on Contact page will prompt a new mail window from Microsoft Outlook  | Pass |
| 19 | Footer section will always remain at the bottom most section of the page  | Pass |
| 20 | Text within footer section of the page will be center aligned when page is minimized or accessed in mobile mode  | Pass |
| 21 | Sign-up button remains disabled until user keys in correct email address format into input box  | Pass |

### Mobile Responsiveness Test
- Site was tested on Android and Apple devices through the assistance of familiy and friends.
- Site works well on all tested platforms with some alignment improvement work required in the carousel section of the home page.

## Deployment
The site is now deployed on GitHub.

1. Site coding was started on Visual Studio Code before transferring intitial code draft into Cloud9 environment. 
2. A new remote repository titled Project 1 was created in GitHub.
3. The local repository in Cloud9 was then linked to the remote repository in GitHub.
4. The code file initial commit was made to link both local and remote repositories. 
5. At regular intervals of code edits, the terminal in Cloud9 was accessed to git commit and git push edited files to ensure that the remote repository is updated with my latest code changes. 

## Credits
### Media
- All images found on the site were sourced from https://unsplash.com/
- Home icon was sourced from https://www.iconfinder.com
- Font styles where applicable were sourced from Google Fonts


