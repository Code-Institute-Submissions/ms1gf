<img src="https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png" style="margin: 0;">


--------



# ChildrenDaze.com

ChildrenDaze was  designed to provide entertainment for internauts. The intertainment is in the format of stories where the main protagonists are the children.
In this webesite, people will be able to read stories and share thei own. Also, the website will be used as a media to raise funds for a charity campain that has the goal to help childer with cancer.
The website has a simple and clean interface so people can focus in its content.

## UX
 
1- Who this website is for?  
Answer: This website is for people interested in family frindly entertainment related to children.

2- What it is that users want to achieve in this website?  
Answer: the user want to be inpired by incent children wisdom, laugh at funny and sumetimes unexpected things they say. Also, children can say quite adorable things and if the user is looking for some cozy and warm fillings, they will be able to find it in the website.

3- How your project is the best way to help them achieve these things?  
Answer: there are other webistes that provide the tipe of entertainment that childrendaze intend to offer. However other webistes focus are not based on only children experiences as this site is.

__User Stories:__   
  
| User Action        | Goal          |
| ------------- |:-------------:| 
| User wants to read nice things online during his school break  | to relief stress | 
| User wants to record a cool thing his daughter said     | To remember the cool things his daughter said while growing up      |  
| User wants to share with the world something cool that his little sun said | to show off how cool is his sun      |

  
__Link to wireframe:__     
- [Click here to see wireframe on PDF format. This should take you to the file stored on gitpod](assets/readmeDocs/MS1MockUp_ChildrenDaze.jpg)
???

## Features
 
- ### Existing Features
    - Clickable buttons and links.
    - Forms
    - Modal window
    - Responsive Grid system
    - Color effect on social media icons on the footer
    - Jumbotron
    - Animation on thumb up icons on index.html

- ### Features Left to Implement
    - Ability to register and login.
    - User profile page.
    - Ability to user to share his stories 
    - ability to comment and like posts.

## Technologies Used

[Bootstrap](https://getbootstrap.com/docs/4.0/utilities/display/) 
    - The navigation bar and footer and login/register portions of the website were built with a template from **bootstrap** to spead up development. However, the template's layout and theme have been modified from its original version to blend those functionaities with the rest of the site.
    - The homepage.html, charity.html, and about.html page's content/body section were built from scratch by me using HTML/CSS/Bootstrap.

[Fontawesome](https://fontawesome.com/)
    - **Fontawesome** was used to style the fonts of the project.

[Viewport](https://www.w3schools.com/css/css_rwd_viewport.asp) 
    - Meta name **viewport** was also added in order to make the site responsive to different sizes of screen.
a <link> was added to the site to make the site able to run javascript (thumbs up functionality required it.)
  
  [JQuery](https://jquery.com) and [Javascript](https://www.javascript.com/) - The project uses **JQuery and javascript** to make features responsive to customer actions (thumbs up functionality required it.).


## Testing

Automated testes were not performed.

1. Navigation bar:
    1. Go to the "Homapage" page
    2. Click on all links and button to see if they work and take the user the the pages they meant to go.
    3. Change the size of the screen to make sure that the navbar is presentable
    4. Click the links and button again in different size of screens to verify they still work (mainly when humburrger icon shows).

2. Content section of homepage:
    1. Go to the "Homepage" page
    2. Make sure that the content is readable and properly laid out.
    3. Click the "thunbs" to make sure that the work well in terms of functionality and effects.
    4. Change sizes of screen to make sure that the site is still presentable and functional.

3. Content section of other pages:
    1. Go to the "homepage" page and click on the link "Charity" from the navigation bar.
    2. Make sure that the content is presentable in all sizes of screens and that the button work.
    3. Click on the link "About Us" from the navigation bar.
    4. Make sure the content of the page is presentable in sizes of screen.
    5. Make sure that the text box are working on all sizes of screen by typing text in them to make the digits shows there.

    (*CLARIFICATION NOTE: Testing screensize means, by increasing and decreasing the browser window and using developer tool to test site on mobile view.*)


**The pages in this webiste will be more simple in the mobile view. For example:**
- links in the menu navigator will be replaced by the hamburger icon.
- Footer portion related to social media, will present only the icons (no text "Social Media") and wont have animation/effect on mobile version.
- Content body sections were made with grid system bootstrap, which mean that, in mobile view or small screens, the column will be presented on top of each other as they were rows.

**Bugs:**  
The project had its challenges but I was not able to identify bugs. Execept for one:
- The browser when on a range of 450px-525px widgit, did not recognized the properties inside of CSS rule #c-social-div and #c-footer-contactus

## Deployment

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:
- Different values for environment variables (Heroku Config Vars)?
- Different configuration files?
- Separate git branch?

In addition, if it is not obvious, you should also describe how to run your code locally.


## Credits

### Content
- The text for section charity.html page was copied from the [American Childhood Cancer Organization](https://www.acco.org/donate/)

### Media
-  [Link to the picture source](https://puntfoundation.org/wp-content/uploads/2019/11/PUNT_Banner_Home-Hero_v3.jpg)
     from picture used in the charity.html' 

### Acknowledgements

I received inspiration for this project from [Codeacademy](https://courses.codeinstitute.net/)
- The modal functionality and the mobil hemburger buttons were built inspired on projects from the video classes from code institute (https://courses.codeinstitute.net/)
 