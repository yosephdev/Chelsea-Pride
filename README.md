# Chelsea Pride Website

# Goal for this Project

Welcome to Chelsea Pride, a vibrant hub for Chelsea Football Club enthusiasts. This website is a dedicated space for fans of all ages, offering the latest in club news, player insights, and historical retrospectives.

This site facilitates easy interaction with the club and fellow fans through social media and a direct contact form, making it simple and accessible for everyone to stay connected with the Chelsea community.

# Table of Contents

- [Chelsea Pride Website](#chelsea-pride-website)
- [Goal for this Project](#goal-for-this-project)
- [Table of Contents](#table-of-contents)
- [UX](#ux)
- [User Goals](#user-goals)
- [User Stories](#user-stories)
- [Site Owner's Goals](#site-owners-goals)
- [Requirements](#requirements)
- [Expectations](#expectations)
- [Design Choices](#design-choices)
  - [Fonts](#fonts)
  - [Icons](#icons)
  - [Colors](#colors)
- [Structure](#structure)
  - [Mobile-First Design](#mobile-first-design)
  - [Responsive Breakpoints](#responsive-breakpoints)
- [Wireframes](#wireframes)
    - [Desktop Wireframe](#desktop-wireframe)
    - [Tablet Wireframe](#tablet-wireframe)
    - [Phone Wireframe](#phone-wireframe)
- [Features](#features)
- [Planned Features for Chelsea Pride](#planned-features-for-chelsea-pride)
  - [Proposed Features](#proposed-features)
  - [Existing Features](#existing-features)
    - [Navigation Bar](#navigation-bar)
      - [Desktop (\>=992px)](#desktop-992px)
      - [Small devices (\<992px)](#small-devices-992px)
      - [Enhancements and Responsive Behavior](#enhancements-and-responsive-behavior)
  - [Main Banner with Site Title](#main-banner-with-site-title)
    - [Overview](#overview)
    - [Design and Features](#design-and-features)
    - [HTML and CSS Implementation](#html-and-css-implementation)
  - [Featured Content Section](#featured-content-section)
    - [Overview](#overview-1)
    - [Design and Implementation](#design-and-implementation)
      - [HTML and CSS Construction](#html-and-css-construction)
  - [Latest News Section](#latest-news-section)
    - [Overview](#overview-2)
    - [Design and Implementation](#design-and-implementation-1)
      - [HTML and CSS Construction](#html-and-css-construction-1)
    - [Club Timeline](#club-timeline)
      - [Design and Features](#design-and-features-1)
    - [Legendary Figures](#legendary-figures)
      - [Design and Features](#design-and-features-2)
    - [Memorable Matches](#memorable-matches)
      - [Design and Features](#design-and-features-3)
    - [Fan Zone](#fan-zone)
      - [Design and Features](#design-and-features-4)
      - [Interactive and Responsive Design](#interactive-and-responsive-design)
    - [Contact Us](#contact-us)
      - [Design and Features](#design-and-features-5)
      - [User Interaction and Usability](#user-interaction-and-usability)
    - [Footer](#footer)
      - [Design and Features](#design-and-features-6)
      - [User Experience and Legal Compliance](#user-experience-and-legal-compliance)
  - [Features to be Implemented](#features-to-be-implemented)
  - [Technologies Used](#technologies-used)
  - [Languages](#languages)
  - [Libraries \& Frameworks](#libraries--frameworks)
  - [Tools](#tools)
- [Testing](#testing)
  - [Encountered Issues](#encountered-issues)
- [Deployment](#deployment)
- [Credits](#credits)

# UX

# User Goals

- Access the latest Chelsea FC news, match results, and player updates.
- Engage with other Chelsea supporters and participate in fan discussions.
- Learn about Chelsea FC's history and legendary players.

# User Stories

- I want up-to-date match results and analyses to follow the team's performance.  
- I need to learn about the club's history to feel more connected.  
- I wish to engage in discussions and polls with fellow fans.

# Site Owner's Goals

- Provide all-inclusive information on Chelsea FC, from news to history.  
- Create a space for fans to connect and share their passion.
- Maintain an intuitive, accessible website for all fans.

# Requirements

- Regularly update the site with the latest Chelsea FC news and match info.
- Include interactive elements like forums and polls.
- Feature a section dedicated to the club's rich history.

# Expectations

- Users expect an interactive experience with fresh, engaging content.
- The site should be a trusted source for accurate Chelsea FC information.
- Ensure the website is user-friendly and accessible across devices.

[Back to Top](#table-of-contents)

# Design Choices

## Fonts

For "Chelsea Pride," I have chosen distinct and complementary fonts from Google Fonts to enhance the website's readability and aesthetic appeal.

- **Main Text: Lato** - [Lato](https://fonts.google.com/ "Google Fonts") is a sans-serif font known for its clarity and modern feel. It provides a clean, approachable look, making it perfect for the main content, where legibility is key.

- **Headers and Navigation Bar: Raleway** - To create a clear distinction between the main text and headers, I've selected [Raleway](https://fonts.google.com/ "Google Fonts"). This font, with its elegant and slightly more stylized characters, complements Lato while ensuring that headers and navigation elements are noticeable and appealing.

## Icons

The website will incorporate icons from the [Font Awesome library](https://fontawesome.com/ "Font Awesome") Font Awesome library. These icons will be used intuitively, ensuring they are self-explanatory. Key areas for their use include social media links, contact links, and a hamburger menu icon for navigation on mobile devices. All icons will be styled to align with the overall design of the website.

## Colors

The color palette for Chelsea Pride has been carefully selected to align with Chelsea FC's branding and to ensure optimal contrast and visual appeal. The colors were chosen using [Colors.co](https://colors.co/ "Colors"), a tool that helps generate harmonious color schemes.

![Colour Palette](wireframes/color-palette.png)

- **#034694 (Chelsea Blue)**: This vibrant shade of blue is synonymous with Chelsea FC and is used for headers and other key interface elements, providing a strong visual identity that fans can immediately connect with.

- **#C0C0C0 (Slate Grey)**: Used for secondary elements such as borders, buttons, and icon backgrounds, this color offers a modern and sophisticated look that complements the primary Chelsea Blue.

- **#F5F5F5 (Off-White)**: Serving as the background color for the website, this light grey provides a neutral canvas that enhances content visibility while being easy on the eyes, ensuring a comfortable reading experience.

- **#383838 (Dark Grey)**: This color is used for the main body text. It's a softer alternative to black that provides excellent readability against the off-white background without the harsh contrast that pure black can sometimes create.

- **#D4AF37 (Metallic Gold)**: This accent color is used for highlighting important elements such as active menu items and call-to-action buttons. It adds a touch of sophistication and highlights areas of importance, drawing the user's attention effectively.

Each color has been chosen not only for its aesthetic value but also for its functionality and ease of use, ensuring that the website is accessible and appealing to all users.

# Structure

The website will be developed with a 'mobile-first' approach, prioritizing optimization for smaller screens before scaling up to larger devices. This approach aligns with modern web design practices, ensuring a seamless user experience across all devices.

## Mobile-First Design

- **Base Size**: The development will start with styling for the iPhone 5/SE, which represents one of the smallest screen sizes (320px) commonly in use. This ensures that the design remains functional and visually appealing on smaller screens.

## Responsive Breakpoints

Responsive breakpoints will be defined based on the updated [Bootstrap](https://getbootstrap.com/docs/5.0/layout/breakpoints/) Bootstrap breakpoints, which are widely recognized and align with contemporary device standards. These breakpoints allow the layout to adapt dynamically to different screen sizes, ensuring optimal readability and usability.

| Screen Size | Breakpoint |
|-------------|------------|
| x-small     | <576px     |
| small       | ≥576px     |
| medium      | ≥768px     |
| large       | ≥992px     |
| x-large     | ≥1200px    |
| xx-large    | ≥1400px    |

[Back to Top](#table-of-contents)

# Wireframes

For "Chelsea Pride," I utilized Balsamiq to create the wireframes. The process began with designing the mobile version, ensuring that the layout and content are optimized for smaller screens. Following the mobile-first approach, the design was then scaled up to accommodate tablet and desktop views.

Given the goal to provide concise yet impactful information to the user, the website is structured as a single-page layout. This design choice facilitates a smooth user journey, allowing visitors to seamlessly scroll through content and easily reach the contact form and club details. The navigation bar also provides direct access to different sections for enhanced user experience.

Below are the wireframes for "Chelsea Pride" across different devices:

### [Desktop Wireframe](wireframes/wireframe-Desktop.png "Desktop wireframe")

### [Tablet Wireframe](wireframes/wireframe-Tablet.png "Tablet wireframe")

### [Phone Wireframe](wireframes/wireframe-phnne.png "Phone wireframe")

[Back to Top](#table-of-contents)

# Features

# Planned Features for Chelsea Pride

The following features are proposed for development in the Chelsea Pride website. Each feature will be implemented systematically, with commits corresponding to the completion of each task.

## Proposed Features

1. **Responsive Navbar**: Design and implement a navigation bar with links to different sections (News & Updates, Team & History, Fan Zone, Contact Us), enabling smooth scrolling and easy navigation within the single-page layout.

2. **News & Updates Section**: Create a section for regularly updated content providing the latest Chelsea FC news, match updates, and club announcements.

3. **Team & History Section**: Develop a section showcasing the Chelsea team and club history, including player profiles and historical achievements.

4. **Fan Zone**: Implement an interactive area for fan engagement, featuring discussions, polls, and user-generated content.

5. **Contact Us Section**: Include a contact form and social media links for easy communication with the site administrators or the club.

6. **Mobile-First Design**: Ensure the website is optimized for mobile devices, providing a seamless experience on smartphones and tablets.

7. **Dynamic Content Display**: Integrate multimedia elements like images, videos, and live social media feeds for a visually engaging user experience.

8. **Interactive Elements**: Add polls, quizzes, and clickable news items to enhance user interaction and engagement.

9. **Accessibility Features**: Design the website with accessibility in mind, using high-contrast colors and readable fonts to cater to all users.

10. **Footer Section**: Design a footer containing additional navigation links, copyright information, and other essential details.

Each feature will be developed in stages, with regular commits to track progress and ensure quality.

## Existing Features

### Navigation Bar

The navigation bar has been thoughtfully designed to be fully responsive, accommodating various screen sizes with ease. It includes essential links for easy navigation throughout the site and prominently features the Chelsea Pride logo, which also serves as a clickable link to return to the homepage.

#### Desktop (>=992px)

![Navigation Bar](wireframes/nav-bar-desktop.png)

- The navigation bar spans the full width of the screen on desktop devices, making all links (News & Updates, Team & History, Fan Zone, Contact Us) clearly visible and accessible. This arrangement ensures straightforward and intuitive navigation for end users.
- Hover effects have been incorporated to visually indicate which link the user is hovering over, highlighted by a change in text color and an underline effect.
  
![Navigation Bar on Hover](wireframes/nav-bar-hover.png)
  
- A distinct visual change in text color upon clicking provides feedback to the user, confirming their selection.

![Navigation Bar on Focus](wireframes/nav-bar-focus.png)

#### Small devices (<992px)

![Navigation Bar on Small Devices](wireframes/nav-bar-small.png)

- On smaller screens, the navigation bar adapts to a hamburger menu style to ensure usability is maintained. This compact form factor preserves screen real estate while still providing easy access to all navigation links.
  
![Navigation Bar Expanded on Small Devices](wireframes/nav-bar-small-expanded.png)
  
- Tapping the hamburger icon reveals the full menu, presenting the same essential navigation links as on larger screens but in a vertical layout, optimized for touch interaction.

#### Enhancements and Responsive Behavior

- **Responsive Design**: The navigation bar's responsiveness is meticulously crafted, providing a seamless transition between different device sizes.
- **Font Awesome Icons**: The integration of Font Awesome icons, specifically for social media links, augments the navigation bar's functionality and aesthetic appeal.
- **Hover and Focus Effects**: Enhanced hover and focus effects on the desktop version improve the user's interactive experience, making navigation intuitive and visually engaging.
- **Font Size Adjustments**: Targeted font size adjustments for medium screens (between 768px and 991px) enhance readability and ensure a balanced appearance across devices.
- **Layout Optimization**: The stacking issue of menu items on tablet and desktop views has been resolved, ensuring a horizontal and evenly spaced layout.

The revamped navigation bar significantly elevates the usability and visual appeal of the Chelsea Pride website, aligning with contemporary web design standards and ensuring an engaging user experience across all devices.

[Back to Top](#table-of-contents)

## Main Banner with Site Title

### Overview

The Main Banner is a prominent feature at the top of the Chelsea Pride website, immediately capturing the visitor's attention with its striking design and the prominent display of the site title, "Chelsea Pride: The Heart of Chelsea Football Club."

### Design and Features

- **Striking Visual Presentation**: The Main Banner is designed to be visually striking, making a strong first impression as soon as visitors land on the website.

- **Site Title**: The banner prominently features the site title "Chelsea Pride: The Heart of Chelsea Football Club" in large, readable text. This not only serves as an introduction to the site but also reinforces the website's identity and purpose.

- **Responsive Design**: The banner is fully responsive, ensuring that it looks great and remains functional on devices of all sizes, from desktops to mobile phones.

- **Styling Consistency**: The design of the banner is consistent with the overall Chelsea FC theme, using the club's color palette and typography to create a cohesive look.

### HTML and CSS Implementation

- **Semantic HTML**: The banner is implemented using semantic HTML, with a `<div>` element classed as `main-banner` encapsulating an `<h1>` tag for the site title. This ensures proper structuring and accessibility.

- **CSS Styling**: The banner's CSS styling is carefully crafted to align with the aesthetic of the Chelsea Pride website, utilizing the Chelsea FC color palette and modern typography for maximum impact.

```html
<!-- Main Banner with Site Title -->
<div class="main-banner">
    <h1>Chelsea Pride: The Heart of Chelsea Football Club</h1>
</div>
```

![Landing Page](wireframes/landing-page.png)

[Back to Top](#table-of-contents)

## Featured Content Section

### Overview

This section serves as a focal point for displaying the latest club news, match highlights, and special features in an engaging and visually appealing manner.

### Design and Implementation

#### HTML and CSS Construction

- **Semantic HTML**: I used semantic HTML5 elements to ensure better content organization and accessibility, creating a structured and SEO-friendly layout.
  
- **Responsive Design**: The section was built with a responsive design, enabling seamless display and interaction across various devices, from desktops to mobile phones.

- **Chelsea FC Color Palette**: The CSS styling is crafted to align with the Chelsea FC color palette, enhancing the section's visual identity and appeal. Key colors include:
  - Chelsea Blue (#034694) for headers and key interface elements.
  - Slate Grey (#C0C0C0) for secondary elements such as borders and buttons.
  - Off-White (#F5F5F5) as the background color.
  - Dark Grey (#383838) for the main body text.
  - Metallic Gold (#D4AF37) for accentuating important elements.

- **Modern Typography**: Google Fonts 'Lato' and 'Raleway' were selected to improve the overall readability and aesthetic of the content.

- **Interactive Elements**: Interactive elements like hover effects were incorporated to enhance user engagement and make navigation within the section intuitive and visually engaging.

![Landing Page](wireframes/feature-page.png)

[Back to Top](#table-of-contents)

## Latest News Section

### Overview

The "Latest News" section is designed to be the hub for all the current and significant happenings related to Chelsea Football Club. It serves as an essential destination for fans to stay updated with the latest club news, managerial announcements, and player updates.

### Design and Implementation

#### HTML and CSS Construction

- **Semantic HTML**: This section was structured using semantic HTML5 elements to enhance content organization and accessibility. The implementation of structured markup ensures a SEO-friendly layout.
  
- **Responsive Design**: The "Latest News" section boasts a responsive design, facilitating seamless display and interaction across a range of devices, from mobile phones to desktops.

- **Chelsea FC Color Palette**: The CSS styling aligns with the Chelsea FC color palette, reinforcing the section's visual connection with the club. Key colors include:
  - Chelsea Blue (#034694) for headings and significant interface elements.
  - Slate Grey (#C0C0C0) for secondary elements like borders and buttons.
  - Off-White (#F5F5F5) for the background, offering a clean, neutral canvas.
  - Dark Grey (#383838) for the main body text, ensuring readability.
  - Metallic Gold (#D4AF37) for call-to-action buttons, adding a touch of sophistication.

- **Modern Typography**: The section utilizes Google Fonts 'Lato' and 'Raleway', enhancing readability and providing a modern, streamlined look.

- **Multimedia Integration**: Each news article is accompanied by a relevant image and an embedded YouTube video, offering a richer, more engaging user experience. This multimedia approach caters to the diverse preferences of the site's audience.

- **Interactive Elements**: Hover effects on buttons and links add an interactive layer, making navigation within the section intuitive and visually pleasing.

![Latest News Section](wireframes/latest-news-section.png)

[Back to Top](#table-of-contents)

### Club Timeline

The "Club Timeline" is a central feature of the "Team & History" section, offering a chronological journey through the pivotal moments of Chelsea Football Club's history. This timeline serves as an interactive and educational tool, allowing fans and visitors to explore the club's significant milestones over the years.

#### Design and Features

![Club Timeline Section](wireframes/club-timeline-section.png)

- The timeline is designed to be visually engaging and easy to navigate. It features a series of events, each marked by a year and accompanied by a brief description of the milestone.
- On larger screens, the timeline adopts a horizontal layout with events alternating on either side of a central line, showcasing a balanced and aesthetically pleasing design. On smaller screens, it switches to a vertical format for better readability.
- Each event on the timeline is highlighted with the club's color theme, maintaining consistency and enhancing visual appeal.
- The timeline not only commemorates the club's achievements but also acts as a storytelling medium, bringing the club's past to life and forging a deeper connection with its rich heritage.
- This feature is built using responsive design principles, ensuring that it adapts seamlessly across various device sizes and screen resolutions.

[Back to Top](#table-of-contents)

### Legendary Figures

This section is dedicated to the iconic legends of Chelsea Football Club, showcasing the profiles of key figures who have made significant contributions to the club's history. Each legend's profile features a photograph, name, and a brief description, giving fans a glimpse into the legacy and achievements of these remarkable individuals.

#### Design and Features

![Legendary Figures Section](wireframes/legendary-figures-section.png)

- The section is presented in a visually appealing card layout, ideal for highlighting individual legends in a neat and organized manner.
- On larger screens, the cards are displayed in a multi-column grid, offering an engaging browsing experience. On smaller screens, the layout adjusts to ensure readability and accessibility.
- Each card includes a hover effect, adding a subtle interactive element to engage users.
- The design adheres to the Chelsea FC color scheme, maintaining visual consistency throughout the site.
- This section not only celebrates the club's history but also serves as an educational resource for new fans to learn about the club's illustrious past.

[Back to Top](#table-of-contents)

### Memorable Matches

Within the "Team & History" section, the "Memorable Matches" feature highlights some of the most significant matches in Chelsea Football Club's history. This part of the website vividly recalls iconic games, showcasing their importance in shaping the club's legacy. Each match is represented with an image, title, and a brief narrative, painting a picture of the event's atmosphere and significance.

#### Design and Features

![Memorable Matches Section](wireframes/memorable-matches.png)

- The matches are presented in an attractive card layout, ideal for encapsulating the essence of each historic game in a concise and visually engaging manner.
- On larger screens, these cards are arranged in a multi-column grid, enhancing the browsing experience and allowing users to easily navigate through the club's storied past. On smaller screens, the layout adapts for optimal readability and accessibility.
- Interactive elements like hover effects are incorporated into each card, adding a layer of engagement and inviting users to explore the details of each match.
- Consistent with the Chelsea FC color scheme, the design maintains a cohesive look and feel with the rest of the site.
- This feature not only commemorates the club's historic victories and pivotal moments but also serves as an informative gateway for fans and newcomers alike to understand and appreciate the club's rich history.

[Back to Top](#table-of-contents)

### Fan Zone

The "Fan Zone" section is a dynamic and interactive area of the website, dedicated to engaging Chelsea Football Club fans in various activities. This section is designed to foster a sense of community and participation among the club's supporters.

#### Design and Features

![Fan Zone Section](wireframes/fan-zone.png)

- **Weekly Fan Poll**: In this feature, fans can express their opinions by voting in weekly polls, such as selecting their player of the match. These polls use radio buttons to ensure a user-friendly and straightforward voting experience.
  
- **Fan Podcasts**: To enhance the fan experience, this section also includes fan-created podcasts. These audio features offer insights, commentary, and discussions about all things Chelsea, adding an auditory dimension to the fan zone.

- **Chelsea Trivia**: This feature tests fans' knowledge about the club's history with a series of trivia questions. The trivia adds an educational and fun dimension to the fan experience, challenging supporters to recall significant moments and facts about the club.

- **Discussion Forum**: A platform for fans to engage in conversations about the club. Integrated via an iframe, this feature connects fans to the Chelsea FC Fan Forum, where they can participate in discussions about the latest matches, transfer rumors, and other club-related topics.

#### Interactive and Responsive Design

- The "Fan Zone" is designed with interactivity in mind, offering features that actively engage users. From polls to quizzes, each element encourages participation and contribution.
- On larger screens, the layout of these features is presented in a multi-column format for easy navigation. On smaller screens, the layout shifts to a stacked format for better readability and accessibility.
- The design adheres to Chelsea FC's color scheme and aesthetic, maintaining visual consistency throughout the site.
- By combining interactive elements with a user-friendly design, the "Fan Zone" enhances the overall fan experience on the website, making it a go-to destination for Chelsea FC supporters.

[Back to Top](#table-of-contents)

### Contact Us

The "Contact Us" section provides a direct and accessible communication channel for visitors of the website. This essential feature allows fans and users to reach out with inquiries, feedback, or support requests, fostering a stronger connection between Chelsea Football Club and its global fanbase.

#### Design and Features

![Contact Us Section](wireframes/contact-us.png)

- **Accessible Contact Form**: The section includes a user-friendly contact form with fields for name, email, and message. This straightforward approach ensures that reaching out is hassle-free and inclusive for all users.
  
- **Responsive Layout**: The form is designed to be responsive, ensuring a seamless experience across various devices. Whether accessed from a mobile phone, tablet, or desktop, the form retains its usability and aesthetic appeal.

- **Chelsea FC Branding**: True to Chelsea FC's color scheme and design language, the "Contact Us" section is both visually pleasing and consistent with the overall website theme. The use of club colors and typography reinforces the brand's identity and enhances the visual continuity of the site.

#### User Interaction and Usability

- Designed with a focus on user interaction, the contact form is straightforward, encouraging users to communicate with ease.
- The form's layout adapts to different screen sizes, ensuring that it remains functional and aesthetically consistent on any device.
- The inclusion of this section contributes significantly to the overall user experience of the website, demonstrating the club's commitment to fan engagement and open communication channels.

[Back to Top](#table-of-contents)

### Footer

The website's footer section serves as a concluding element on each page, providing easy access to Chelsea Football Club's social media channels and important legal information. This footer is both functional and visually aligned with the overall design of the site.

#### Design and Features

![Footer Section](wireframes/footer.png)

- **Social Media Connectivity**: The footer includes neatly arranged icons linking to Chelsea FC's official social media pages on Facebook, Instagram, and Twitter. These icons allow fans to stay connected with the club's latest updates and engage with its online community.

- **Responsive and Accessible**: Ensuring accessibility and responsiveness, the footer's layout and design are optimized for all devices. This thoughtful design approach ensures that the footer's content is easily navigable regardless of the device being used.

- **Consistent Branding**: In line with Chelsea FC's branding, the footer maintains the club's color scheme and typographic style. This consistent branding across the website reinforces the club's identity and ensures a cohesive user experience.

#### User Experience and Legal Compliance

- The footer's user-friendly design includes clearly labeled social media icons, making it simple for users to find and follow Chelsea FC on various platforms.
- A copyright statement, '© 2023 Chelsea Pride. All rights reserved.', is prominently displayed, acknowledging the site's legal rights and ownership.
- The incorporation of this well-designed footer not only enhances the aesthetic appeal but also contributes to the site's functionality, offering users additional resources and avenues for engagement with the club.

[Back to Top](#table-of-contents)

## Features to be Implemented

- **Contact Form**: Integrate a functional form for direct communication with website administrators.
- **Sponsor Links**: Include links to official Chelsea FC sponsors' websites.

[Back to Top](#table-of-contents)

## Technologies Used

## Languages

- [HTML](https://en.wikipedia.org/wiki/HTML "HTML") - Structuring web content.

- [CSS](https://en.wikipedia.org/wiki/CSS "CSS") - Styling HTML content.

## Libraries & Frameworks

- [Google Fonts](https://fonts.google.com/ "Google Fonts") - Diverse and appealing font styles.

- [Font Awesome](https://fontawesome.com/ "Font Awesome") - Wide range of icons.

## Tools

- [Codeanywhere](https://codeanywhere.com/ "Codeanywhere") - Cloud IDE used for website development.
- [Balsamiq](https://balsamiq.com/wireframes/ "Balsamiq") - Wireframing during the design phase.
- [W3C HTML Validation Service](https://validator.w3.org/ "W3C HTML") - Validating HTML content.
- [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/ "W3C CSS") - Validating CSS styles.
- [Box Shadow Generator](https://html-css-js.com/css/generator/box-shadow/ "html-css-js.com") - CSS box shadows.
- [Unsplash](https://unsplash.com/ "Unsplash") - High-quality, royalty-free images.

[Back to Top](#table-of-contents)

# Testing

The Chelsea Pride website has been thoroughly tested to ensure it meets the desired goals and provides an optimal user experience. The website has been designed to be responsive, adapting seamlessly to different screen sizes. This adaptability ensures that the images and content are displayed clearly and sharply on all devices, avoiding any large, empty spaces. The site's navigation is user-friendly, allowing visitors to easily explore the site and make contact through the provided form or social media links. The content has been kept simple and concise to avoid overwhelming users.

## Encountered Issues

During the testing phase, several issues were identified and addressed:

- **Responsive Design Adjustments**: Initially, the site was designed with a minimum width of 992px for the largest screen styling. However, it became clear that this approach was not visually effective for larger screens. An extra-large screen size breakpoint was added to improve the site's appearance and usability on larger screens.

- **Wireframe Design Modifications**: The original wireframe designs underwent changes during the development process. These modifications were made to enhance user experience, improve visual appeal, and ensure better content organization. The final design is a result of iterative adjustments, balancing aesthetics and functionality.

- **Forum Link Positioning**: In the desktop version, the positioning of the 'Forum Link' under the iframe was not initially aligned as intended. Adjustments were made to the CSS to ensure the link is positioned correctly under the iframe, leading to a cleaner and more intuitive layout.

- **HTML Validation Issues**: HTML validation revealed several issues, including obsolete attributes and misplaced text within the iframe element. These issues were corrected by removing outdated attributes and ensuring proper placement of text and elements within the HTML structure.

- **CSS Frameborder Obsolescence**: The 'frameborder' attribute on iframe elements was found to be obsolete. This was resolved by using CSS for border styling instead, adhering to modern web standards.

- **Unresponsive 'a' Link**: The 'a' link within the 'fan-forum' section was initially unresponsive and affected the layout. This was corrected by adjusting the CSS properties and ensuring proper HTML structure, resulting in a fully functional and well-positioned link.

These issues were systematically resolved to enhance the overall functionality, usability, and aesthetic appeal of the Chelsea Pride website.

[Back to Top](#table-of-contents)

# Deployment

The Chelsea Pride website was deployed using GitHub Pages with the following steps:

- Navigate to the repository on GitHub and click 'Settings'.
- Select 'Pages' from the side navigation menu.
- Choose the 'main' branch under the 'Source' dropdown menu.
- Click the 'Save' button.
- The website is now live and accessible at [Chelsea Pride GitHub Page URL].
- Future changes can be made by committing and pushing updates to GitHub, which will automatically reflect on the live site.

[Back to Top](#table-of-contents)

# Credits

Credits for the Chelsea Pride website are extended to:

- **Code Inspiration, Help, and Advice:**
  - [Simen Daehlin](https://github.com/Eventyret "Simen Daehlin") for project idea, review and guidance.
  - [CSS-Tricks](https://css-tricks.com/ "CSS-Tricks") for various CSS snippets.
  - [Code Institute](https://www.codeinstitute.net/ "Code Institute") for HTML and CSS guidance.

- **Design and Content Inspiration:**
  - [Chelsea Football Club Official Website](https://www.chelseafc.com/ "Chelsea FC Official Website") for club information.
  - [The Pride of London Website](https://theprideoflondon.com/ "The Pride of London Website") for layout ideas.

- **Images and Media:**
  - [Unsplash](https://unsplash.com/ "Unsplash") for high-quality, royalty-free images.
  - [FontAwesome](https://fontawesome.com/ "Font Awesome") for icons used throughout the site.

[Back to Top](#table-of-contents)
