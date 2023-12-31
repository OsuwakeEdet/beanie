# Formal Documentation for the Provided HTML Code

## Document Information:
- **Document Title:** Beanie Website HTML Structure
- **Author:** Emana Osuwake Edet
- **Date:** December 30, 2023

## Table of Contents:
1. Introduction
2. Document Purpose
3. HTML Structure Overview
4. Description of Components
5. Styles and External Resources
6. Conclusion

## 1. Introduction:
This document provides a formal documentation for the HTML code representing the structure of the Beanie website.

## 2. Document Purpose:
The purpose of this document is to offer clarity and understanding of the HTML structure, elements, and components used in the Beanie website.

## 3. HTML Structure Overview:
The provided HTML code consists of the following primary sections:
- **Document Type Declaration and Metadata**: Specifies document type, character set, viewport settings, and refresh interval.
- **Header**: Contains navigation elements such as the logo and menu items.
- **Main Content**: Includes sections for the hero banner, statistics, course offerings, certificates, pricing, and footer.

## 4. Description of Components:

### Header:
- **Navigation**: 
  - Logo labeled as "beanie.io".
  - List of navigation items: 'about', 'contact', 'skill', 'blog'.
  - Icons for search and menu functionalities.

### Main Content:
- **Hero Section**: 
  - Prominent header with a tagline and CTA buttons.
  - Background image and related content.
- **Statistics Section**: 
  - Ratings and reviews metrics.
  - Statement about trust and credibility.
- **Course Section**: 
  - Three distinct course offerings with icons and descriptions.
- **Certificate Section**: 
  - List of popular certificates with details like pricing, time, and description.
- **Pricing Section**: 
  - Pricing plans categorized as 'Monthly'.
  - Detailed features under each plan.

### Footer:
- **Newsletter Signup**: 
  - Input field for email subscription and a submit button.
- **Footer Links**: 
  - Categorized sections for About, Solutions, Personal, and Social links.

## 5. Styles and External Resources:
- **Styling**: Inline styles are applied for certain components to define font styles, colors, and other visual attributes.
- **External Resources**: 
  - Stylesheet: `style.css` is linked for additional styling.
  - External fonts are sourced from Google Fonts and other icon libraries (Boxicons, Remixicon).

## 6. Conclusion:
This formal documentation outlines the structure, components, and resources utilized in the Beanie website's HTML code. It provides a comprehensive overview for developers or stakeholders to understand the layout and functionality of the website.

---

This document is intended to provide a structured overview of the HTML code. For more detailed insights or modifications, further collaboration or discussion may be required.


The provided code is a CSS stylesheet that defines various styles for a website. Here's a structured documentation for the CSS code:

### CSS Documentation:

#### 1. Global Reset:
- Resetting default styles for all elements.
  ```css
  * {
    padding: 0;
    margin: 0;
    text-decoration: none;
    color: black;
    list-style: none;
  }
  ```

#### 2. Button Styles:
- Defines the base styles for buttons across the site.
  ```css
  button {
    cursor: pointer;
    font-weight: 500;
    border: none;
    outline: none;
  }
  ```

#### 3. Navigation Styles:
- Styles for the website navigation.
  ```css
  .nav {
    display: flex;
    align-items: center;
    justify-content: space-around;
    gap: 20px;
    text-transform: capitalize;
    font-family: "Prompt", sans-serif;
    width: 100%;
    margin: auto;
    margin-top: 20px;
  }
  ```

#### 4. Hero Section:
- Styles for the main hero section of the website.
  ```css
  .hero-section {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 100%;
    margin-top: 1%;
    height: 80vh;
  }
  ```

#### 5. Statistics Section:
- Styles for displaying statistics like ratings and reviews.
  ```css
  .stats {
    display: flex;
    width: 100%;
    margin: 5em 0 10em 0;
    align-items: center;
    justify-content: center;
  }
  ```

#### 6. Course Section:
- Styles for displaying different courses offered.
  ```css
  .course-section {
    margin-top: 3em;
    margin-bottom: 5em;
  }
  ```

#### 7. Certificate Section:
- Styles for displaying certificates or qualifications.
  ```css
  .certificate-section {
    display: flex;
    flex-direction: column;
  }
  ```

#### 8. Pricing Section:
- Styles for the pricing details section.
  ```css
  .pricing-section {
    width: 100%;
    margin-top: 4em;
    margin-bottom: 1em;
  }
  ```

#### 9. Responsive Design:
- Media queries for responsive design, adjusting styles for screens with a max-width of 800px.
  ```css
  @media all and (max-width: 800px) {
    /* Styles for smaller screens */
  }
  ```

### Conclusion:
The provided CSS code contains styles for various sections of a website. It covers global resets, button styles, navigation styles, hero section, statistics, courses, certificates, pricing, and responsive design. This structured documentation gives an overview of the different styles applied to various components of the website.
