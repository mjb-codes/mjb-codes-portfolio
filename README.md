#User Centric Frontend Development Milestone Project

##Personal Portfolio for Freelance Web Developer

###What is the main goal of the website?
To attract new clients and have them get in contact with potential work and opportunities for web development projects, or showcase work to potential employers

###What is your Call to Action?
To get in contact with the site owner via a contact form - “Get in touch” or “Let’s work together”

###Who will be using it?
Individuals or Businesses in need of a developer to fulfil a web development project

###What do primary users need from the website?
An overview of what services are provided, examples of in-production work and a method to get in contact with the site owner

##UX

###Strategy

####User Needs
Visitors to the website will be potential clients, professional collaborators or potential employers looking to understand the level of skill, experience and scope of previous project work, with the goal of initiating contact about working together.

####Site Objectives
To demonstrate technical ability and personality through a clear flow of information, deployed examples of previous projects and verified references in the form of client testimonials, to encourage contact via web form or through professional social channels.

###Scope

####Key features
*Responsive portfolio section
*“About me” section with short professional bio and current tech stack
*Contact form
*Links to professional social channel (LinkedIn) and GitHub
*Client testimonials

####Content types
*Text: skills list, project descriptions, testimonials
*Media: Hero background video, portrait image for About Me section, icons, project thumbnails
*Interactive elements: Nav links, buttons (with hover animations),  interactive project cards linking to deployed examples, contact form

###Structure

####Information Architecture
*Logical Navigation flow: Home > About Me > Portfolio (& Testimonials) > Contact
*Single page divided into sections, for easier exploration of content
*Sticky navigation header, so all sections can be found at any point of page scroll

####Design interaction
*Smooth scrolling transition between sections when using nav bar
*Design feedback when using interactive elements (e.g. button or card hover animations)
*Mobile-first design, with responsive layouts and collapsible navigation

###Skeleton

####Layout
*Responsive and flexible layout using flexbox
*Call to action prominent “above the fold” (e.g. “Get in touch” button linking to contact section)

####Skeleton
*Sticky navigation header for consistent access to page sections
*Intuitive and consistent design choices (e.g. button colouring)

####Interface
*Contact form with clearly labelled input elements
*Page components that respond and adjust to device size
*Media in appropriate web formats to enhance page performance

###Surface

####Design

*Neutral, professional base colours, with accents to highlight important page features (e.g. CTA buttons)
*Typography - complimentary font pairings between headers and body, contrast font color against backgrounds, legible and professional font for body text
*Use recognisable icons where highlighting tech stack and off-site platforms

####Cues
*Subtle animation on interactive elements, such as project card hovering
*Ensure colour contrast choices are appropriate choices for accessibility

##User Stories

###Users

####User 1 - Small business owner
#####Needs:
-To find someone trustworthy
-View examples of previous projects
-Easily get in touch

####User 2 - Project manager at tech company
#####Needs:
-Evaluate technical level of previous work
-Understand availability
-Assess professionalism

####User 3 - CTO looking to hire
#####Needs:
-See technical proficiency in multiple programming languages
-Understand career progression and assess if the right fit
-Be able to contact through professional channels (e.g. LinkedIn)

###Stories
**_“As a small business owner I want to see examples of websites built for other small businesses, so I can judge if the developer understands my needs”_**

**_“As a project manager I want to view a detailed portfolio, so I can evaluate the developer’s technical ability”_**
	
####Acceptance Criteria
1. The website displays a dedicated Portfolio section with multiple and varied examples of previous projects
2. Each example has a thumbnail image for quick viewing, a link to a deployed version and details about the project
3. All cards are displayed clearly across all devices

####Tasks
1. Create a HTML section on the site dedicated to a project portfolio and populate with cards for each example
2. Include an image of the project, project title and detail text and button linking to the deployed project
3. Add custom dynamic styling with CSS using flexbox

**_“As a small business owner I want to see testimonials from previous clients, so I feel reassured that they are trustworthy to hire”_**

**_“As a project manager I want to understand that the developer can work with us in a professional manner by seeing evidence of this from previous clients”_**

**_“As a potential employer I want to read about how the developer has been received by other clients, so I can assess if they are a good fit for our company”_**

####Acceptance Criteria
1. Website displays a section of testimonials from previous clients about work undertaken for them
2. Testimonies are attributed to a name and business site for validation
3. Testimonies are clear to read across all devices

###Tasks
1. Create HTML testimonials section of website
2. Add testimony text, name and hyperlink to their business
3. Customise display styling with CSS

**_“As a small business owner I want a clear and simple way to contact the developer to arrange to talk about pricing and availability”_**

**_“As a project manager I need an easy method to contact about availability for long-term projects to manage my timeline”_**

####Acceptance Criteria
1. Display a contact section on the site with a form to message the site owner
2. Enable user to enter personal details and message into form, as well as indicate what information they are most interested in determining
3. Form is clearly formatted and usable across different devices 

####Tasks
1. Create a contact section of the page in HTML
2. Build a contact form with input fields for name, email and message, including a dropdown selector with the label “What are you most interested in discussing?” with options for “Pricing, Availability, Ideas, Another topic” and a submit button.
3. Use custom CSS to add flexible styling across different devices

**_“As a potential employer I need to know what technologies the developer specialises in, so I can assess their suitability for the role.”_**

####Acceptance Criteria
1. Include an ‘About Me’ section that clearly states information about what languages, frameworks etc. the developer is familiar in
2. List this information clearly outside of a main paragraph to make it easily visible
3. Format this list to read across all devices

####Tasks
1. Create About Me section in html with image of developer and paragraph of background information
2. Create unordered list of tech stack developer is experienced in
3. Use custom CSS to format list to fill page space dynamically across all devices











