# Web Developer’s Professional Page

## Description

The aim of this project was to build a portfolio to showcase the developer’s work. The motivations for this included bolstering the developer’s public image and consolidating their deployed applications into a ‘one-stop-shop’ that is easily accessible to potential employers.

The project criteria included creating a page that displays the developer’s name, avatar and sections to portfolio their recent work and display their contact details. 

The specification for the portfolio section (called “Work”) was to include a larger image of the first project showcased in this section.

The page was also required to be responsive on various screens and devices.


## Development, Build and Limitations

Wireframes were created to demonstrate the page layout on different devices/screens, based on the recommended breakpoints for large (1008px and larger), medium/ small (641px to 1007px; 640px to 376px) and mobile (less than 376px) (Microsoft, 2023; Medium, 2023).

### Wireframe for large (1008px and larger)

<img src="./images/wireframe-large.png" alt="screenshot of wireframe for large screens. A header/navigation bar spans the top of the page. Under the header/navigation bar is the About me section. This is one row and from left to right displays a header, avatar and text. Under the About me section is the Work section. This consists of three rows. The first row, left to right, displays a header and image of project 1. The second row, left to right, displays two project images. The third row, left to right, displays another two project images. Under the Work section is the Contact me section. This is one row and from left to right displays a header and contact me links." width="50%"/>

### Wireframe for medium and small (641px to 1007px; 640px to 376px)

<img src="./images/wireframe-medium.png" alt="Screenshot of wireframe for medium and small screens. This is the same as the wireframe for larger screens, but the avatar in the About me section has been replaced with a larger area for text." width="50%"/>

### Wireframe for mobile (less than 376px)

<img src="./images/wireframe-mobile.png" alt="Screenshot of wireframe for mobile. This is the same as the wireframe for medium screens, but the header/navigation bar and all of the header sections are no longer included." width="50%"/><br>

To meet the aims of the project and build the page (as per the wireframes above), CSS flexboxes, grids and media queries were added into the original starter code. This included three individual grids for the “About me”, “Work” and “Contact me” sections.

On reflection, a CSS grid applied to the `<main>` element may have been a better approach (e.g. would have allowed for easier symmetry across the three sections).

The design for mobile is also, arguably, a ‘pared down’ version of the design for larger resolutions. To combat this, a mobile-first approach could have been considered from the outset (Interaction Design Foundation, 2016).

