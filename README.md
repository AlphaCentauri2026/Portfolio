# Personal Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. Features a clean design, smooth animations, and mobile-friendly layout.

## 🚀 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Interactive Elements**: Hover effects, smooth scrolling, and dynamic navigation
- **Contact Form**: Functional contact form with validation
- **Mobile Navigation**: Hamburger menu for mobile devices
- **SEO Optimized**: Semantic HTML structure and meta tags
- **Fast Loading**: Optimized CSS and JavaScript

## 📁 File Structure

```
Portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
├── README.md           # This file
└── public/
    └── images/
        ├── profile/    # Profile photos
        ├── projects/   # Project screenshots
        ├── icons/      # Custom icons
        └── backgrounds/ # Background images
```

## 🎨 Customization Guide

### 1. Personal Information

Update the following in `index.html`:

- **Name**: Replace "Your Name" with your actual name
- **Title**: Update the hero subtitle to match your profession
- **Description**: Modify the hero description to reflect your expertise
- **Contact Information**: Update email, phone, and location in the contact section

### 2. About Section

- **Bio**: Update the paragraphs in the about section
- **Statistics**: Modify the numbers and labels in the stats section
- **Experience**: Adjust years of experience, projects completed, etc.

### 3. Projects

Replace the sample projects with your own:

- **Project Images**: Replace the placeholder icons with actual project screenshots
- **Project Descriptions**: Update project details and technologies used
- **Links**: Add actual GitHub and live demo links
- **Technologies**: Update the tech tags to match your project stack

### 4. Skills

Customize the skills section:

- **Frontend Skills**: Update HTML, CSS, JavaScript, and framework skills
- **Backend Skills**: Modify server-side technologies
- **Tools**: Update development tools and platforms
- **Icons**: Font Awesome icons are used - you can change them from [Font Awesome](https://fontawesome.com/)

### 5. Contact Information

Update the contact section:

- **Email**: Your professional email address
- **Phone**: Your contact number
- **Location**: Your city and country
- **Social Links**: Update GitHub, LinkedIn, Twitter, and Instagram links

### 6. Styling

Customize the design in `styles.css`:

- **Colors**: Update the color scheme by modifying CSS variables
- **Fonts**: Change the font family (currently using Inter)
- **Layout**: Adjust spacing, padding, and margins
- **Animations**: Modify transition effects and animations

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript**: Interactive functionality
- **Font Awesome**: Icons
- **Google Fonts**: Inter font family

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 🚀 Deployment

### Option 1: GitHub Pages

1. Push your code to a GitHub repository
2. Go to repository Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://username.github.io/repository-name`

### Option 2: Netlify

1. Drag and drop your project folder to [Netlify](https://netlify.com)
2. Your site will be deployed instantly
3. You can connect your GitHub repository for automatic deployments

### Option 3: Vercel

1. Connect your GitHub repository to [Vercel](https://vercel.com)
2. Deploy with one click
3. Automatic deployments on every push

## 📝 Customization Tips

### Adding Your Photo

1. Replace the profile placeholder in the hero section:
```html
<div class="hero-image">
    <img src="path/to/your/photo.jpg" alt="Your Name" class="profile-photo">
</div>
```

2. Add CSS for the photo:
```css
.profile-photo {
    width: 300px;
    height: 300px;
    border-radius: 50%;
    object-fit: cover;
    border: 3px solid rgba(255, 255, 255, 0.2);
}
```

### Adding Project Images

1. Replace placeholder divs with actual images:
```html
<div class="project-image">
    <img src="path/to/project-image.jpg" alt="Project Name">
</div>
```

2. Add CSS for project images:
```css
.project-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}
```

### Custom Color Scheme

Update the main colors in `styles.css`:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #fbbf24;
    --text-color: #1f2937;
    --light-bg: #f8fafc;
    --gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
```

## 🔧 Advanced Customization

### Adding New Sections

1. Add HTML structure in `index.html`
2. Add corresponding CSS in `styles.css`
3. Update navigation menu
4. Add JavaScript functionality if needed

### Form Integration

The contact form currently shows a success message. To make it functional:

1. Use a form service like Formspree, Netlify Forms, or EmailJS
2. Update the form action and method
3. Handle form submission in JavaScript

### Analytics

Add Google Analytics or other tracking:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 📞 Support

If you need help customizing your portfolio:

1. Check the HTML comments for guidance
2. Review the CSS structure for styling options
3. Examine the JavaScript for functionality
4. Use browser developer tools to experiment

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Happy coding! 🎉**

Your portfolio is now ready to showcase your skills and projects to the world! 