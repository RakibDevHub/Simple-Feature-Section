<!-- Please update value in the {}  -->

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
  - [Useful resources](#useful-resources)
- [Built with](#built-with)
- [Features](#features)
- [Contact](#contact)
- [Acknowledgements](#acknowledgements)

<!-- OVERVIEW -->

## Overview

![screenshot](https://user-images.githubusercontent.com/16707738/92399059-5716eb00-f132-11ea-8b14-bcacdc8ec97b.png)

<!--
Introduce your projects by taking a screenshot or a gif. Try to tell visitors a story about your project by answering:

- What have you learned/improved?
- Your wisdom? :)
-->

This project is a clean, responsive "Feature Section" designed for SaaS products. It demonstrates how to handle card-based layouts that remain readable and visually balanced across mobile, tablet, and desktop viewports.

### What I learned

<!-- Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge. -->

In this challenge, I focused on mastering **Flexbox wrapping** and **box-shadow optics**.

One key highlight from my CSS was managing the card dimensions while using `flex-wrap: wrap`. By using a `max-width` on the `.feature-card` and `justify-content: center` on the container, the layout automatically handles the transition from a 3-column row to a 1-column stack without needing complex math for every breakpoint.

```css
.feature-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 32px;
}

.feature-card {
  max-width: 350px;
  flex-direction: column;
}
```

### Useful resources

<!--
- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.
-->

### Built with

<!-- This section should list any major frameworks that you built your project using. Here are a few examples.-->

- Semantic HTML5 for accessibility.
- CSS Custom Styling (No frameworks used).
- Flexbox Layout for both the section structure and internal card alignment.

## Features

<!-- List the features of your application or follow the template. Don't share the figma file here :) -->

This application/site was created as a submission to a [DevChallenges](https://devchallenges.io/challenges-dashboard) challenge.

## Acknowledgements

<!-- This section should list any articles or add-ons/plugins that helps you to complete the project. This is optional but it will help you in the future. For exmpale -->

## Author

- Protfolio [Md Rakibul Islam](https://portfolio-pi-seven-54.vercel.app/)
- GitHub [@RakibDevHub](https://{github.com/rakibdevhub})
```
