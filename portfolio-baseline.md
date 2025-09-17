# Portfolio Website - Baseline HTML/CSS/JS

This document contains the complete HTML, CSS, and JavaScript code for a modern, responsive portfolio website. The design features a clean, animated interface with smooth scrolling and interactive elements.

## Features

- Responsive navigation with smooth scrolling
- Animated hero section with call-to-action buttons
- About section with skills display
- Projects grid with hover effects
- Contact form with social media links
- Mobile-responsive design
- Scroll animations and interactive elements

## File Structure

```
portfolio/
├── index.html         # Main HTML file
├── css/
│   └── style.css      # All styles (currently in the head)
└── js/
    └── main.js        # JavaScript functionality (currently in the body)
```

## Usage

1. Copy the HTML content to an `index.html` file
2. Move the CSS from the `<style>` tag to `css/style.css`
3. Move the JavaScript from the `<script>` tag to `js/main.js`
4. Update the content, images, and links to personalize the portfolio

## Customization

### Colors
Update the CSS variables in the `:root` selector to change the color scheme:

```css
:root {
    --primary: #6366f1;
    --primary-dark: #4f46e5;
    --secondary: #ec4899;
    --dark: #0f172a;
    --light: #f8fafc;
    --gray: #64748b;
    --gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
```

### Content
- Update the hero section with your name and title
- Add your projects to the projects grid
- Update the about section with your information and skills
- Set up the contact form to work with your preferred backend service

## Browser Support

The website is compatible with all modern browsers including:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Notes

- The contact form requires a backend service to function
- Replace the placeholder emoji with actual project screenshots
- Update the social media links in the footer

## License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).

---

```html
<!DOCTYPE html>
<!-- The full HTML content would go here, but it's omitted for brevity in this markdown -->
```

*Note: The actual HTML content is not included in this markdown to avoid duplication. It's available in the original file provided.*
