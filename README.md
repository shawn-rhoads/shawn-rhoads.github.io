# Personal Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. This website is designed to showcase your projects and skills as a software engineer.

## Features

- Responsive design that works on all devices
- Modern and clean user interface
- Smooth scrolling navigation
- Project showcase section
- Skills and about section
- Contact information with social links
- Animated sections on scroll

## Setup Instructions

1. Fork this repository
2. Clone your forked repository to your local machine
3. Customize the content in `index.html` with your personal information
4. Update the styling in `styles.css` if desired
5. Add your projects to the projects section
6. Update social media links in the contact section

## Customization

### Personal Information
Edit the following sections in `index.html`:
- Hero section with your name and title
- About section with your bio
- Skills section with your technical skills
- Projects section with your work
- Contact section with your social links

### Styling
The website uses CSS variables for easy customization. Edit the following in `styles.css`:
```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #1e40af;
    --text-color: #1f2937;
    --light-text: #6b7280;
    --background: #ffffff;
    --section-bg: #f3f4f6;
}
```

### Adding Projects
To add a new project, copy and paste the following structure in the projects section:
```html
<div class="project-card">
    <div class="project-image">
        <img src="path-to-your-image" alt="Project Name">
    </div>
    <div class="project-info">
        <h3>Project Name</h3>
        <p>Project description</p>
        <div class="project-links">
            <a href="#" class="btn small">View Demo</a>
            <a href="#" class="btn small">GitHub</a>
        </div>
    </div>
</div>
```

## Deployment

This website can be easily deployed to GitHub Pages:

1. Go to your repository settings
2. Scroll down to the GitHub Pages section
3. Select the main branch as the source
4. Your site will be published at `https://yourusername.github.io/repository-name`

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is open source and available under the [MIT License](LICENSE). 