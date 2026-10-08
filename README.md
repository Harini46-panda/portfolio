# Personal Portfolio Website

A static personal portfolio website built with HTML and CSS to present a computer science engineering student's profile, education, technical skills, achievements, interests, and contact information through a simple multi-page interface.

## Table of Contents

* [About](#about)
* [Features](#features)
* [Technology Stack](#technology-stack)
* [Website Pages](#website-pages)
* [Getting Started](#getting-started)
* [Prerequisites](#prerequisites)
* [Run Locally](#run-locally)
* [Usage Guide](#usage-guide)
* [Project Structure](#project-structure)
* [How It Works](#how-it-works)
* [External Resources](#external-resources)
* [Limitations](#limitations)
* [License](#license)

## About

The Personal Portfolio Website is a static web application designed to introduce the developer and provide an overview of their academic background, technical interests, achievements, and contact information.

The website uses separate HTML pages for different sections of the portfolio and dedicated CSS files for page styling. A dark gradient theme is used throughout the website, with navigation links connecting the main sections.

## Features

### Personal Introduction

* Presents a short introduction on the home page.
* Highlights an interest in computer science, coding, and problem-solving.

### About Section

* Provides personal and academic information.
* Displays school and college details.
* Includes internship experience.
* Lists programming and web development skills.
* Displays language proficiency.

### Honors and Awards

* Presents achievements using image-based cards.
* Displays descriptions when the user interacts with the achievement images.
* Includes academic and coding-related achievements.

### Contact Section

* Provides contact information for communication.
* Includes links to social and professional profiles.
* Provides a simple email input area for staying connected.

### Navigation

* Provides navigation between Home, About, Honors & Awards, and Contact pages.
* Uses a consistent navigation style across the website.

### Visual Design

* Uses a dark gradient background.
* Uses CSS Grid for content layouts.
* Uses rounded images and styled typography.
* Includes W3.CSS animation on selected pages.

## Technology Stack

| Technology               | Purpose                                                           |
| ------------------------ | ----------------------------------------------------------------- |
| HTML5                    | Creates the structure and content of the portfolio pages          |
| CSS3                     | Provides styling, layouts, colors, typography, and visual effects |
| CSS Grid                 | Organizes portfolio and footer content into structured layouts    |
| W3.CSS                   | Provides page animation used on selected pages                    |
| External Image Resources | Provides visual content used on the home page                     |

## Website Pages

### Home Page

The home page introduces the developer with a short personal statement and presents visual content related to creativity, technology, and problem-solving.

Main file:

```text
index.html
```

### About Page

The About page presents:

* Personal introduction
* Educational background
* College information
* Internship experience
* Programming languages
* Web development skills
* Language proficiency

Main file:

```text
about.html
```

### Honors & Awards Page

The Honors & Awards page presents academic and extracurricular achievements using images with hover-based descriptions.

Main file:

```text
honors.html
```

The page includes achievements related to:

* Coding activities
* Chemistry quiz participation
* Higher secondary academic performance
* Highest mark in Chemistry

### Contact Page

The Contact page provides a direct way to get in touch and displays professional and social links.

Main file:

```text
contact.html
```

## Getting Started

This project is a static website and does not require a backend server, database, package manager, or build tool.

The website can be opened directly in a browser or served locally using a development server such as VS Code Live Server.

## Prerequisites

The following are recommended:

* A modern web browser such as Google Chrome, Microsoft Edge, or Firefox
* Visual Studio Code
* Live Server extension for VS Code (optional)

No additional programming runtime is required.

## Run Locally

Follow these steps to run the portfolio on your local machine.

### 1. Clone or Download the Repository

Clone the repository:

```bash
git clone <repository-url>
```

Or download and extract the project ZIP file.

### 2. Open the Project

Open the project folder in Visual Studio Code.

```text
portfolio-main/
```

### 3. Start the Website

#### Option 1: Open Directly

Open the following file in a web browser:

```text
index.html
```

The portfolio will load as a static website.

#### Option 2: Use VS Code Live Server

1. Open the project in Visual Studio Code.
2. Install the **Live Server** extension if it is not already installed.
3. Right-click `index.html`.
4. Select **Open with Live Server**.
5. The website will open in your default browser.

Using Live Server is recommended during development because changes can be viewed quickly after editing the files.

## Usage Guide

### Navigating the Website

Use the navigation bar to move between:

```text
Home
About
Honors & Awards
Contact
```

### Viewing the About Section

Open the **About** page to view educational background, internship experience, programming skills, web development skills, and language proficiency.

### Viewing Achievements

Open **Honors & Awards** to view the achievement images. Hover over an image to reveal its corresponding description.

### Contacting the Developer

Open the **Contact** page to view the available communication and professional profile links.

## Project Structure

```text
portfolio-main/
│
├── index.html
│   └── Main home page
│
├── about.html
│   └── About, education, experience, and skills
│
├── honors.html
│   └── Honors and awards section
│
├── contact.html
│   └── Contact information and social links
│
├── homepagestyle.css
│   └── Home page styling
│
├── about.css
│   └── About page styling
│
├── honors.css
│   └── Honors and awards page styling
│
├── contact.css
│   └── Contact page styling
│
├── my photo.jpg
│   └── Personal profile image
│
├── code.jpg
│   └── Coding achievement image
│
├── chemistry.jpg
│   └── Chemistry quiz achievement image
│
├── top-notch.jpg
│   └── Academic achievement image
│
└── centum.jpg
    └── Academic achievement image
```

## How It Works

The website follows a simple static-page workflow:

```text
User Opens index.html
        │
        ▼
     Home Page
        │
        ├──────────────┐
        ▼              ▼
     About       Honors & Awards
        │              │
        └───────┬──────┘
                ▼
             Contact
```

Each HTML page is connected to its corresponding CSS file for styling.

The navigation links allow users to move between the different pages. The Honors & Awards page uses CSS hover effects to hide the achievement image and display its description when the user interacts with the image.

The Home and Contact pages also use W3.CSS for a top animation effect.

## Styling and Layout

The portfolio uses CSS features including:

* Linear gradient backgrounds
* CSS Grid layouts
* Floating navigation elements
* Rounded images
* Custom typography
* Hover effects
* Responsive viewport configuration
* Footer-based multi-column layout

The overall design uses a dark theme with white text and consistent navigation across the pages.

## External Resources

The project references W3.CSS from the W3Schools CDN on the Home and Contact pages.

The Home page also uses externally hosted images for some of its visual content. An internet connection may therefore be required for those external resources to load correctly.

Local achievement and profile images are stored directly in the project directory.

## Limitations

The current implementation is a static portfolio website and has the following limitations:

* There is no backend or database.
* The email input on the footer does not implement a server-side subscription or submission process.
* The website does not contain a dedicated JavaScript application layer.
* Some navigation references use `homepage.html`, while the actual main page in the project is `index.html`; these links may need to be updated to `index.html` for direct navigation to work correctly.
* Some social links are placeholders rather than fully implemented destinations.
* Some images on the Home page are loaded from external URLs and may not appear without an internet connection.
* The layout uses fixed spacing in some sections and may require further refinement for different screen sizes.

## License

No license file is currently included in the project. Add an appropriate license before distributing the project publicly.
