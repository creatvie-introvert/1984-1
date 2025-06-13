# 1984.1
![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)

### 🔗 Live Site
[view the deplyed site here](https://creatvie-introvert.github.io/1984-1/)

**1984.1** is a satirical website, that explores the relevance of George Orwell's *1984* in today's society, specifically through the lens of modern-day London. It guides users through themes such as surveillance, propaganda, and thought control using humour, visual design and interactive storytelling.

The site is designed for users who want a thought-provoking yet entertaining way to reflect on how dystopian concepts have been repackaged as everyday conveniences in the digital age. It encourages critical thinking about technology, privacy, and media - without taking itself too seriously.

### 🖼️ Site Preview
![Mockup](docs/1984-1-mockup.png)

### [Contents](#)
- [User Goals](#user-goals)
- [User Stories](#user-stories)
- [Website Goals & Objectives](#website-goals--objectives)
- [Wireframes](#wireframes)
- [Design Choices](#design-choices)
  - [Typography](#typography)
  - [Colour Scheme](#colour-scheme)
  - [Responsiveness](#responsiveness)
  - [Images](#images)
- [Features](#features)
  - [Navigation](#navigation)
  - [Footer](#footer)
  - [Hero Section](#hero-section)
  - [Webite Intro - Citizen Briefing Document](#website-intro---citizen-briefing-document)
  - [Main Navigation Grid](#main-navigation-grid)
  - [Testimonials Carousel](#testimonials-carousel)
  - [Newsletter Signup Form](#newsletter-signup-form)
  - [Newsletter Signup Confirmation Page - Join the Broadcast Confirmation](#newsletter-signup-confirmation-page---join-the-broadcast-confirmation)
- [Additional Pages](#additional-pages)
  - [Surveillance Page](#surveillance-page)
  - [Housing Page](#)
- [Technologies Used](#technologies-used)
  - [Languages](#languages)
  - [Libraries & Frameworks](#libraries-&-frameworks)
  - [Tools](#tools)
- [Testing](#testing)
  - [Bugs Fixed](#bugs-fixed)
  - [Responsiveness Tests](#responsiveness-tests)
  - [Code Validation](#code-validation)
    - [HTML](#html)
    - [CSS](#css)
  - [User Story Testing](#user-story-testing)
  - [Feature Testing](#feature-testing)
  - [Accessibility Testing](#accessibility-testing)
  - [Lighthouse Testing](#lighthouse-testing)
  - [Browser Testing](#browser-testing)
- [Deployment](#deployment)
  - [How to Deploy the Project](#how-to-deploy-the-project)
  - [How to Fork the Project](#how-to-fork-the-project)
  - [How to clone the Project](#how-to-clone-the-project)
- [Credits](#credits)

## User Goals
- Navigate the site easily with user-friendly, intuitive structure.
- Engage with content against a clean, non-distracting background.
- Understand Orwellian concepts of surveillance, censorship, and misinformation, and how they relate to today's society.
- Explore Orwellian themes in a creative, humourous, and engaging format.
- Reflect on their own and society's relationship with technology and authority through satire.
- Use the site as a resource for teaching, learning, research, or creative inspiration.
- Appreciate thoughtful design that enhances storytelling and concept delivery.

## User Stories
- As a user, I want to navigate the site with ease so that I can find content without friction or confusion.
- As a user, I want the background to be clean and minimal so I can focus on the content without distractions.
- As a user, I want to understand how Orwell's themes relate to today's society so I can make meaningful connections between fiction and reality.
- As a user, I want to explore Orwell's themes in a humorous and engaging way so that learning feels enjoyable. 
- As a user, I want the site to prompt reflection on my relationship with technology and authority so I can analyse my own reliance from a new perspective in a *light-hearted way*. 
- As a user, I want use the site as a creative teaching or research tool so I can explain or explore *1984* in a different format.
- As a user, I want the design to include thoughtful visuals so I can see how design enhances storytelling and concept delivery.

## Website Goals & Objectives
**Primary Goals:**
  - Create a responsive, accessible, and user-friendly experience.
  - Design consistent layout and reusable components across muliple pages and/or sections.
  - Ensure performance, usability, and mobile responsiveness.
  - Engage users with thought-provoking content and creative visuals.
  - Present Orwellian themes through a modern, satirical lens.
  - Encourage light-hearted reflection on surveillance, censorship, and digital obedience.
  - Showcase front-end development and UX storytelling skills.

**Secondary Goals:**
  - Maintain a tone that educates whilst entertains.
  - Support use in educational or classroom settings.
  - Create a project that demonstrates narrative and technical skills.
  - Keep the site scalable for future additions (e.g. new sections or interactive features).

  ## Wireframes
  To plan the structure and layout of the site, I created fow-fidelity wireframes using **Figma**. My process began with a **mobile-first design**, ensuring responsiveness and usability on smaller screeens before scaling up. I then adapted the layouts for **tablet** and finally for **laptop/desktop** viewports, making design choices that preserve visual hierachy and accessibility across all devices.

  [Mobile wireframes](docs/mobile-wf.png)

  [Tablet wireframes](docs/tablet-wf.png)

  [Laptop wireframes](docs/desktop-wf.png)

  ## Design Choices
  The design of 1984.1 was guided by the project's satirical tone and its central theme: a modern dystopia rooted in everyday London. Each visual choice - from colours and typography to layout and imagery - was made to reinforce the atmosphere of institutional control, passive surveillance, and curated obedience, while ensuring readability and responsiveness across all devices.

  During the development, some initial design elements - particularly images - were changed to better align with the final tone and layout of the site. These updated visuals more effectively support the storytelling and aesthetic goals of the project.

  This section reflects the design decisions currently implemented on the live site and may contiue to evolve through user feedback and ongoing post-launch improvements.

  ### Typography
  **Headings - *Unioca One*** 

  Chosen for its bold, rigid style that echoes the cisual tone of public notices, government signage, and institutional messageing. It reinforces the satirical undertone by mimicking the cold authority of bureaucratic communication.

  **Body Text - *Inter***

  Selected for its clean, modern readability, modern design, and clean geometry. Inter supports the site's long-form content and adapts well across screen sizes, maintaining clarity without visual clutter.

  **Purpose & Performance**

  The combination of Unica One and Inter reflecrs the visual language of public sector materials, aligning with the site's parodty of controlled communication. To ensure performance and reduce load times, fonts are imported using `@import` from \Google Fonts.

  ![Typography Styles](docs/typography.png)

  #### Font Usage Table
  |CSS Name|Font Name|Use Case Description|
  |--------|---------|--------------------|
  |--font-body|Inter|Used for paragraphs, buttons, forms, and navigation links to ensure clarity and consistency.|
  |--font-heading|Unica One|Used for all main headings to evoke insitutional/public signage.|

  ### Colour Scheme
  A limited 5-colour palette was used to create a stark, modernist aesthetic. The colours were chosen to reflect both the physical urban environment of London and the emotional tone of passive control. I used [Coolers](https://coolors.co/) to explore combinations and define a cohesive colour palette.

  ![Colour Scheme](docs/1984-1-colours.png)

  |CSS Variable|Hex Code|Usage Description|
  |------------|--------|-----------------|
  |`--page-bg` |`1E1E1E`  |Background colour of the page|
  |`--primary-text`|`EAEAEA`|Default body text colour|
  |`--cta-text`|`000000`  |Call-to-action text colour; used in buttons and highlighted UI elements|
  |`--link-text`|`5FAFFF` |Standard link colour|
  |`--alerts`|`DC5C50` |Used for warning or error messages and helper text|
  |`--ctas-highlight`|`FFDD2D`|Button background, highlight accents, and hover states for interactive elements|

  ### Responsiveness
  To ensure the site worked effectively across all devices, I followed a **mobile-first approach**, starting with wireframes for small screens and scaling up to tablet and desktop.

  I used **Relume's layout library for inspiration** for designing my wireframes. All layouts were custom built and adapted to fit the tone, content, and style of 1984.1

  ### Images
  The imagery in 1984.1 plays a critical role in reinforcing the site's satirical tone and dystopian message. All images were selected or generated to resemble propaganda posters, government-issued warnings, and comic-style artwork that exaggerates modern anxieties.

  **Design Intent**:
  - **Style**: Stylised, high-contrast illustrations with bold lines and muted or limited colour palettes to evoke feelings of control, surveillance, and psychological strain.
  - **Themes**: Each image aligns with a core theme - such as housing inequality, social isolation, or mass surveillance - and often includes exaggerated or surreal elements to heightn the satire.
  - **Accessibility**: All images include descriptive `alt` text that communicates both the visual content and the satirical intent for screen reader users.
  - **Optimisation**: Images are served in .webp format to balance visual quality and performance, keeping load times minimal across devices.

  This approach ensures the visual content doesn't just decorate the site - it deepens the narrative and experience.

## Features
The **1984.2** website includes a range of features designed to support its satirical tone, reinforce its dystopian narrative, and ensure accessibility across all devices. Each section was deliberately styled to reflect the aesthetic of institutional messaging, urban surveillance, and controlled user experience.

### Responsive Layout
This site uses a responsive grid system powered by Bootstrap 5, with custom media queries to handle layout transitions across mobile, tablet, and desktop breakpoints. Elements stack or align as needed for seamless user navigation.
<details>
<summary>Responsive layout on Mobile, Tablet, and Desktop</summary>

![Mobile Site](docs/mobile-site.png)
![Tablet Site](docs/tablet-site.png)
![Desktop Site](docs/desktop-site.png)
</details>

### Navigation
A sticky top navigation bar ensures users can quickly jump between site sections. It is fully responsive and collapses into a hamburger menu on smaller screens.
<details>
<summary>Sticky responsive navigation bar</summary>

![Mobile Navigation Bar Closed](docs/mobile-navbar.png)

![Mobile Navigation Bar Open](docs/mobile-navbar-open.png)

![Desktop Navigation Bar Open](docs/desktop-navbar.png)
</details>

### Footer
The footer is informative nd functional. It incldes key navigation links, social media icons, legal dislaimers, and a satirical compliance message. Designed to remain visually balanced witht he rest of the layout, it adapts to various screen sizes.
<details>
<summary>Custom responsive footer with compliance message</summary>

![Mobile Footer](docs/mobile-footer.png)
![Desktop Footer](docs/desktop-footer.png)
</details>

### Hero Section
The hero section serves as the site's bold introduction, immediately establishing its satirical tone and dystopian theme. It features a prominent, multi-line heading with a subheading styled as a smaller `<small>` tag, delivering dark humour through phases like *"Now With Targeted Ads!"* Below this, a lead paragraph reinforces the parody with references to modern surveillance culture, setting the stage for the site's narrative. A clear call-to-action button (*"Welcome to London"*) is places beneath the text, styled as a large Bootstrap button that spans the full-width on smaller screens `w-100` and adjusts to auto width on larger ones `w-md-auto` for responsiveness and accessibility. Structurally, the section is built using Bootstrap's grid system: a singlerow aligns the content vertically on mobile and transitions to a two-column ;ayout on larger viewports `col-12` and `col-ld-6`. The right-hand column contains an optimised `.img-fluid` image of a comic-style illustration of London's skyline, in .webp format for responsiveness and performance. The entire hero section is enclosed in a `<header>` element with `bg-dark` and `text-light` classes for high contrast, along with `py-5` padding and `section` for spacing and structural consistency.
<details>
<summary>Hero Section - Mobile & Desktop Screen</summary>

![Hero Section on Mobile Screens](docs/mobile-hero.png)
![Hero Section on Desktop Screens](docs/desktop-hero.png)
</details>

### Website Intro - Citizen Briefing Document
The "Citizen Briefing Document" introduces the site's core satire by delivering a bold narratve hook wrapped in a visually dystopian aesthetic. Built using a full-width Bootstrap card with a `.card-img-overlay`, it overlays centrally aligned content atop a responsive WebP background styled to resemble comic book art. The layout is powered by Flexbox for vertical centring, with structured paragraphs and a stylised heading that escalates in tone toward a strong closing alignment statement. Responsive padding and alignment ensure readability across screen sizes, while `aria-label` enhances accessibility for screen readers. The section maintains consistency with the site's visual language, using sematic HTML and typographics cohesion to deliver a memorable, legible, and technically sound introduction.
<details>
<summary>Citizen Briefing Document - Introduction Section</summary>

![Citizen Briefing on Mobile Screens](docs/mobile-citizen-briefing.png)
![Citizen Briefing on Desktop Screens](docs/desktop-citizen-briefing.png)
</details>

### Main Navigation Grid - Indoctrination Tiles
The Indoctrination Tiles section fatures a responsive 4-card grid biult using Bootstrap's grid system, showcasing satirical content categories - Sureveillance, Housing, Community, and Room 101. Each card pairs a themed icon with a darkly humorous summary and a custom call-to-action link that directs users to the corresponding sections. The layout adapts fluidly: stacking vertically on mobile, forming 2 columns on tablet, and dispklaying as a four-column layout on desktop. Styled with a bold black and yellow palette and consistent typography, the cards reinforce the site's Orwellian theme. The section maintains semantic structure, keyboard accessibility, and contrast compliance for a a fully inclusive user experience. 
<details>
<summary>Indoctrination Tiles - Responsive Grid (Mobile, Tablet, Desktop)</summary>

![Indoctrination Tiles on Mobile](docs/mobile-nav-tiles.png)
![Indoctrination Tiles on Tablet](docs/tablet-nav-tiles.png)
![Indoctrination Tiles on Desktop](docs/desktop-nav-tiles.png)
</details>

### Testimonials Carousel
The testimonial carousel features a rotating set of fictional citizen quotes built using the Bootstrap 5 carousel component, parodying state-approved propaganda with over-the-top priase for surveillance culture. Each testimonial is housed in a centred `<blockquote>` styled for contrast and emphasis, accompanied by a mock citizen ID as metadata. The section maintains visual cohesion with the site's dystopian branding trough consistent typography and colour use. The layout is fully responsive, with spacing and alignment adapting smoothly across devices via Bootstrap's grid and utility classes, delivering dynamic satire iin a format that mimics official endorsement.
<details>
<summary>Indoctrination Tiles - Responsive Grid (Mobile, Tablet, Desktop)</summary>

![Testimonials Carousel on Mobile](docs/mobile-testimonials.png)
![Testimonials Carousel on Desktop](docs/desktop-testimonials.png)
</details>

### Forms - Join the Broadcast (newsletter) & Report a Violation
The site features two custom-built forms that parody civic participation: a newsletter subscription card and a "Report a Violation" complaint portal. The **Newsletter Signup** form is styled in a dystopian black/yellow palette and include satirical prompts like "we promise not to sell your data to *more* corporations than necessary." Built with a Bootstrap structure and enhanced with semantic HTML, it includes accessible labels, aria-describedby helper texr, and responsive spacing. The **Report a Violation** form mimics government reporting tools, complete with stylised radio buttons, required fields, and themed helper coopy. Both forms are frontend-only, keyboard accessible, visually consistent with the site's Orwellian tone, and fully responsive across screen sizes. 
<details>
<summary>Forms- Join the Broadcast & Report a Violation</summary>

![Join the Broadcast on Mobile](docs/mobile-newsletter-signup.png)
![Join the Broadcast on Desktop](docs/desktop-newsletter-signup.png)
![Report a Violation on Mobile](docs/mobile-report-a-violation.png)
![Report a Violation on Desktop](docs/desktop-report-a-violation.png)
</details>

### Newsletter Signup Confirmation Page - Join the Broadcast Confirmation
Instead of using a modal, a standalone conformation page reinforces the site's dystopian rheme with a formal Ministry-style announcement. Upon subscribing, users are redirected to a responsive layout built with Bootstrap's grid and utility classes, where bold headings and satirical phrases mock automated state messaging. The page maintains accessibility via semantic HTML and ARIA attributes, and includes a persistent navigation bar and footer components for visual continuity. Styled with the same dark, high-contrast palette, it continues the tone of dark humour and institutional parody.
<details>
<summary>Broadcast Confirmation - Subscription Complete</summary>

![Broadcast Confirmation Page on Mobile](docs/mobile-broadcast-confirmation.png)
![Broadcast Confirmation Page on Desktop](docs/mobile-broadcast-confirmation.png)
</details>

### Report a Violation - Confirmation Page
After submitting a violation, users are redirected to a Ministry-branded confirmation page that continues the site's satirical voice with mock government language and absurd acknoledgements such as "Silently judged" and "Used in a future training presentation." Built using Bootstrap's grid and utility classes, the layout is fully responsive and ensures a seamless visual and structural transition from the main form page. Custom icons, accessible structure, and dark humour combine to deliver a memorable UX. The page includes semantically structured HTML, a consitent footer and navigation, and high-contrast styling for compliance with accessibility standards - all designed to reinforce the parody of civic surveillance culture.
<details>
<summary>Report a Violation - Form Sent Confirmation</summary>

![Report a Violation Confirmation Page on Mobile](docs/mobile-report-a-violation-confirmation.png)
![Report a Violation Confirmation Page on Desktop](docs/desktop-report-a-violation-confirmation.png)
</details>

### 404 Error Page
The 404 error page delivers a satirical response to navigation failure, styled to resemble a government denial. A full-width graphic of static-filled monitors anchors the visual theme, with a bold red "404" message and comic-styling. The layout is fully responsive using Bootstrap's grid and spacing utilities, ensuring a consistent experience across devices. Clear headings and dual call-to-action buttons invite the user to either return to the homepage or report the missing content as a violation - reinforcing the site's ongoing narrative of bureaucratic contel. The page includes semantic HTML, accessible markup, and reuses shared navigation and footer components to maintain continuity with the rest of the site.
<details>
<summary>404 Page - Page Not Found</summary>

![404 Error Page on Mobile](docs/mobile-404-page.png)
![404 Error Page on Desktop](docs/desktop-404-page.png)
</details>

### Accessibility
The 1984.1 website was developed with accessibility in mind to ensure it remains inclusive and usable for all visitors, including those relying on assistive technologies. Key considerations include:
- **Semantic HTML**: All sections use meaningful tags`<header>`, `<main>`, `<section>`, `<nav>`, etc. to enhance document structure and screen reader navigation.
- **ARIA attributes**: `aria-label`, `aria-describedby`, and `aria-labeledby` have been used where appropiate to provide additional context to assistive technologies, especially in interactive and image-based areas.
- **Keyboard Navigation**: All interactive elements - including buttons, navigation links, and forms - are fully operable via keyboard alone, supporting tabbing and focus states.
- **Colour Contrast**: The site uses a high-contrast colour scheme (yellow on black or light grey on dark backgrounds) to meet or exceed WCAG AA contrast ratios for text and interactive elements.
- **Focus Styles**: Custom focus styles have been implemented to ensure users can clearly identify which element is in focus during navigation.
- **Responsive Layouts**: Content adjusts appropiatey across screen sizes without requiring horizontal scrolling or loss of functionality.
- **Alt Text and Descriptions**: All images include descriptive `alt` text or `aria-labels`, particularly important for satire-based graphics that communicate key meaning.

Accessibiity testing was performed using [Lighthouse](https://developer.chrome.com/docs/lighthouse/overview/), keyboard-only navigation, and screen reader checks to verify usability across various user needs.

## Technologies Used
### Languages
- HTML5
- CSS3

### Libraries & Frameworks
- Bootstrap
- Font Awesome 6
- Google Fonts

### Tools
- Figma
- Visual Studio Code
- Git
- GitHub
- Lighthouse
- [Sora](https://sora.chatgpt.com/explore): for image generation
- [Squoosh](https://squoosh.app): for image optimisation
- [Tailwind Image Alt Text Generator](https://www.tailwindapp.com/marketing/tools/image-alt-text-generator)
- [Am I Responsive](https://ui.dev/amiresponsive)
- [Responsive Design Checker](https://responsivedesignchecker.com)

## Testing
### Bugs Fixed

|Bug ID|Issue|Location|Status|Solution|
|------|-----|--------|------|--------|
|001|"Report a Violation" link on scrolling to the correct section|Navigation Button|Fixed|Checked the href value and corrected the target ID.|
|002|All navbar and footer links on "Join the Broadcast" page|`join-the-broadcast.html`|Fixed|Updated all anchor links to match correct section IDs.|
|003|"Submit Another Report" button links to homepage instead of the form|Confirmation Page|Fixed|Update button path ot point to the correct section.|
|004|Multiple `<h1>` tags on homepage|index.html|Fixed| Changed extra `<h1>` elements to `<h2>` for proper hierachy.|
|005|Low contrast on small yellow and red text|Throughout the site|Fixed|Updated colour classes to use body text colour for better accessibility.|
|006|Image performance issues flagged by Lighthouse|Hero and section images|Fixed|Resized images, used srcset, and `<picture>` with WebP + preload optimisations.|
|007|Broken url|index.html footer|Fixed|Updated href values to point to the correct section IDs.|
|008|Missing `preload` for hero image|`<head>` in `index.html`|Fixed|Added `<link rel="preload">` for the hero image|
|009|Render-blocking Google Fonts|`<head>`|Fixed|Moved Google fonts from `<link>` in `<head> to `@import` in CSS|

### Responsiveness Tests
To ensure optimal performance and usablitlity  across devices, i tested the 1984.1 website using a **mobile-first approach**. Tests were performed in Google' Chrome's DevTools and Safari, and Firefox and Edge using simulated devices. I also verified responsiveness using **Am I Responsive**, **Responsive Design Checker**, and **actual mobile devices** when possible.

Throughout testing, I checked for consistency in:
- Navigation functionality and placement
- Text readability and layout alignment
- Image responsiveness and scaling
- Section spacing and stacking behaviour
- Interactive elements and scroll links

All breakpoints were assessed for smooth layout flow, clear typography, and uninterrupted user experience. Key layout adjustments and bug fixes were applied where necessary.

**Responsive Design Test Results**
|Screen Size|Device Tested|Navigation|Element Alignment|Content Layout|Functionality|Notes|
|-----------|-------------|----------|-----------------|--------------|-------------|-----|
|sm|iPhone SE (375px)|Good|Good|Good|Good|Adjusted hero font size and CTA spacing|
|sm|Pixel 5 (393px)|Good|Good|Good|Good| |
|sm|iPhone 13 Mini (390px)|Good|Good|Good|Good| |
|md|iPad Mini (768px)|Good|Good|Good|Good| |
|md|Galaxy Tab S7(800px)|Good|Good|Good|Good| |
|md|iPad Air (820px)|Good|Good|Good|Good| |
|lg|iPad Pro (1024px)|Good|Good|Good|Good|Header spacing verified|
|xl|Macbook Air (1280px)|Good|Good|Good|Good| |
xl|Desktop Monito (1440px)|Good|Good|Good|Good|All layout sections scale correctly without overflow or distortion|

### Code Validation
As part of the final checks for this project, both HTML and CSS files were validated using W3C's online validation tools.The following results were recorded:

#### HTML

|File|Tool Used|Outcome|
|----|---------|-------|
|`index.html`|[W3C Markup Validator](https://validator.w3.org)|Pass|
|`404.html`|[W3C Markup Validator](https://validator.w3.org)|Pass|
|`form-confirmation.html`|[W3C Markup Validator](https://validator.w3.org)|Pass|
|`join-the-broadcast-confirmation.html`|[W3C Markup Validator](https://validator.w3.org)|Pass|

<details>
<summary>HTML Validation Reports (All Pages)</summary>

![index.html](docs/index-html-checker.png)
![404.html](docs/404-html-checker.png)
![form-confirmation.html](docs/form-confirmation-html-checker.png)
![join-the-broadcast-confirmation.html](docs/join-the-broadcast-confirmation-html-checker.png)
</details>

#### CSS

|File|Tool Used|Outcome|
|----|---------|-------|
|style.css|[W3C css validator](https://jigsaw.w3.org/css-validator/)|Pass|

<details>
<summary>CSS Validation Report</summary>

![style.css](docs/css-checker.png)
</details>
<br>
**Note**: The following *warnings* were flagged by the CSS calidator:
- **Line 1**: Imported style sheets are not checked in direct input and file upload modes.
- **Lines 24, 60, 162, 170, 455**: "Due to their dynamic nature, CSS variables are not currently statically checked."

These warnings are for **reference only**, and **do not indicate errors**. All core CSS was validated.

### User Story Testing
|User Story|Result|
|----------|------|
|As a user, I want to navigate the site with ease so that I can find content without friction or confusion.|Navigation bar is sticky, links scroll smoothly to sections, intuitive button renaming.|
|As a user, I want the background to be clean and minimal so I can focus on the content without distractions.|Background is a dark, neutral colour with high contrast text and minimal visual clutter, ensuring content remans the focal point.|
|As a user, I want to understand how Orwell’s themes relate to today’s society so I can make meaningful connections between fiction and reality.|Satirical copy throughout the site connects Orwellian ideas to modern life, especially in surveillance and housing sections.|
|As a user, I want to explore Orwell’s themes in a humorous and engaging way so that learning feels enjoyable.|Satirical tone maintained across al copy, icons, labels, and CTAs.|
|As a user, I want the site to prompt reflection on my relationship with technology and authority so I can analyse my own reliance from a new perspective in a light-hearted way.|Infographics and examples in Surveillance section highlight tech overreach in a humorous way.|
|As a user, I want use the site as a creative teaching or research tool so I can explain or explore 1984 in a different format.|Site is structured into digestible secions, accessible language, and responsive design for presentation.|
|As a user, I want the design to include thoughtful visuals so I can see how design enhances storytelling and concept delivery.|Each section is paired with a stylised illustration, matching the theme and tone of the content.| 

#### Feature Testing
To ensure that all core interactive and visual features of the website function as intended, I conducted manual testing across devices, screen sizes, and user interaction paths. Each feature was tested for expected behaviou, responsiveness, and accessibility.

The table below outlines the features tested, along with a description and the steps taken to verify their functionality.

|Feature|Description|Steps|Expected Outcome|
|-------|-----------|-----|----------------|
|Navigation Bar Toggle|Hamburger menu toggles navigation links on smaller screens|Click hamburger icon on mobile viewport|Menu opens/closes correctly, links visible|
|Hero Button|Scrolls to main intro section|Click "Welcome to London" CTA|Page scrolls smmothly ro #intro-section|
|Indoctrination Tiles|Each card links to a relevant section|Click on tile links|Page scrolls smoothly to relevant content section|
|Testimonial Carousel|Slides through citizen testimonials|Click arrows or wait for autoplay|Slides rotate with animations and accessible controls|
|Newsletter Signup|Email form collects user input and redirects to confirmation page|Enter email, click "Join the Broadcast"|Redirects to confirmation page|
|Report a Violation Form|User submits form to simulate reporting a violation|Fill out all form fields and submit|Confirmation page loads with mock case ID and message|
|Responsive Layout|Site layout adapts to different screen sizes|View site on various devices or use browser dev tools|Layout adjusts appropiately across breakpoints|
|Dark Theme and Colour Contrast|Text and UI elements have sufficient contrast on dark background|Visually inspect site across sctions| All text meets WCAG contrast standards|
|Image Responsiveness|Images change size and resolution based on screen| Resize browser or inspect image sources|Appropiate image resolution loaded, layout maintained|
|Back to Top Functionality|Return to top when navigating long pages|Use anchor links or scroll manually|Focus returns to top smoothly|

#### Accessibility Testing
This project was tested using [WAVE - Web Accessibility Evaluation Tool](https://wave.webaim.org/)

**Summary:**
- 0 accessibility errors
- 2 alerts noted (see below)

<details>
<summary>WAVE Report</summary>

![WAVE report showing 0 errors and 2 alerts](docs/wave.png)
</details>

**Alert Details**
1. **Redundant Link**
A logo and a navigation link both lead to the homepage. This is intentional for user clarity and branding.
2. **Noscript Element**
`<noscript>` tag present for when JavaSCript is disabled, including intentionally.

Additionally, all website colour combinations were tested for WCAG 2.1 AA comliance using [WebAIM's Contrast Checker](https://webaim.org/resources/contrastchecker/). The following combinations were used throughout the site and all passed for normal text, large text, and non-text elements.

|Combination|Foreground|Backgroud|Ratio|Result|
|-----------|----------|---------|-----|------|
|#FFFFFF on #1E1E1E|White|Dark Grey|16.67:1|Pass|
|#EAEAEA on #1E1E1E|Pale Grey|Dark Grey|13.85:1|Pass|
|#5FAFFF on #000000|Sky Blue|Black|9.06:1|Pass|
|#EAEAEA on #000000|Pale Grey|Black|17.45:1|Pass|
|#FFDD2d on #000000|Yellow|Black|15.63:1|

<details>
<summary>View Screenshots</summary>

![#FFFFFF on #1E1E1E -16.67:1](docs/contrast-eaeaea-1e1e1e.png)
![#EAEAEA on #1E1E1E – 13.85:1](docs/contrast-ffffff-1e1e1e.png)
![#5FAFFF on #000000 – 9.06:1](docs/contrast-5fafff-000000.png)
![#EAEAEA on #000000 – 17.45:1](docs/contrast-eaeaea-000000.png)
![#FFDD2D on #000000 – 15.63:1](docs/contrast-ffdd2d-000000.png)
</details>

#### Lighthouse Testing
The site was tested using [Chrome Dev Tools Lighthouse](https://developer.chrome.com/docs/devtools/) to evaluate the overall quality and performance of the site. The report evaluates:
  - **Performance** - how quickly the site loads and responds
  - **Accessibility** - how usable the site is for people using assistive technologies
  - **Best Practices** - adherence to modern development standards
  - **SEO** - whether the site is optimised for search engines

<details>
<summary>View Lighthouse Reports</summary>

![Mobile Report](docs/lighthouse-report-mobile.png)
![Desktop Report](docs/lighthouse-report-desktop.png)
</details>

#### Browser Testing
The site was tested for browser compatibity and performance across a variety of platform using both [BrowserStack](https://www.browserstack.com/live) and manually.

Manual Testing:<br>
The site was manually tested on the following real devices:
- Chrome (Desktop - macOS)
- Safari (Desktop - macOS)
- Safari (iPad - iPadOS)
- Safari (iPhone iOS)
No layout shifts, functionality errors, or rendering issues were observed on any tested device.

BrowserStack Testing:<br>
Using BrowserTestig, the site was tested on Mozilla Firefox and Microsoft Edge.
  Summary of Resuts:
  - All layouts rendered consistently across browsers.
  - Navigation, buttons, and form elements all behaved as expected.
  - No display or functionality issues were encountered.
  - Fonts, spacing, and responsive behavour remained consistent.

The website passed visual and functional checks across all major modern browsers.

## Deployment
### How to Deploy the Project
1984.1 was deployed early in the process to GitHub pages via the following steps:
  - Navigate to the repository on GitHub and click on **Settings**.
  - In the side navigation, select **Pages**.
  - In the **None** dropdown,choose **Main**.
  - Click o nthe **Save** button.
  - The website is now live at https://creatvie-introvert.github.io/1984-1/index.html.

*Any changes required to the website, can be made, commited, and pushed to GitHub.* 

### How to Fork the Project
Forking the GitHub repository allows you to create a duplicate of a local repository. This is done so that modifications to the copy can be performed without compromising the original repository.
  - Log in to GitHub
  - Locate the repository
  - Click to open it
  - The fork button is located on the right side of the repository menu. Click fork to copy the repository to your GitHub account.

### How to clone the Project
To clone the project:
  - Log in to GitHub
  - Navigate to the main page of the repository and click Code.
  - Copy the URL for the repository
  - Open your local IDE
  - Change the current working directory to the location where you want to clone the directory
  - Type git clone, and paste the URL you copied earlier
  - Press Enter to create your local clone/copy.
## Credits