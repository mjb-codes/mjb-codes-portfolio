# User Centric Frontend Development Milestone Project

## Personal Portfolio for Freelance Web Developer

A single page website built with HTML and CSS deployed using [GitHub Pages](https://pages.github.com/)

### Live demo

[MJB Codes Portfolio website](https://mjb-codes.github.io/mjb-codes-portfolio)

### Project Structure

```bash
mjb-codes-portfolio/
├───index.html
├───style.css
├───script.js
└───assets
	└───images
    	├───styles
    	├───videos
    	└───wireframes
└───README.md
```

### Built with:

* HTML5
* CSS3
* Github pages

### Deployment instructions

You can deploy this project to GitHub Pages using the following steps:

#### 1. Push the Project to GitHub

```bash
git init
git remote add origin https://github.com/mjb-codes/mjb-codes-portfolio.git
git add .
git commit -m "Initial commit"
git push -u origin main
```

#### 2. Enable GitHub Pages

1. Go to the repository on GitHub.

2. Go to Settings and select Pages.

3. Under Source, select main (or master) branch and / (root) folder.

4. Click save

---

## UX

### What is the main goal of the website?
To attract new clients and have them get in contact with potential work and opportunities for web development projects, or showcase work to potential employers

### What is your Call to Action?
To get in contact with the site owner via a contact form - “Get in touch” or “Let’s work together”

### Who will be using it?
Individuals or Businesses in need of a developer to fulfil a web development project

### What do primary users need from the website?
An overview of what services are provided, examples of in-production work and a method to get in contact with the site owner

### Strategy

#### User Needs
Visitors to the website will be potential clients, professional collaborators or potential employers looking to understand the level of skill, experience and scope of previous project work, with the goal of initiating contact about working together.

#### Site Objectives
To demonstrate technical ability and personality through a clear flow of information, deployed examples of previous projects and verified references in the form of client testimonials, to encourage contact via web form or through professional social channels.

### Scope

#### Key features
* Responsive portfolio section
* “About me” section with short professional bio and current tech stack
* Contact form
* Links to professional social channel (LinkedIn) and GitHub
* Client testimonials

#### Content types
* Text: skills list, project descriptions, testimonials
* Media: Hero background video, portrait image for About Me section, icons, project thumbnails
* Interactive elements: Nav links, buttons (with hover animations),  interactive project cards linking to deployed examples, contact form

### Structure

#### Information Architecture
* Logical Navigation flow: Home > About Me > Portfolio (& Testimonials) > Contact
* Single page divided into sections, for easier exploration of content
* Sticky navigation header, so all sections can be found at any point of page scroll

#### Design interaction
* Smooth scrolling transition between sections when using nav bar
* Design feedback when using interactive elements (e.g. button or card hover animations)
* Mobile-first design, with responsive layouts and collapsible navigation

### Skeleton

#### Layout
* Responsive and flexible layout using flexbox
* Call to action prominent “above the fold” (e.g. “Get in touch” button linking to contact section)

#### Skeleton
* Sticky navigation header for consistent access to page sections
* Intuitive and consistent design choices (e.g. button colouring)

#### Interface
* Contact form with clearly labelled input elements
* Page components that respond and adjust to device size
* Media in appropriate web formats to enhance page performance

### Surface

#### Design

* Neutral, professional base colours, with accents to highlight important page features (e.g. CTA buttons)
* Typography - complimentary font pairings between headers and body, contrast font color against backgrounds, legible and professional font for body text
* Use recognisable icons where highlighting tech stack and off-site platforms

#### Cues
* Subtle animation on interactive elements, such as project card hovering
* Ensure colour contrast choices are appropriate choices for accessibility

## User Stories

### Users

#### User 1 - Small business owner
##### Needs:
- To find someone trustworthy
- View examples of previous projects
- Easily get in touch

#### User 2 - Project manager at tech company
##### Needs:
- Evaluate technical level of previous work
- Understand availability
- Assess professionalism

#### User 3 - CTO looking to hire
##### Needs:
- See technical proficiency in multiple programming languages
- Understand career progression and assess if the right fit
- Be able to contact through professional channels (e.g. LinkedIn)

### Stories
**_“As a small business owner I want to see examples of websites built for other small businesses, so I can judge if the developer understands my needs”_**

**_“As a project manager I want to view a detailed portfolio, so I can evaluate the developer’s technical ability”_**
	
#### Acceptance Criteria
1. The website displays a dedicated Portfolio section with multiple and varied examples of previous projects
2. Each example has a thumbnail image for quick viewing, a link to a deployed version and details about the project
3. All cards are displayed clearly across all devices

#### Tasks
1. Create a HTML section on the site dedicated to a project portfolio and populate with cards for each example
2. Include an image of the project, project title and detail text and button linking to the deployed project
3. Add custom dynamic styling with CSS using flexbox

#### Action

The Portfolio section of the website displays 'Project cards' which include a background image of the target website, a short description and a link to a production (or archived) version of the project.

![Portfolio website section](https://mjb-codes.github.io/mjb-codes-portfolio/assets/images/portfolio-section.png "Portfolio section screenshot")

Using flexbox, the cards wrap underneath each other as screen size is reduced, displaying each one clearly on the vertical scroll.

![Portfolio section on Mobile screens](https://mjb-codes.github.io/mjb-codes-portfolio/assets/images/portfolio-section-responsive.png "Portfolio section screenshot on mobile screens")

**_“As a small business owner I want to see testimonials from previous clients, so I feel reassured that they are trustworthy to hire”_**

**_“As a project manager I want to understand that the developer can work with us in a professional manner by seeing evidence of this from previous clients”_**

**_“As a potential employer I want to read about how the developer has been received by other clients, so I can assess if they are a good fit for our company”_**

#### Acceptance Criteria
1. Website displays a section of testimonials from previous clients about work undertaken for them
2. Testimonies are attributed to a name and business site for validation
3. Testimonies are clear to read across all devices

#### Tasks
1. Create HTML testimonials section of website
2. Add testimony text, name and hyperlink to their business
3. Customise display styling with CSS

### Action

A Testimonials section was added within the Portfolio section with the title "Client Experiences". Flexbox was used for the layout and to make the section responsive across devices.

![Testimonials secton of the website](https://mjb-codes.github.io/mjb-codes-portfolio/assets/images/testimonials.png "Screenshot of the testimonials section")

The quotes, names and business names for each testimonial was generated using [ChatGPT](https://chatgpt.com). Anchor tags were styled usng CSS under each testimonial pointing to www.example.com for demonstration purposes.

**_“As a small business owner I want a clear and simple way to contact the developer to arrange to talk about pricing and availability”_**

**_“As a project manager I need an easy method to contact about availability for long-term projects to manage my timeline”_**

#### Acceptance Criteria
1. Display a contact section on the site with a form to message the site owner
2. Enable user to enter personal details and message into form, as well as indicate what information they are most interested in determining
3. Form is clearly formatted and usable across different devices 

#### Tasks
1. Create a contact section of the page in HTML
2. Build a contact form with input fields for name, email and message, including a dropdown selector with the label “What are you most interested in discussing?” with options for “Pricing, Availability, Ideas, Another topic” and a submit button.
3. Use custom CSS to add flexible styling across different devices

#### Action

The Contact section of the page features a HTML form and brand icons from [Font Awesome](#font-awesome) acting as links to external platforms.

By default the Contact section layout is styled for larger screens, as opposed to mobile devices, as media queries in the CSS were used to adjust the flex properties as the screen size reduced. This was necessary to acheive a consistent layout across devices.

![Contact section Flex layout on Large screens](https://mjb-codes.github.io/mjb-codes-portfolio/assets/images/contact-flex.png "Screenshot of the contact section with flex lines")

![Contact section Flex layout on Small screens](https://mjb-codes.github.io/mjb-codes-portfolio/assets/images/contact-flex-mobile.png "Screenshot of the contact section on mobile")

**_“As a potential employer I need to know what technologies the developer specialises in, so I can assess their suitability for the role.”_**

#### Acceptance Criteria
1. Include an ‘About Me’ section that clearly states information about what languages, frameworks etc. the developer is familiar in
2. List this information clearly outside of a main paragraph to make it easily visible
3. Format this list to read across all devices

#### Tasks
1. Create About Me section in html with image of developer and paragraph of background information
2. Create unordered list of tech stack developer is experienced in
3. Use custom CSS to format list to fill page space dynamically across all devices

#### Action

The about section features text content, a profile image and branded icons from [Font Awesome](#font-awesome) representing the developer's Tech Stack (a collection of programming languages or frameworks they are versed in).

As for other sections, the layout was achieved using flexbox, to keep the section dynamic and responsive across all devices.

![About section on a large screen size](https://mjb-codes.github.io/mjb-codes-portfolio/assets/images/about-section.png "Screenshot of the About section")

## Wireframes

These wireframes represent how the single page website will view across different devices. The breakpoints for each device have been decided based on the following screen sizes:

Screen size | Breakpoint | Device Type
--- | --- | ---
Small | `480px and under` | Smartphone (portrait)
Medium | `481px - 768px` | Tablet (portrait)
Large | `769px and above` | Laptop screens and larger

1. [Mobile device wireframe](./assets/wireframes/Portfolio%20Page%20Wireframes.png)
2. [Tablet device wireframe](./assets/wireframes/Portfolio%20Page%20Wireframes.png)
3. [Laptop and larger device wireframe](./assets/wireframes/Portfolio%20Page%20Wireframes.png)

## Design

### Colour Pallette

The base colour pallette chosen for the website is from [colorhunt.co](https://www.colorhunt.co)

The decision to use a mainly blue pallette was made as these colours suggest professionalism, trust and reliabilty, with a contrasting accent colour in red to call attention to pivotal elements such as CTA buttons.

[Blue colour pallette from colorhunt.co](https://colorhunt.co/palette/00354500454a3c6562ed6363)

![Blue colour pallete](./assets/images/Color%20Hunt%20Palette%2000354500454a3c6562ed6363.png "Blue colour pallete")

Additionally, colours for highlighted accent elements and a light text colour that complimented this pallete were added. The completed site colour pallete is as follows:

```html
Primary Dark: #00454A
Primary Light: #3C6562
Secondary: #003545
Highlight: #ED6363
Highlight Raise: #b94c4c
Text Light: #ededed
```

The color pallete hex codes have been added to the global scope of the stylesheet as [custom variables](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_cascading_variables/Using_CSS_custom_properties)

```CSS
:root {
    --color-primary-dark: #00454A;
    --color-primary-light: #3C6562;
    --color-secondary: #003545;
    --color-highlight: #ED6363;
    --color-highlight-raise: #b94c4c
    --color-text-light: #ededed;
}
```
### Fonts

The fonts selected for the website were taken from [Google Fonts](https://fonts.google.com)

**Arvo** Was selected for the logo and headings as a professional and modern looking serif font:

[Arvo font family on Google Fonts](https://fonts.google.com/specimen/Arvo/about?query=arvo)

**Rubik** was selected for body text and links for it's legibility and complementary look against Arvo:

[Rubik font family on Google Fonts](https://fonts.google.com/specimen/Rubik/about?query=rubik)

The-+54- fonts are imported into the stylesheet via @import:

```css
@import url('https://fonts.googleapis.com/css2?family=Arvo:ital,wght@0,400;0,700;1,400;1,700&family=Rubik:ital,wght@0,300..900;1,300..900&display=swap');
```
### Navigation Menu Toggle

The navigation menu toggle for mobile and tablet was created by using an checkbox input and the :checked selector to effect the height of the div container housing the list of page links when in a checked state.

The hamburger icon was imported using the Font Awesome library as the input label, for it to act as a button to change the input state. A transition animation to smooth the open and closing of the menu was also applied to the navigation links container div.

**Navigation HTML:**

```html
<nav class="flex" id="nav">
        <!-- Logo -->
            <div id="nav-logo-container">
                <h1 id="nav-logo">[<span class="heavy-text">MJB</span> codes]</h1>
            </div>
        <!-- Hamburger menu -->
        <div id="nav-menu-icon-container">
            <label class="menu-icon" for="menu-toggle">
                <i class="fa-solid fa-bars"></i>
            </label>
        </div>
        <input type="checkbox" class="menu-toggle" id="menu-toggle">
        <div id="nav-links-container">
            <ul id="nav-links">
                <li>Home</li>
                <li>About</li>
                <li>Portfolio</li>
                <li>Testimonials</li>
                <li>Contact</li>
            </ul>
        </div>
    </nav>
```

**Navigation CSS**

```css
/* Styling to toggle navigation menu open and closed */
/* https://developer.mozilla.org/en-US/docs/Web/CSS/:checked */
/* https://www.w3schools.com/css/tryit.asp?filename=trycss3_transition2 */

#menu-toggle {
    /* hide checkbox input */
    display: none
}

/* increase height of nav links container when input checked to reveal menu */
#menu-toggle:checked + #nav-links-container {
    height: 50vh;
}
```
### Flexbox

[MDN Flexbox documentation](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_flexible_box_layout/Basic_concepts_of_flexbox)

The websites layout and responsiveness was achieved using [Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_flexible_box_layout/Basic_concepts_of_flexbox).

The properties of Flexbox allow for responsive design, as it gives content the ability to best fit the space used, dynamically changing width, height, and wrapping, making it easier to build a dynamic structure.

## Libraries

### Font Awesome

[Font Awesome vers. 6](https://www.fontawesome.com) icon library is installed to allow for branded icons in the About Me and Contact sections

### Tutorials referenced

#### Gradient Background for the Hero section

[Gradient backgrounds in CSS](https://www.w3schools.com/css/css3_gradients.asp)

#### Menu toggling using checkbox inputs

[The :checked property for checkbox inputs (for menu toggling)](https://developer.mozilla.org/en-US/docs/Web/CSS/:checked)

[Height transition animation referenced for menu toggling](https://www.w3schools.com/css/tryit.asp?filename=trycss3_transition2)

---

## Testing

### Responsiveness Testing

The sites responsiveness was tested using Chrome's developer tools to view the the page across the screen breakpoints [outlined in the wireframes section](wireframes)

![Screenshot of Chrome Dev Tools Responsive device view](https://mjb-codes.github.io/mjb-codes-portfolio/assets/images/chrome-dev-tools-responsiveness-screenshot.png "Chrome Dev Tools")

### Hyperlink testing

All hyperlinks were tested manually to ensure they function correctly and opened the external target in a new tab of the browser window.

### CSS and HTML validation

The following services were used to validate the CSS and HTML used in the project:

[CSS Validation Service](https://jigsaw.w3.org/css-validator/)
[Markup Validation Service](https://validator.w3.org/)

### Accessibility testing

To check the websites accessibility the following service was used:

[ADA and WCAG Accessibility Checker](https://www.accessibilitychecker.org/)

This returned errors with visibility using the accent text colour. These elements were adjusted to make the website compliant with WCAG guidelines.

---

### Bugs

This following bugs were discovered during the development process. Each one provides a detail of the issue and the solution to fix it, and where appropriate also the expected behaviour before discovering the bug.

#### Form Textarea

##### Issue

When resizing the text area input box, it caused formatting issues with other elements in the form

##### Solution

The solution was to disable the textarea resize property within CSS stylesheet using `resize: none`

```css
textarea {
    height: 150px;
    resize: none;
}
```
#### Navigation logo and Hero title

##### Issue

The title heading for the Hero section overflowing off screen on smaller device sizes, while the Navigation logo was breaking to a new line

##### Solution

Using a media query for screen sizes below 480px to reduce the font sizes for both elements

```css
@media screen and (max-width: 480px) {

    /* reduce logo size */
    #nav-logo {
        font-size: 5vw;
    }

    /* reduce hero title type size */
    #hero-title {
        font-size: 5vh;
    }
}
```
#### About image wrapper

##### Issue

The sizing of the about image wrapper div was creating a margin to the right of the screen on smaller device widths

##### Solution

Add a media query style rule that reduced the wrapper to 80% of the screen width on devices under 480px

```css
@media screen and (max-width: 480px) {

    /* reduce about image size on smaller devices */

    #about-image-wrapper {
        width: 80vw;
        height: 80vw;
    }
}
```
#### Menu link scrolling

##### Issue

When using the menu navigation links a smooth scrolling transition was expected between sections, but it jumped straight to each section

##### Solution

Add `scroll-behavior: smooth` to the html element in the stylesheet to enable smooth scrolling for the whole page

#### Contact section responsiveness

##### Issue

On screen sizes below 1024px, the contact form would not wrap under the other content, opening a margin to the right side of the screen elsewhere

##### Expected behaviour

Contact form to stack in column under rest of content

##### Solution

Add a media query up to screens sized 1024px that forced flex direction to revert to column
```css
@media screen and (max-width: 1024px) {
    /* Change flex direction of contact form to stack vertically */
    #contact {
        flex-flow: column nowrap;
        justify-content: center;
        align-items: center;
        max-height: 100%;
    }

    /* Revert flex properties of content */

    #contact .title-wrapper,
    #contact .text-wrapper,
    #contact-form-container,
    #socials {
        flex: 1 0 auto;
        align-self: center;
    }

    /* align text center */

    #contact .title-wrapper,
    #contact .text-wrapper, {
        text-align: center;
    }

    /* Justify socials icons evenly */

    #socials-list {
        justify-content: space-between;
    }

    /* Change contact form order in flex */

    #socials {
        order: 1;
        /* Add margin above */
        margin-top: 2rem;
    }
}
```

#### Testimonials not responsive to screen size

##### Issue

The testimonials would keep reducing in width as screen size reduces, making them unreadable

##### Expected behaviour

Testimonials should wrap as screen width reduced beyond their min width

##### Solution

I found an error in the defined property for the Testimonials container in the stylesheet. `flex-direction: row wrap` was defines, where it shuld have been `flex-flow: row wrap`. Changing to the correct property solved the issue.

#### Form submit button width

##### Issue

The submit input button on the contact form was not expanding to 100% width after setting the appropriate CSS properties in a media query

##### Solution

I found using Chrome developer tools that the default button class `.button` was set to `max-width: 200px`. For the submit button I was setting `width: 100%`, so the max-width property remained active. By changing the width property in the media query to `max-width: 100%` the button expanded across the full space.
