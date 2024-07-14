# Aster News Website

## Overview

Aster News is a responsive web application designed to provide the latest news across various categories including Top Stories, Around the World, Business, Health, Covid-19, Entertainment, Sports, and more. The application leverages HTML, CSS (with Tailwind CSS), and JavaScript to deliver a clean, user-friendly interface.

## Table of Contents

1. [Prerequisites](#prerequisites)
2. [Getting Started](#getting-started)
3. [Project Structure](#project-structure)
4. [HTML File Explanation](#html-file-explanation)
5. [CSS File Explanation](#css-file-explanation)
6. [Running the Project](#running-the-project)
7. [Vulnerabilities](#vulnerabilities)
8. [About the Author](#about-the-author)

## Prerequisites

- Modern web browser (e.g., Chrome, Firefox, Safari)
- Text editor or IDE (e.g., VSCode, Sublime Text)
- Node.js and npm (optional, for development purposes)

## Getting Started

### Steps

1. **Clone the repository:**
    ```bash
    git clone https://github.com/yourusername/aster-news.git
    ```
2. **Navigate to the project directory:**
    ```bash
    cd aster-news
    ```
3. **Open `index.html` in your browser:**
    - You can directly open `index.html` file in your browser.
    - Alternatively, you can use a live server extension in your text editor for a better development experience.

## Project Structure

aster-news/
├── assets/
│ ├── css/
│ │ └── style.css
│ ├── img/
│ │ ├── logo.svg
│ │ ├── home.svg
│ │ ├── globe.svg
│ │ ├── Business.svg
│ │ ├── Health.svg
│ │ ├── Covid.svg
│ │ ├── Entertainment.svg
│ │ ├── Sports.svg
│ │ ├── Discussion.svg
│ │ ├── Notification.svg
│ │ ├── settings.svg
│ │ ├── gift.svg
│ │ ├── GalaxyF22.jpg
│ │ ├── feather.svg
│ │ ├── crosshair.svg
│ │ ├── sun.svg
│ │ ├── file-text.svg
│ │ └── share.svg
├── index.html
└── README.md

## HTML File Explanation

### `index.html`

This file structures the content of the Aster News website and includes the following main sections:

- **Header**: Contains the search bar, latest news button, and profile section.
- **Sidebar Navigation**: Provides links to different news categories.
- **Main Content Area**: Displays the top stories and other news articles.
- **Footer**: Includes links to the privacy policy and terms of service.
- **Aside Section**: Displays additional information such as weather updates and quick bytes.

## CSS File Explanation

### `style.css`

This CSS file includes custom styles for the website and imports:

- Font Awesome for icons.
- Google Fonts for typography.
- Additional CSS for styling various elements like the navigation bar, filter buttons, news articles, and footer.

Key classes and styles:
- **`.active-nav-item`**: Highlights the currently active navigation item.
- **`nav li:hover`**: Provides visual feedback for user interactions in the navigation menu.
- **`.filter-item`**: Styles the category filter buttons in the main content area.

## Running the Project

To run the project, simply open the `index.html` file in your web browser. If you prefer a live server, you can use extensions like Live Server in VSCode to serve the project locally.

## Vulnerabilities

1. **Insecure External Resources**: The external resources (Font Awesome, Google Fonts, etc.) are included via HTTP links. Consider using HTTPS for secure loading of resources.
2. **Unvalidated Input**: The search input is not validated or sanitized. This can potentially open the site to XSS (Cross-Site Scripting) attacks.
3. **Hardcoded Links**: The links in the sidebar are hardcoded, which might lead to broken links if not managed properly.
4. **No Authentication**: The profile section suggests user interaction, but there is no authentication mechanism implemented.
5. **CSS Injection**: Inline CSS or external stylesheets should be carefully managed to prevent unwanted CSS injections.

## About the Author

As an experienced front-end developer, I (Ramin Kerimov) have been improving user experience with intuitive and visually appealing user interfaces since 2021. Specializing in HTML, CSS, and JavaScript, I excel at translating design concepts into functional code. I am proficient in various frameworks such as React and Next.js, as well as libraries such as Tailwind, Shadcn, Antd, Chakra, and Material UI. My experience extends to version control systems (GIT, GitHub, GitLab), state management tools (Context, Zustand, Jotai), and other important tools such as PWA, Webpack, and Vite.

I graduated from Baku State University in biology and speak several languages, including Azerbaijani, Russian, Turkish, English, and Arabic. I have worked in a company developing a business management program, supporting existing projects, making additions and corrections.
