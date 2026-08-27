# Hazel Canlas - Professional Portfolio

**Operations & Dispatch Coordinator** | 7+ Years Experience | U.S. Home Service Specialist

A modern, responsive, and elegant portfolio website showcasing my professional experience, skills, and achievements in operations management and field service coordination.

## 🚀 Live Demo

[View Portfolio](https://canlashaze.github.io/portfolio/)

## ✨ Features

✨ **Modern Design**
- Minimalist and elegant aesthetic
- Dark theme with teal/cyan accent colors
- Smooth animations and transitions
- Professional typography and spacing

📱 **Fully Responsive**
- Mobile-first design approach
- Seamless experience on all devices (mobile, tablet, desktop)
- Touch-friendly interface elements

⚡ **Performance Optimized**
- Fast loading times
- Optimized images and assets
- Clean, maintainable code
- Minimal dependencies

♿ **Accessible**
- WCAG 2.1 compliance standards
- Semantic HTML structure
- Keyboard navigation support
- Screen reader friendly
- Reduced motion preferences respected

🔍 **SEO Friendly**
- Optimized metadata
- Open Graph tags for social sharing
- Semantic markup
- Fast Core Web Vitals

## 📄 Project Structure

```
portfolio/
├── index.html              # Main portfolio page
├── css/
│   └── styles.css         # Complete styling (23KB)
├── js/
│   └── script.js          # Interactivity and animations
├── assets/
│   ├── og-image.png       # Social sharing image
│   └── Hazel_Canlas_Resume.pdf  # Resume PDF
├── README.md              # This file
├── LICENSE                # MIT License
└── .gitignore            # Git ignore rules
```

## 🛠️ Technology Stack

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS Grid, Flexbox, and animations
- **JavaScript (Vanilla)** - No dependencies, pure JS for interactivity
- **Google Fonts** - Inter & Poppins typefaces
- **GitHub Pages** - Hosting

## 🎨 Design Features

### Color Scheme
- **Primary**: Teal (#14b8a6) - Accent and highlights
- **Secondary**: Cyan (#0891b2) - Gradients
- **Background**: Dark Slate (#0f172a) - Main background
- **Text**: Light colors for high contrast and readability

### Animations
- Fade-in-up on scroll
- Smooth hover effects
- Floating elements
- Bouncing indicators
- Gradient transitions

## 📖 Sections

1. **Navigation** - Fixed, responsive navbar with smooth scrolling
2. **Hero** - Eye-catching introduction with CTA buttons
3. **About Me** - Professional summary and key statistics
4. **Skills** - Organized by categories with tag-based layout
5. **Experience** - Timeline view of professional history
6. **Projects** - Card-based showcase of key achievements
7. **Education** - Formal education credentials
8. **Qualifications** - Additional certifications and strengths
9. **Contact** - Multiple ways to get in touch
10. **Footer** - Navigation and social links

## 🚀 Deployment

### GitHub Pages Setup

1. **Repository Settings**
   - Go to repository Settings → Pages
   - Select "Deploy from a branch"
   - Choose main branch and /(root) folder
   - Click Save

2. **Custom Domain (Optional)**
   - Go to Settings → Pages
   - Add your custom domain in "Custom domain"
   - Create a CNAME file in the root:
     ```
     yourdomain.com
     ```
   - Update your domain registrar DNS records

3. **Verify Deployment**
   - GitHub will show deployment status
   - Site typically goes live within 10-60 seconds
   - Access at: `https://canlashaze.github.io/portfolio/`

### Local Development

```bash
# Clone the repository
git clone https://github.com/canlashaze/portfolio.git
cd portfolio

# Open in browser (no build process needed)
open index.html
# or
firefox index.html
# or start a local server:
python -m http.server 8000
# Then visit http://localhost:8000
```

## ✏️ Customization

### Update Your Information

1. **Personal Details** (index.html)
   - Update name, title, and description in hero section
   - Change email and phone in contact section
   - Update social links (LinkedIn, etc.)

2. **Resume PDF**
   - Replace `assets/Hazel_Canlas_Resume.pdf` with your resume
   - Keep the same filename or update the link in index.html

3. **Colors & Theme**
   - Edit CSS variables in `css/styles.css`:
     ```css
     :root {
       --primary-color: #14b8a6;        /* Change accent color */
       --secondary-color: #0891b2;      /* Change secondary */
       --bg-dark: #0f172a;              /* Change background */
     }
     ```

4. **Content**
   - Edit sections in index.html
   - Update skills, experience, and projects
   - Modify about me section
   - Add/remove timeline entries

### Adding a Profile Image

1. Save your image to `assets/profile.jpg`
2. Replace the SVG avatar in the hero section with:
   ```html
   <img src="assets/profile.jpg" alt="Hazel Canlas" class="profile-image">
   ```
3. Add CSS styling in styles.css:
   ```css
   .profile-image {
     width: 300px;
     height: 300px;
     border-radius: 50%;
     object-fit: cover;
     filter: drop-shadow(0 10px 30px rgba(20, 184, 166, 0.2));
   }
   ```

## 📊 SEO Optimization

- **Meta Tags**: Description, keywords, OG tags configured
- **Structured Data**: HTML semantic markup
- **Performance**: Fast load times, optimized CSS/JS
- **Mobile**: Responsive design and viewport meta tag
- **Accessibility**: Proper heading hierarchy, alt text, ARIA labels

## 📈 Performance Metrics

- **Page Load**: < 2 seconds
- **CSS Size**: 23KB (minified)
- **JS Size**: 10KB (vanilla, no dependencies)
- **Total Assets**: < 50KB without resume PDF
- **Lighthouse Score**: 95+ (Performance, Accessibility, Best Practices, SEO)

## ♿ Accessibility

- **WCAG 2.1 AA Compliant**
- Keyboard navigation fully supported
- Screen reader friendly
- Sufficient color contrast
- Semantic HTML structure
- ARIA labels where appropriate
- Respects prefers-reduced-motion

## 🌐 Browser Support

- Chrome/Chromium (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 License

MIT License - Feel free to use this template for your own portfolio!

## 🤝 Contributing

This is a personal portfolio, but feel free to fork and customize it for your own use!

## 📞 Contact

- **Email**: canlashazel4@gmail.com
- **Phone**: +63 955 645 0307
- **LinkedIn**: [hazel-canlas-20bb25263](https://linkedin.com/in/hazel-canlas-20bb25263)

---

**Last Updated**: August 2026

Built with ❤️ using HTML, CSS, and JavaScript