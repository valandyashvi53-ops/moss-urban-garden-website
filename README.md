# moss-urban-garden-website
A responsive urban gardening website built with HTML, CSS, Bootstrap, and JavaScript, featuring garden services, image gallery, plant quiz, stories, and garden planner.
# 🌿 Moss — Make Room to Grow

A modern, responsive urban gardening website designed to help city dwellers turn balconies, rooftops, windowsills, courtyards, and indoor spaces into beautiful green spaces.

## 🌱 About the Project

**Moss — Make Room to Grow** is a frontend website project focused on urban gardening and sustainable city living.

The website provides information about garden planning, planting, plant care, community gardens, and different ways to create green spaces in small urban environments.

It also includes interactive features such as a plant-care quiz, image gallery, garden stories, service information modals, and a personalized garden planner.

## ✨ Features

* 🌿 Modern and clean gardening-themed UI
* 📱 Fully responsive design
* 🧭 Responsive Bootstrap navigation bar
* 🖼️ Interactive image gallery
* 🔍 Gallery image preview using Bootstrap modal
* 📖 Garden stories section
* 💡 Interactive garden service information
* 🌱 Plant-care quiz with score
* 🪴 Personalized garden planner
* ☀️ Garden recommendations based on space and sunlight
* 📧 Garden planner email functionality
* 🎨 Custom typography using Google Fonts
* ♿ Accessibility-friendly labels and focus states
* 🎞️ Smooth scrolling and subtle animations
* 📐 Mobile, tablet, and desktop layouts
* 🌍 Urban gardening and eco-friendly content

## 🛠️ Technologies Used

* **HTML5** — Website structure
* **CSS3** — Styling, responsive design, animations
* **JavaScript** — Interactive functionality
* **Bootstrap 5** — Responsive layout, navbar, modals, forms
* **Google Fonts** — DM Sans & Playfair Display
* **Unsplash** — Gardening and plant imagery

## 📂 Project Structure

```text
moss-urban-garden-website/
│
├── index.html
├── bootstrap.min.css
├── bootstrap.bundle.min.js
├── README.md
└── assets/
    └── images/
```

> If Bootstrap files are stored in another folder in your project, update the paths in `index.html` accordingly.

## 🖥️ Main Sections

### 🏠 Home

The hero section introduces Moss with the message:

> **Make room to grow.**

It contains a call-to-action button and an introduction to the urban gardening concept.

### 🌿 About

Explains the purpose of Moss and highlights its focus on bringing nature into urban environments.

### 🖼️ Gallery

A responsive collection of urban gardening images.

Users can click an image to open a larger version inside a Bootstrap modal.

### 📖 Stories

Contains three garden starting-point ideas:

* Kitchen-window herb bar
* Calmer green corner
* Pocket for pollinators

Each story opens additional information in a modal.

### 🌱 Services

The website provides nine gardening-related services:

1. Space Planning
2. Garden Setup
3. Hands-on Workshops
4. Seasonal Check-ins
5. Grow-your-own Kits
6. Shared Garden Projects
7. Soil & Compost Coaching
8. Plant Health Visits
9. Watering Setup

Each service contains additional eco-friendly tips.

### 🧠 Plant Quiz

An interactive three-question plant-care quiz.

The quiz checks:

* Pot drainage
* Watering
* Sunlight requirements for basil

The user receives a score after submitting the answers.

### 🪴 Garden Planner

The garden planner allows users to select:

* Garden space
* Amount of sunlight
* Location
* What they want to grow

Based on the selected space and sunlight, the website dynamically generates a garden idea.

### 📩 Contact

Provides contact information and a call-to-action for users who want help planning their garden.

## 📱 Responsive Design

The website is designed to work across:

* 💻 Desktop
* 💻 Laptop
* 📱 Tablet
* 📱 Mobile

CSS media queries are used to adjust layouts, typography, grids, navigation, and spacing for smaller screens.

## 🎨 Design

The design uses a natural color palette inspired by plants and outdoor spaces.

### Main Design Elements

* Soft off-white background
* Deep green accents
* Earth-inspired colors
* Serif display typography
* Clean sans-serif body typography
* Minimal borders
* Large photography
* Responsive cards and grids

### Fonts

The project uses:

* **Playfair Display** — Headings
* **DM Sans** — Body text

## ⚙️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/moss-urban-garden-website.git
```

### 2. Open the project

Go to the project folder:

```bash
cd moss-urban-garden-website
```

### 3. Run the website

Open:

```text
index.html
```

in your browser.

You can also use **VS Code Live Server** for development.

## 📧 Garden Planner

The garden planner uses a `mailto:` link to prepare an email containing the user's garden information.

The form collects:

```text
Name
Email
Space
Sunlight
Neighborhood / City
What they want to grow
Generated Garden Idea
```

The visitor can review the generated email and send it through their default email application.

## 🌐 Image Sources

The project uses images from **Unsplash** through remote image URLs.

Because the images are loaded remotely, an internet connection is required to display them.

## 🚀 Future Improvements

Possible future improvements include:

* Add a backend for storing garden-planner submissions
* Add real user accounts
* Add a database for garden projects
* Add more plant recommendations
* Add plant search functionality
* Add dark mode
* Add appointment booking
* Add a real contact form
* Add an admin dashboard
* Replace remote images with optimized local assets
* Add SEO improvements
* Add favicon and social sharing metadata

## 📸 Project Preview

Add screenshots of your website here:

```markdown
![Moss Website Home](screenshots/home.png)

![Moss Gallery](screenshots/gallery.png)

![Moss Services](screenshots/services.png)

![Moss Garden Planner](screenshots/garden-planner.png)
```

## 📄 License

This project is created for learning, practice, and portfolio purposes.

If you reuse the project, make sure you comply with the licenses and usage terms of any third-party assets, fonts, libraries, and images.

---
Frontend Web Development Project

⭐ If you like this project, consider giving the repository a star!
