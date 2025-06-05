# User Centric Frontend Development Milestone Project

## Personal Portfolio for Freelance Web Developer

### What is the main goal of the website?
To attract new clients and have them get in contact with potential work and opportunities for web development projects, or showcase work to potential employers

### What is your Call to Action?
To get in contact with the site owner via a contact form - “Get in touch” or “Let’s work together”

### Who will be using it?
Individuals or Businesses in need of a developer to fulfil a web development project

### What do primary users need from the website?
An overview of what services are provided, examples of in-production work and a method to get in contact with the site owner

## UX

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

**_“As a small business owner I want to see testimonials from previous clients, so I feel reassured that they are trustworthy to hire”_**

**_“As a project manager I want to understand that the developer can work with us in a professional manner by seeing evidence of this from previous clients”_**

**_“As a potential employer I want to read about how the developer has been received by other clients, so I can assess if they are a good fit for our company”_**

#### Acceptance Criteria
1. Website displays a section of testimonials from previous clients about work undertaken for them
2. Testimonies are attributed to a name and business site for validation
3. Testimonies are clear to read across all devices

### Tasks
1. Create HTML testimonials section of website
2. Add testimony text, name and hyperlink to their business
3. Customise display styling with CSS

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

**_“As a potential employer I need to know what technologies the developer specialises in, so I can assess their suitability for the role.”_**

#### Acceptance Criteria
1. Include an ‘About Me’ section that clearly states information about what languages, frameworks etc. the developer is familiar in
2. List this information clearly outside of a main paragraph to make it easily visible
3. Format this list to read across all devices

#### Tasks
1. Create About Me section in html with image of developer and paragraph of background information
2. Create unordered list of tech stack developer is experienced in
3. Use custom CSS to format list to fill page space dynamically across all devices

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

## Libraries

### Font Awesome

[Font Awesome vers. 6](https://www.fontawesome.com) icon library is installed to allow for branded icons in the About Me and Contact sections

### Tutorials referenced

[Gradient backgrounds in CSS](https://www.w3schools.com/css/css3_gradients.asp)
[The :checked property for checkbox inputs (for menu toggling)](https://developer.mozilla.org/en-US/docs/Web/CSS/:checked)
[Height transition animation referenced for menu toggling](https://www.w3schools.com/css/tryit.asp?filename=trycss3_transition2)

## Testing

### Bugs

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