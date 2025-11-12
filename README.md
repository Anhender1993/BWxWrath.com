# BWxWrath.com

> The official portfolio and media hub for **BWxWrath**, integrating Twitch content, podcast embeds, and merchandise links under one unified brand.


## Table of Contents
- [Project Description](#project-description)
- [Directory Structure](#directory-structure)
- [Tech Stack](#tech-stack)
- [Deployment](#deployment)
- [Features](#features)
- [Lessons Learned](#lessons-learned)
- [Author](#author)

## Project Description
**BWxWrath.com** is a personal brand website designed and developed by Andrew Henderson.  
It serves as the main hub for the **BWxWrath** ecosystem — combining streaming content, podcast episodes, and merchandise showcases in a responsive, modern layout.  

The site is entirely static and optimized for GitHub Pages deployment, ensuring fast load times and minimal maintenance.  
Key focuses include:
- A clean, symmetrical layout built for accessibility and readability  
- Integrated Twitch and Spotify embeds  
- Themed styling with light/dark mode toggles  
- Links to Redbubble merch, Wrathcast podcast, and social media

## Directory Structure
.
├── .github/workflows/   # Static site build/deploy workflow for GitHub Pages
├── assets/              # Logos, Twitch thumbnails, and merchandise images
├── css/                 # All style definitions (including dark/light mode)
├── index.html           # Main landing page HTML
├── CNAME                # Custom domain configuration for bwxwrath.com
├── .gitignore           # Ignored files and local config
├── .hintrc              # HTMLHint configuration
├── README.md            # Project documentation
└── .DS_Store            # macOS metadata (ignored in deployment)

## Tech Stack
- **Languages:** HTML5, CSS3, JavaScript  
- **Deployment:** GitHub Pages (static site hosting)  
- **Design Tools:** VS Code, Live Server, Browser DevTools  
- **Version Control:** Git & GitHub Actions (static.yml workflow)


## Deployment
The website is hosted directly from this GitHub repository using **GitHub Pages** with a custom domain.

### Deployment Process
1. Commit and push updates to the `main` branch.  
2. GitHub Actions (`.github/workflows/static.yml`) automatically builds and deploys the site.  
3. DNS is configured via the `CNAME` file to route traffic to: bwxwrath.com
4. To view the live version: **[https://bwxwrath.com](https://bwxwrath.com)**

## Features
- **Responsive Layout:** Scales smoothly across desktop and mobile devices.  
- **Light/Dark Mode Toggle:** User-selectable theme persistence using CSS variables.  
- **Embedded Content:**  
- Twitch live stream window  
- Spotify Wrathcast episode player  
- Featured merchandise gallery  
- **Navigation Menu:**  
- Hamburger-style for compact screens  
- Expands horizontally on desktop view  

## Lessons Learned
- Practiced balancing visual design with responsive structure.  
- Learned to configure custom domain hosting with GitHub Pages and `CNAME`.  
- Improved workflow automation through GitHub Actions.  
- Gained experience organizing assets and styling modularly for maintainability.

## Author
**Andrew Henderson**  
- GitHub: [Anhender1993](https://github.com/Anhender1993)   
- Portfolio: [Anhender1993](https://github.com/Anhender1993)    
- LinkedIn: [linkedin.com/in/andrew-v-henderson](https://linkedin.com/in/andrew-v-henderson)
