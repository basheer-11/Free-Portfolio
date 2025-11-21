<img width="1909" height="920" alt="Capture d’écran 2025-11-21 à 16 20 05" src="https://github.com/user-attachments/assets/12a44424-a62d-472a-b992-8762f736c105" />

# 🌟 Free Portfolio Template

A modern, responsive, and customizable portfolio template designed for developers, designers, and creatives. Built with clean HTML, CSS, and JavaScript.
Perfect for building your professional portfolio or learning front-end web development through a real-world project.

![Portfolio Preview] : http://mmi23h06.mmi-troyes.fr/portfolio/projets/template_portfolio/

## ✨ Features

- **Responsive Design**: Fully responsive layout that works seamlessly on all devices
- **Modern UI/UX**: Clean and professional interface with smooth animations
- **Animated Hero Section**: Eye-catching hero section with SVG wave animations
- **Scroll Animations**: Dynamic scroll-triggered animations for enhanced user experience
- **Multiple Sections**:
  - About Me: Personal introduction and CV download
  - Skills: Showcase your technical skills with icon-based cards
  - Projects/Work: Display your portfolio projects with images and technology tags
  - Contact: Interactive contact form with embedded Google Maps
- **Social Media Integration**: Easy-to-configure social media links
- **Smooth Scroll**: Smooth scrolling navigation between sections
- **Back to Top Button**: Convenient button to quickly return to the top
- **Font Awesome Icons**: Pre-integrated Font Awesome for professional icons
- **Easy Customization**: Well-structured and commented code for easy modifications

## 🚀 Quick Start

### Prerequisites

- A modern web browser
- A text editor (VS Code, Sublime Text, etc.)
- Basic knowledge of HTML, CSS, and JavaScript

### Installation

1. Clone or download this repository:
```bash
git clone https://github.com/yourusername/Free-Portfolio.git
```

2. Navigate to the project directory:
```bash
cd Free-Portfolio
```

3. Open `index.html` in your browser or use a local development server

## 🛠️ Customization Guide

### 1. Personal Information

Edit `index.html` and replace the following placeholders:

- **Line 35**: Replace `"Your name here"` with your name
- **Line 36**: Update your job title/specialty
- **Line 89-90**: Write your personal bio
- **Line 91**: Link to your CV/Resume PDF
- **Line 93**: Replace profile image (`images/man.png`)
- **Line 321-322**: Update contact information (phone and email)

### 2. Social Media Links

Update social media links in two locations:

**Header Section** (Lines 41-43):
```html
<a href="YOUR_LINKEDIN_URL" target="_blank">
<a href="YOUR_TWITTER_URL" target="_blank">
<a href="YOUR_GITHUB_URL" target="_blank">
```

**Footer Section** (Lines 361-362):
```html
<a href="YOUR_LINKEDIN_URL" target="_blank">
<a href="YOUR_DISCORD_URL" target="_blank">
```

### 3. Skills Section

Customize your skills in the three main categories (Lines 103-136):
- **Languages**: HTML, CSS, JavaScript, PHP, etc.
- **Tools**: Docker, Ubuntu, SQL, Bootstrap, etc.
- **Design**: Photoshop, Illustrator, Figma, etc.

### 4. Projects

Update your projects (Lines 145-290). For each project:
```html
<div class="project-card">
  <div class="project-img">
    <img src="./images/YOUR_PROJECT_IMAGE.png" alt="project description">
  </div>
  <div class="project-info">
    <p class="project-text">Your Project Description</p>
    <strong class="project-title">
      <span class="icon-span">
        <!-- Add technology icons here -->
      </span>
      <a class="link-project" href="YOUR_PROJECT_URL" target="_blank">
        <span>VISIT</span>
      </a>
    </strong>
  </div>
</div>
```

### 5. Google Maps

Replace the embedded map URL (Line 349) with your location:
- Visit [Google Maps](https://www.google.com/maps)
- Search for your location
- Click "Share" → "Embed a map"
- Copy the iframe code and replace the existing one

### 6. Color Scheme

Customize colors in `css/styles.css`:
- Primary colors are defined in the root or throughout the stylesheet
- Wave animations colors (Line 59-61 in `index.html`)

### 7. Favicon

Replace `images/favicon.png` with your own favicon (Line 12)

## 📁 Project Structure

```
Free-Portfolio/
│
├── index.html              # Main HTML file
├── scroll.js               # JavaScript for scroll animations
│
├── css/
│   ├── styles.css          # Main stylesheet
│   ├── responsive.css      # Responsive design rules
│   └── scroll.css          # Scroll animation styles
│
├── images/
│   ├── favicon.png         # Website favicon
│   ├── man.png             # Profile image
│   ├── web.png             # Project placeholder images
│   ├── adobe-photoshop.256x256.png
│   └── adobe-illustrator.256x256.png
│
├── README.md               # Documentation (this file)
└── LICENSE                 # MIT License
```

## 🎨 Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with animations
- **JavaScript**: Smooth scrolling and interactive elements
- **Font Awesome 6.5.2**: Icon library
- **SVG**: Wave animations
- **Google Maps**: Embedded location map
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🤝 Contributing

Contributions are welcome! If you'd like to improve this template:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

⭐ If you find this template helpful, please consider giving it a star!
