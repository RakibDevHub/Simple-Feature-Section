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

### Built with

- Semantic HTML5 for accessibility.
- CSS Custom Styling (No frameworks used).
- Flexbox Layout for both the section structure and internal card alignment.

## Features

This application/site was created as a submission to a [DevChallenges](https://devchallenges.io/challenges-dashboard) challenge.

## Author

- Protfolio [Md Rakibul Islam](https://portfolio-pi-seven-54.vercel.app/)
- GitHub [@RakibDevHub](https://{github.com/rakibdevhub})
