# Mohamed Alkamel Portfolio Website Template

A modern, responsive portfolio website template populated with Mohamed Alkamel's professional information. This template is ready to use and can be easily customized with your own content.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean and professional design with smooth animations
- **Interactive Navigation**: Sidebar navigation with smooth section transitions
- **Portfolio Filtering**: Filter portfolio items by category (All, App, Web, Card)
- **Contact Form**: Functional contact form with validation
- **Social Media Links**: Easy-to-customize social media integration
- **Pre-populated Content**: Contains Mohamed Alkamel's professional information

## Sections Included

1. **Home**: Hero section with name and professional title
2. **About**: Personal information and professional summary
3. **Resume**: Education and professional experience
4. **Portfolio**: Showcase of projects with filtering options
5. **Services**: List of professional services
6. **Contact**: Contact information and contact form

## Content Included

This template is pre-populated with:

### Personal Information
- **Name**: Mohamed Alkamel
- **Title**: GIS Specialist
- **Birthday**: 02 Aprile 1995
- **Nationality**: Sudanese
- **Location**: Abu Dhabi, UAE
- **Email**: Alkamelgis@gmail.com, Alkamelgeo@gmail.com
- **Phone**: +971 55351242, +249 920097574

### Education
- **B.Sc. GIS, Cartography and Remote Sensing** (2012-2017) - University of Khartoum
- **Diploma Geographic Information Systems (GIS) Specialization** (2017-2018) - US Davis, California

### Professional Experience
- **GIS Analyst** - Dibba Municipality (April 2023 - present)
- **GIS Specialist** - Global Surveying Projects (July 2021 - March 2023)
- **GIS Specialist** - Lavajet Company (June 2020 - July 2021)
- **GIS Developer - Technical Officer** - World Health Organization (Jan 2019 - May 2020)
- **GIS Specialist** - Federal Ministry of Health (Nov 2017 - Dec 2018)
- **Geo-Marketing Developer & GIS Engineering** - AFROMAP (Jan 2018 - Nov 2018)

### Services
- Geo-marketing
- Spreadsheet Management
- Infographics & Maps Visualization
- Geo-databases
- Graphic Design Map
- Spatial Analysis

## How to Customize

### 1. Replace Personal Information

Edit the `index.html` file and update:

- Replace "MOHAMED ALKAMEL" with your name
- Update "GIS Specialist" with your professional title
- Replace all personal information in the About section
- Update education and work experience in the Resume section
- Customize services with your offerings
- Update contact information

### 2. Add Your Photos

- Replace the profile image URL in the Home section with your photo
- Update portfolio project images with your actual work
- Optimize images for web (recommended: JPG/PNG, max 1MB per image)

### 3. Customize Colors and Styling

Edit the `style.css` file to match your brand:

- Change the primary color (currently `#4a90e2`) to your preferred color
- Modify fonts, spacing, and other design elements as needed

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

### Method 1: Direct Upload (Easiest)

1. Create a new repository on GitHub named `your-username.github.io`
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
# Clone your repository
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
portfolio-template-populated/
├── index.html          # Main HTML file with populated content
├── style.css           # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Important Notes

- **Image Sources**: The template currently uses image URLs from the original website. You may want to download these images and host them locally in your repository for better reliability.
- **Contact Form**: The contact form includes basic JavaScript validation. For a fully functional form, you'll need to set up a backend service.
- **Customization**: All content can be easily modified by editing the HTML file.

## Browser Support

This template works on all modern browsers:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This template is free to use for personal and commercial projects.

---

**Ready to deploy! 🚀**

