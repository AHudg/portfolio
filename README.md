# Andrew Hudgins Programming Portfolio
## Description
This code was created to host my primordial programming portfolio. It creates a space for me to display my personality and my skills to my potential clients- allowing them to learn more about me. 

The page contains a sticky header that scrolls throughout an *About*, *Projects*, and *Contact* section. The header also contains a link to my resume as well. The *Projects* section contain interactive images that display the project title along with the code used to build it. Lastly, the *Contact* section contains links to my phone number, email and relative social medias, as well as a inquiry form where the user can email me straight from the website their thoughts, ideas, and projects.

## Built With:
* HTML
* CSS

## Planned Updates:
* More intricate designs drawn into the landscape of the page.
* Use a media query for small desktops and larger that changes the sticky header to a sidebar that takes up a fixed portion of the LHS screen at full heighth.
* Condense CSS code- while it isn't ~too~ crazy, I think I could clean it up more.
* Perhaps actually code some projects to update the page with? Just a thought...

## Key Features:
### Utilization of Flex Boxes
Through flex boxes, I was able to achieve a clean design of stacked elements. Manipulating the design using display:flex allowed for more control of how the elements flowed and greatly increased the overall screen responsiveness of this project. Below is an image of the *Projects* section where I highlighted using similar colors the flex parent container along with the corresponding flex children based on how I coded the nested containers.

![Screenshot of how I used nested flex box parent elements, utilizing different main axis, to achieve a stacked layout of my projects](/assets/images/readmePhotos/flexbox.png)

### Media Queries for Screen Responsiveness
This project was built from scratch using a maximum width of 480px. While being built, preset phone screen simulations were used on Google Chrome's Developer Tools to ensure the webpage displayed well on all screen sizes. From here, I scaled the page to common breakpoints of screens:
    * 480px and below for cell phones
    * 481px to 768px for iPads and tablets
    * 769px to 1024px for small screens and laptops
    * 1025px to 1200px for desktops and large screens
    * 1200px and above for extra large screens and TVs

With each of these breakpoints, minor tweaks were adjusted to font-sizes or margins to make the page flow more cohesively as I increased my viewing parameters. NOTE: Using CSS units such as vw or vh greatly enhanced the overall usability of the program on any screen without the use of media queries.

![Screenshot of how I used media queries to help with screen responsiveness](/assets/images/readmePhotos/MediaQueries.png)

### CSS Variables
CSS Variables were used so that editting the major themes of the page can be done within a simple code line rather than picking through each line to change particular elements. This will be invaluable when refining the website to fit my exact personality. And it is efficient!

![Screenshot of CSS Variables that allow quick changes of multiple variables](/assets/images/readmePhotos/CSSvariables.png)

View the live page [here](https://ahudg.github.io/portfolio/index.html)

## Contribution
Made by Andrew Hudgins :)