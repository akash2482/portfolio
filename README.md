# My Portfolio Website

Welcome to my personal portfolio website! This is a modern, responsive portfolio built with HTML, CSS, and JavaScript.

## Features

- **Responsive Design** - Works perfectly on all devices (desktop, tablet, mobile)
- **Modern UI** - Clean and professional design with smooth animations
- **Multiple Sections**:
  - Hero/Introduction section
  - About me
  - Featured projects
  - Skills showcase
  - Contact form
  - Social media links
- **Smooth Navigation** - Sticky navbar with smooth scrolling
- **Project Cards** - Display your projects with descriptions and links
- **Contact Form** - Get in touch section for visitors

## File Structure

```
portfolio/
├── index.html      # Main HTML file
├── styles.css      # Stylesheet
├── script.js       # JavaScript functionality
└── README.md       # This file
```

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/akash2482/portfolio.git
   cd portfolio
   ```

2. Open `index.html` in your browser or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Or using Node.js
   npx http-server
   ```

3. Visit `http://localhost:8000` in your browser

## Customization

### Change Your Information
- Edit `index.html` to update your name, email, and project details
- Replace placeholder text with your own content
- Update social media links in the contact section

### Modify Colors
Open `styles.css` and update the CSS variables:
```css
:root {
    --primary-color: #667eea;
    --secondary-color: #764ba2;
    --text-color: #333;
}
```

### Add Your Projects
In the Projects section, duplicate the `.project-card` div and update:
- Project title
- Project description
- Technologies used (tags)
- Project links

### Update Skills
Modify the Skills section categories and add your own skills in the `<ul>` elements

## Deployment

### Option 1: GitHub Pages
1. Repository is already set up on GitHub
2. Go to Settings → Pages
3. Select `main` branch as the source
4. Your site will be live at `https://akash2482.github.io/portfolio`

### Option 2: Netlify
1. Connect your GitHub repository to Netlify
2. Deploy automatically on every push
3. Get a free domain or connect your own

### Option 3: Vercel
1. Sign up at vercel.com
2. Import your GitHub repository
3. Deploy with one click

## Technologies Used

- HTML5
- CSS3 (with CSS Variables and Grid)
- Vanilla JavaScript
- Font Awesome Icons

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available under the MIT License.

## Contact

Feel free to reach out for any questions or suggestions!

---

Made with ❤️ by Akash