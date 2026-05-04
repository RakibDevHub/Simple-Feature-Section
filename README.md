<h1 align="center">Simple Feature Section | devChallenges</h1>

<div align="center">
   Solution for a challenge <a href="https://devchallenges.io/challenge/simple-feature-section-challenge" target="_blank">Simple Feature Section</a> from <a href="http://devchallenges.io" target="_blank">devChallenges.io</a>.
</div>

<div align="center">
  <h3>
    <a href="[https://rakibdevhub.github.io/simple-feature-section/](https://rakibdevhub.github.io/simple-feature-section/)">
          Demo
    </a>
    <span> | </span>
    <a href="[https://github.com/RakibDevHub/simple-feature-section](https://github.com/RakibDevHub/simple-feature-section)">
      Solution
    </a>
    <span> | </span>
    <a href="https://devchallenges.io/challenge/simple-feature-section-challenge">
      Challenge
    </a>
  </h3>
</div>

<!-- TABLE OF CONTENTS -->

## Table of Contents

- [Overview](#overview)
  - [What I learned](#what-i-learned)
- [Built with](#built-with)
- [Features](#features)
- [Auuthor](#author)

<!-- OVERVIEW -->

## Overview

![screenshot](https://user-images.githubusercontent.com/16707738/92399059-5716eb00-f132-11ea-8b14-bcacdc8ec97b.png)

This project is a clean, responsive "Feature Section" designed for SaaS products. It demonstrates how to handle card-based layouts that remain readable and visually balanced across mobile, tablet, and desktop viewports.

### What I learned

In this challenge, I focused on mastering **Flexbox wrapping** and **Media Screen** transitions.

One key highlight was managing card dimensions using `flex-wrap: wrap`. By combining `max-width` on individual cards with `justify-content: center` on the parent container, the layout handles the transition from a 3-column row to a 1-column stack automatically. I also implemented dynamic header scaling for better mobile typography.

```css
/* Responsive header logic */
.feature-header {
  max-width: 400px;
}

@media (max-width: 640px) {
  .feature-header {
    max-width: 600px;
  }
}

/* Automatic card wrapping */
.feature-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 32px;
}
```

### Built with

-   **Semantic HTML5 markup**: For structured and accessible content.
-   **CSS Custom Styling**: Utilizing Flexbox for both the primary layout and internal card alignment.
-   **Media Queries**: Tailoring the header and container widths for specific breakpoints.
-   **Responsive Assets**: Integrating SVG backgrounds and high-quality images that scale with the layout.

## Features

-   **Adaptive Header**: The header width adjusts based on the screen size to prevent awkward text wrapping.
-   **Dynamic Grid**: Cards wrap seamlessly from horizontal to vertical stacks based on available width.
-   **Deep Shadow UI**: Uses layered box-shadows to create a modern, elevated feel on dark backgrounds.
-   **Nested Flexbox**: Each card uses `flex-direction: column` to perfectly align icons, text, and descriptive images.

This application/site was created as a submission to a [DevChallenges](https://devchallenges.io/challenges-dashboard) challenge.

## Author

- Protfolio [Md Rakibul Islam](https://portfolio-pi-seven-54.vercel.app/)
- GitHub [@RakibDevHub](https://{github.com/rakibdevhub})
