# LiamBrowne.com . - https://liamb123.github.io/LiamBrowne.com.github.io/.

## UX
    The Goal of the site was to make a visually appealing landing page for users looking to hire me as a software developer.
    The UX focus was on aesthically pleasing pages with simple, minimal click navigation and all information being easily available.
    Users can quickly see all aspects of my work and contact me quickly and easily.
    
## User Stories:
    1. An Employer
        I am an employer looking to hire Liam but want to see some of his work before contacting him and seeing if hes up to standard.
        I can easily see his github repos and deployed websites along with contacting him easily off the site.
        
    2. A Recruiter
        I am a recruiter and i think Liam might fit a job opening i have for him.I want a copy of his resumé and a look at what kind of work hes done before.
        The Cv was obtained in a single click and his portfolio accessed quickly, visually easy to see with a quick summary of each of his works.
        
    3. A Developer
        Im a budding developer and im looking for some inspiration for my personal webpage, i want to see what kind of design other developers are using for their sites.
        And hopefully have a look at how they put together their own work.
        
## Features
        1. Navigation Bar
            The Navigation bar is the only aspect consistent on all html pages. It has a light styling to match the black/white theme of the site and has 3 call to actions.
            One Dropdown menu, one pdf opened in a new tab and one contact.
            The Nav Bar collapses when on smaller screen sizes and still functions the same being easiily navigated with the whole site explored in potenitally 3 clicks.
            
        2. Portfolio
            The Portfolio section showcases the work i have done as a developer. In the nav bar by selecting individual sites it opens them directly to the site in a new tab.
            My Git hub repo can be accessed instantly in a new tab and then the Portfolio.html can be accessed.
            the html has an accordion displaying my 3 other milestone projects with a brief summarry of the sites purpose, technology used and links to them.
            This Page is the only page incorporating color as it displays my creative side and is where I would like most users to gravtate toward.
            
        3.Contact
            The Contact section is a simple form wihtin a modal triggered by a block level button. 
            The page is minimal with all aspects of the form being required for it to successfully submit.
            The form contains minimum information about the user, just a message and an address where i can respond to them at.
            
            
    
## Features Left to Implement
    
        1. I would add more to the Portfolio section as my work grows, linking off to other projects i have been apart of.
        
        2. I would wire up the contact section to send the received messges to an email or remake the project in django to store the received messages.

## Technologies Used
    The Main technologies used were Bootstrap (https://getbootstrap.com/), Html, Css , JavaScript and JQuery.

## Testing
    All html files were passed thorugh a html vaildatior (https://validator.w3.org/nu/) to make sure the code was semantically correct and mappable all round. I found several unncessary closing div tags and removed them until a successful pass.
    
    The Single Css file was also passed through a CSS validator (https://validator.w3.org/nu/) to make sure all code was semantically correct and wasnt conflicting.
    
    The Pages themselves were tested manually by clicking all buttons, refreshing, 
    
    Home Page
        The home page image loads on all screen sizes with its main use being the nav bar
        nav bar functioned correctly linking to other htmls correctly and linking to new tabs for off site pages (cv,portfolio sites)
        nav bar collapses appropriately when the minimum screen size was observed
        
    Contact
        The Contact page image loaded correctly on all screen sizes with one possible issue being the white lettering on smaller screens can become difficult to read as it blends with the background image.
        Button remains at a block level regardless of screen size and launches modal correctly
        Modal form launches well on all screen sizes, with the required fields tested by trying to submit without filling out, prompting the user to fill in email addresses in the correct field and some sort of message is requied before hitting send.
        All of these requirements are prompted to the user ensuring a meaningfully filled out form will be sent to the site owner.
        
    Portfolio
        The Portfolio img loads appropriately for each screen size and accordion opens and resizes as required.
        The accordion links are all clickable and launch the sites in a new tab, the page loads with the first open and acts accordingly as a new section is opened the previous closes.
        
## Deployment
    After passing through all testing I deployed the site to GitHub Pages and can be found here - 
    The act of deploying meant i had to chage the repo name addnig a .github.io to allow the deployment.
    I also had to create a an index.md file as the GitPages documentation requires one for deployment. I copied my index.html file into and repeated the testing on the deployed site to ensure there was no discrepancies between the development and deployed versions of the site.


## Content

## Media
    All imagery used in this site was taken from unsplash, and can be found here - https://unsplash.com/
## Acknowledgements 
    I received most of my inspiration from code institutes examplar found here https://www.haleyschafer.com/
    This gave me the key ideas to have an aesthically pleasing contact section and a quickly accessible version of my portfolio and CV.