# Mindfulness Kids Club

A fully responsive, accessible one-page landing site introducing children (ages 5–10) to playful mindfulness exercises. Built with Bootstrap 3.4, jQuery and custom CSS, it features:

- A hero image carousel of three breathing and sensory activities  
- Collapsible “About” info cards on emotional regulation, focus & empathy  
- Class-booking thumbnail cards for London, Birmingham & Bristol with a purchase modal  
- A contact form with proper labels and ARIA attributes  
- Smooth-scroll anchors, tooltips and WCAG 2.1 AA–compliant contrast

---

## Table of Contents

1. [Introduction](#introduction)  
2. [Goals](#goals)  
   - [User Goals](#user-goals)  
   - [Company Goals](#company-goals)  
3. [User Experience (UX)](#user-experience-ux)  
   - [Ideal User](#ideal-user)  
   - [User Stories](#user-stories)  
4. [Design](#design)  
   - [Wireframes](#wireframes)  
   - [Colour & Fonts](#colour--fonts)  
   - [Structure](#structure)  
5. [Technologies Used](#technologies-used)  
6. [Features](#features)  
   - [Existing Features](#existing-features)  
   - [Future Features](#future-features)  
7. [Testing](#testing)  
   - [HTML & CSS Validation](#html--css-validation)  
   - [Accessibility](#accessibility)  
   - [Performance & Compatibility](#performance--compatibility)  
8. [Deployment](#deployment)  
   - [GitHub Pages](#github-pages)  
   - [Local Development](#local-development)  
   - [Fork & Clone](#fork--clone)  
9. [Credits & Acknowledgments](#credits--acknowledgments)  
10. [License](#license)  

---

## Introduction

Mindfulness Kids Club is a fictional site designed for parents, teachers and caregivers who want to introduce young children to simple breathing exercises, color-spotting walks and playful “spidey-sense” meditations. It demonstrates best practices in responsive design, accessibility and user engagement—all in a single landing page.

---

## Goals

### User Goals

- Discover kid-friendly mindfulness exercises  
- Learn emotional and academic benefits  
- Find upcoming class dates and locations  
- Book and pay for lessons quickly  
- Contact the organizers with ease  

### Company Goals

- Promote the “Mindfulness Kids Club” brand  
- Showcase benefits and lesson offerings  
- Capture leads via a contact form  
- Offer a seamless booking experience  
- Maintain WCAG 2.1 AA accessibility standards  

---

## User Experience (UX)

### Ideal User

- A parent or educator seeking calming activities for children  
- A caregiver wanting to improve a child’s focus and emotional resilience  
- Anyone exploring mindfulness for the first time  

### User Stories

1. **First-time visitor**  
   - Wants to quickly scan activities and benefits  
   - Needs to view class dates and pricing  
   - Expects to book in under 3 clicks  

2. **Returning visitor**  
   - Remembers site layout and wants rapid access to booking  
   - Prefers keyboard navigation and clear focus states  
   - May wish to contact via email form  

---

## Design

<img width="935" alt="Home" src="https://github.com/user-attachments/assets/0687e33d-261d-4018-8605-bd98d59df6fd" />

<img width="847" alt="About 2" src="https://github.com/user-attachments/assets/128a56f0-5280-4f10-b61b-11d45087a1cf" />

<img width="620" alt="Benefits 3" src="https://github.com/user-attachments/assets/1e433d22-3314-4c66-bd42-f5bf22e36675" />

<img width="730" alt="Class dates 4" src="https://github.com/user-attachments/assets/4b1a26bb-edc5-41c3-94b0-72bfa70abb56" />


<img width="595" alt="Lessons 5" src="https://github.com/user-attachments/assets/aa99e931-5dbe-49c9-bf02-addc9d7b39b2" />

<img width="635" alt="Contact 6" src="https://github.com/user-attachments/assets/68fcbc72-d30f-4ccf-bbc9-4ca291f12c17" />




### Wireframes

- Mobile, tablet and desktop wireframes drafted in Balsamiq and PDF format  
- Responsive grid with a sticky navbar (hamburger menu on < 768 px)

### Colour & Fonts

- Calming pastel backgrounds on cards; high-contrast red (#c9302c) for badges  
- Google Fonts: **Lato** for body text, **Montserrat** for headings  

### Structure

- Single-page layout divided into six sections:  
  1. Hero carousel  
  2. About (collapsible benefits)  
  3. Lessons (dates & booking cards)  
  4. Contact form  
  5. Footer with back-to-top link  
- Smooth-scroll anchors and screen-reader landmarks  

---

## Technologies Used

- **HTML5 & CSS3** (Bootstrap 3.4 grid, utilities, components)  
- **JavaScript/jQuery 3.7.1** (carousel, collapse, smooth scroll, tooltips)  
- **Google Fonts**: Lato & Montserrat  
- **Bootstrap Glyphicons** for icons  

---

## Features

### Existing Features

- **ARIA & Labels**: All icons and controls have `aria-label` or `<label>`  
- **Carousel**: `role="listbox"` with `role="option"` slides  
- **Collapsible Cards**: Keyboard-accessible info toggles  
- **Booking Modal**: Form fields with required attributes and hidden labels  
- **Contact Form**: Name, email, message fields with proper `<label>`  
- **High Contrast Overrides**: Ensures 4.5:1 text/background ratio  

### Future Features

- **Backend Integration**: Connect booking form to an API for real reservations  
- **Dynamic Class Calendar**: Load dates via JSON or CMS  
- **User Accounts**: Allow returning users to view past bookings  
- **Multi-language Support**: Toggle between English and other languages  

---

## Testing

### HTML & CSS Validation

- Passed W3C HTML5 validator with zero errors


  ![Html Validator](https://github.com/user-attachments/assets/7fd2a14d-8e94-472c-ade1-cc35de551cf1)



- CSS validated via W3C Jigsaw—no warnings


<img width="337" alt="W3C css" src="https://github.com/user-attachments/assets/6a97dbe3-4d9c-4b37-a07e-211768e61952" />

   

### Accessibility

- **Lighthouse**: Accessibility score ≥ 90
- 
![Lighthouse report](https://github.com/user-attachments/assets/26ab9a23-2f75-4d24-bdb4-fb896bfc7c0f)



- **Manual Testing**: Full keyboard navigation, focus styles visible  

### Performance & Compatibility

- **Google Lighthouse** Performance ≥ 80 on mobile & desktop  
- Tested on Chrome, Firefox, Edge, Safari (desktop & mobile)  
- Responsive from 320 px to 1920 px  

---

## Deployment

### GitHub Pages

1. Push your `main` branch to GitHub  
2. In **Settings > Pages**, select **main** branch and `/ (root)**  
3. Your site will publish at  
   `https://<your-username>.github.io/mindfulness-kids-club/`

### Local Development

- Option A: Open `index.html` in browser  
- Option B: Serve with Python HTTP server:  
  ```bash
  python3 -m http.server
