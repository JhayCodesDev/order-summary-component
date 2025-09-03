# Frontend Mentor - Order summary card solution

This is a solution to the [Order summary card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUj). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview
The goal of this challenge was to build a clean and responsive order summary card that closely matches the provided design.

In this solution, I applied:

Semantic HTML structure to improve readability and ensure accessibility.

Container and sub-container classes to clearly organize the layout and separate content sections.

CSS styling for typography, spacing, buttons, and background to align with the mockup design.

Flexbox for layout alignment and spacing adjustments.

Hover states for interactive elements to enhance user experience.

Responsive design with media queries to ensure the card looks good on smaller devices (down to 320px).

Consistent CSS organization for easier updates and scalability.

This challenge was a valuable opportunity to practice working with layout structures, creating button hover effects, and refining details to transform a static design into a responsive and visually appealing component.

### Screenshot

![screenshot for desktop](./Screenshot%202025-09-03%20at%2023-18-08%20Frontend%20Mentor%20Order%20summary%20card.png)
![screenshot for mobile](./Screenshot%202025-09-03%20at%2023-18-36%20Frontend%20Mentor%20Order%20summary%20card.png)
![screenshot for active state](./Screenshot%202025-09-03%20at%2023-19-15%20Frontend%20Mentor%20Order%20summary%20card.png)

### Links

- Live Site URL: [View live site here](https://JhayCodesDev.github.io/order-summary-component/)

## My process

1. Setup

Downloaded the starter files and extracted them into a new project folder named order-summary-card-main.

Reviewed the provided documents (style-guide.md, README-template.md, README.md, and design mockups) to understand the requirements.

2. Structure

Built the HTML structure using semantic tags for readability and accessibility.

Used a container and sub-container to organize the main layout.

Added a details section to display the order plan and pricing information.

Included an attribution div at the bottom for credits and links.

3. Styling

Applied base styles for the body, headings, and containers to align with the design mockup.

Used Flexbox to align and space elements consistently within the card.

Styled the order details, buttons, and hover states for interactive feedback.

Added a background image for both desktop and mobile views to match the challenge design.

Styled the attribution section to maintain consistency with the overall design.

4. Responsiveness

Followed a desktop-first approach, ensuring the card looked good on larger devices.

Added a mobile breakpoint:

@media screen and (max-width: 400px) {
  .container {
    width: 90%;
    background-image: url("images/pattern-background-mobile.svg");
  }
}


The desktop view used the pattern-background-desktop.svg, while the mobile view switched to the pattern-background-mobile.svg.

Adjusted font sizes, spacing, and layout so the design remained visually appealing and fully functional on smaller screens.

5. Finishing Up

Cleaned up CSS by grouping selectors logically.

Tested across different screen sizes to ensure responsiveness.

Wrote the README and prepared the project for deployment.

### Built with

- Semantic HTML5 markup

- CSS custom properties for reusable values (colors, spacing, etc.)

- Flexbox for layout and alignment

- Desktop-first workflow with media queries for smaller devices (max-width: 400px)

- Responsive design techniques, including background images optimized for desktop and mobile

## Author

- Website - [@JhayCodesDev](https://github.com/JhayCodesDev)
- Frontend Mentor - [@yJhayCodesDev](https://www.frontendmentor.io/profile/JhayCodesDev)
- Twitter - [@JhayCodes](https://www.twitter.com/JhayCodes)

## Acknowledgments
Thanks to Frontend Mentor for providing such practical and challenging projects.
