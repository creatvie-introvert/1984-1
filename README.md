# 1984.1
### 🔗 Live Site
[view the deplyed site here](#)

**1984.1** is a satirical website, that explores the relevance of George Orwell's *1984* in today's society, specifically through the lens of modern-day London. It guides users through themes such as surveillance, propaganda, and thought control using humour, visual design and interactive storytelling.

The site is designed for users who want a thought-provoking yet entertaining way to reflect on how dystopian concepts have been repackaged as everyday conveniences in the digital age. It encourages critical thinking about technology, privacy, and media - without taking itself too seriously.

### 🖼️ Site Preview
> _add a screenshot of the site showing desktop, tablet and mobile views_

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
  - > _add more features here_
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

  [Mobile wireframes](assets/docs/mobile-wf.png)

  [Tablet wireframes](assets/docs/tablet-wf.png)

  [Laptop wireframes](assets/docs/desktop-wf.png)

  ## Design Choices
  The design 1984.1 was guided by the project's satirica tone and its central theme: a modern dystopia rooted in everyday London. Each visual choice - from colours and typography to layout and imagery - was made to reinforce the atmosphere of institutional control, passive surveillance, and curated obedience, while ensuring readability and responsive ness across aall devices.

  These choices reflect the design intent at the start of development and may be refined further based on how they perform on the live site.

  ### Typography
  **Headings:** *Unioca One* - chosen for its rigid, institutional feel, evoking the aesthetic of public notices and government-issued warnings.

  **Body Text:** *Inter* - selected for its clean, modern readability and versatility across devices, supporting long-form critical copy without distraction.

  The typography aims to reflect the visual language of public sector communication, reinforcing the site's satirical tone.

  To optimise performance:
  - Fonts are loaded using a `<link>` in the HTML `<head>` instead of `@import`, which improves page rendering speed.
  - Added `rel="Preconnect"` directives for Google Fonts domains to reduce DNS lookup time nd latency during font loading.

  ![Typography Styles](assets/docs/typography.png)


  ### Colour Scheme
  A limited 5-colour palette was used to create a stark, modernist aesthetic. The colours were chosen to reflect both the physical urban environment of London and the emotional tone of passive control. I used [Coolers](https://coolors.co/) to explore combinations and define a cohesive colour palette.

  ![Colour Scheme](assets/docs/colours.png)


  ### Responsiveness
  To ensure the site worked effectively across all devices, I followed a **mobile-first approach**, starting with wireframes for small screens and scaling up to tablet and desktop.

  I used **Relume's layout library for inspiration** for designing my wireframes. All layouts were custom built and adapted to fit the tone, content, and style of 1984.1

  ### Images
  > _add image design choices_

## Features
### Navigation
### Footer

> _add more features here_

## Technologies Used
### Languages
### Libraries & Frameworks
### Tools

## Testing
### Bugs Fixed
### Responsiveness Tests
### Code Validation
#### HTML
#### CSS
### User Story Testing
#### Feature Testing
#### Accessibility Testing
#### Lighthouse Testing
Performance testing was carried out using Lighthouse in Chrome DevTools.

**Lighthouse Issue Tracker:**
|Issue Identified          |Solution Implemented                                                        |
|--------------------------|----------------------------------------------------------------------------|
|Fonts loaded via `@import`|Switched to `<link>` in head for faster loading and added `Preconnect` links|
|Image not properly sized(logo)|Resized logo to 154px, compressed with squoosh.app, and updated image source|

#### Browser Testing
### Deployment
#### How to Deploy the Project
#### How to Fork the Project
#### How to clone the Project
## Credits