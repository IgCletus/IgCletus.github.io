# Portfolio Website Template

A modern, responsive portfolio website template inspired by professional resume designs. This template is perfect for showcasing your skills, experience, and projects.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional design with smooth animations
- **Interactive Navigation**: Sidebar navigation with smooth section transitions
- **Portfolio Filtering**: Filter portfolio items by category (All, App, Web, Card)
- **Contact Form**: Functional contact form with validation
- **Social Media Links**: Easy-to-customize social media integration
- **Easy Customization**: Simple HTML, CSS, and JavaScript structure

## Sections Included

1. **Home**: Hero section with your name and professional title
2. **About**: Personal information and professional summary
3. **Resume**: Education and professional experience
4. **Portfolio**: Showcase your projects with filtering options
5. **Services**: List your professional services
6. **Contact**: Contact information and contact form

## How to Use

### 1. Customize Your Information

Edit the `index.html` file and replace the placeholder content with your own information:

- Replace "YOUR NAME" with your actual name
- Update "Your Professional Title" with your job title
- Replace placeholder text in the About section
- Add your education and work experience in the Resume section
- Update portfolio items with your actual projects
- Customize services with your offerings
- Update contact information

### 2. Add Your Photos

- Replace the placeholder profile image URL in the Home section
- Add your actual portfolio project images
- Optimize images for web (recommended: JPG/PNG, max 1MB per image)

### 3. Customize Colors and Styling

Edit the `style.css` file to match your brand:

- Change the primary color (currently `#4a90e2`) to your preferred color
- Modify fonts, spacing, and other design elements as needed
- The CSS is well-organized with clear comments for easy customization

### 4. Update Social Media Links

In the `index.html` file, update the social media links in the sidebar:

```html
<div class="social-links">
    <a href="your-linkedin-url" class="social-link"><i class="fab fa-linkedin"></i></a>
    <a href="your-github-url" class="social-link"><i class="fab fa-github"></i></a>
    <a href="your-twitter-url" class="social-link"><i class="fab fa-twitter"></i></a>
    <!-- Add or remove social links as needed -->
</div>
```

## Deploying to GitHub Pages

### Method 1: Direct Upload

1. Create a new repository on GitHub named `your-username.github.io` (replace `your-username` with your actual GitHub username)
2. Upload all the template files to this repository
3. Go to repository Settings > Pages
4. Select "Deploy from a branch" and choose "main" branch
5. Your site will be available at `https://your-username.github.io`

### Method 2: Custom Repository

1. Create a new repository with any name (e.g., `portfolio`)
2. Upload all the template files to this repository
3. Go to repository Settings > Pages
4. Select "Deploy from a branch" and choose "main" branch
5. Your site will be available at `https://your-username.github.io/repository-name`

### Method 3: Using Git (Command Line)

```bash
# Clone or create your repository
git clone https://github.com/your-username/your-username.github.io.git
cd your-username.github.io

# Copy template files to the repository
# (copy all files from this template)

# Add, commit, and push
git add .
git commit -m "Add portfolio website"
git push origin main
```

## File Structure

```
portfolio-template/
├── index.html          # Main HTML file
├── style.css           # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Browser Support

This template works on all modern browsers:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Customization Tips

1. **Colors**: Search for `#4a90e2` in the CSS file to change the primary color
2. **Fonts**: The template uses "Poppins" font from Google Fonts (loaded via FontAwesome CDN)
3. **Icons**: Uses FontAwesome icons - you can replace them with other FontAwesome icons
4. **Layout**: The CSS Grid and Flexbox layout makes it easy to modify the structure
5. **Animations**: Smooth transitions and hover effects are included for a professional feel

## Contact Form

The contact form includes basic JavaScript validation. For a fully functional form, you'll need to:

1. Set up a backend service (like Formspree, Netlify Forms, or your own server)
2. Update the form action attribute in the HTML
3. Modify the JavaScript to handle form submission properly

## License

This template is free to use for personal and commercial projects. No attribution required, but appreciated!

## Support

If you need help customizing this template or have questions, feel free to reach out or create an issue in the repository.

---

**Happy coding! 🚀**

