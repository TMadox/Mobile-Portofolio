# Mohamed Mamdouh - Portfolio Website

A modern, responsive portfolio website showcasing professional experience, published applications, and services as a Senior Flutter Developer.

![Portfolio Website](https://mohamedmamdouh.com/assets/main_logo.png)

## 🌟 Overview

This is a personal portfolio website built to showcase professional work, skills, and expertise in software development. The site features a clean, modern design optimized for both desktop and mobile devices.

**Live Site:** [mohamedmamdouh.com](https://mohamedmamdouh.com)

## ✨ Features

- **Responsive Design** - Fully responsive layout that works seamlessly on all devices
- **Interactive Navigation** - Smooth scrolling with section-based navigation
- **Published Apps Showcase** - Gallery of 13+ published mobile applications
- **Services Section** - Detailed overview of professional services offered
- **About Me** - Comprehensive bio with contact information and professional background
- **Contact Form** - Integrated contact form powered by FormSubmit
- **SEO Optimized** - Meta tags, Open Graph, and Twitter Card support for social sharing
- **Modern UI/UX** - Clean, professional design with smooth animations

## 🛠️ Technologies Used

- **HTML5** - Semantic markup structure
- **CSS3** - Custom styling with modern design patterns
- **Vanilla JavaScript** - Interactive features and smooth scrolling
- **FormSubmit** - Contact form handling without backend code
- **Python HTTP Server** - Local development server

## 📂 Project Structure

```
Mobile-Portofolio/
├── assets/
│   ├── bazaar.jpg          # Coming soon app image
│   ├── main_logo.png       # Site logo and favicon
│   ├── resume.pdf          # Downloadable resume
│   ├── styles.css          # Main stylesheet
│   ├── suit.jpg            # Profile photo
│   └── tawzea.jpg          # Coming soon app image
├── index.html              # Main homepage
├── thank-you.html          # Contact form success page
├── CNAME                   # Custom domain configuration
└── README.md              # This file
```

## 🚀 Getting Started

### Prerequisites

- Python 3.x installed on your machine (or any static file server)
- Modern web browser (Chrome, Firefox, Safari, Edge)

### Local Development

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/Mobile-Portofolio.git
   cd Mobile-Portofolio
   ```

2. **Start the development server**

   ```bash
   python -m http.server 8000
   ```

3. **Open in browser**
   ```
   http://localhost:8000
   ```

### Alternative Servers

If you prefer other methods:

```bash
# Using Node.js http-server
npx http-server -p 8000

# Using PHP
php -S localhost:8000

# Using Live Server (VS Code Extension)
# Right-click index.html → Open with Live Server
```

## 📋 Sections

### 1. About Me

- Personal introduction
- Contact information
- Education background
- Professional experience highlights
- Interests and hobbies

### 2. Services

- Mobile App Development
- UI/UX Design Implementation
- API Integration & Development
- Architecture & Code Review
- Team Leadership & Mentorship
- CI/CD & DevOps

### 3. Published Apps

Showcases 13+ published applications including:

- Diet Watchers
- Soldout
- Crunch
- Siru Maps
- Hayatona Clinics
- Smart Sales
- Tayseer Finance
- Mountain Lakes Bagels
- Misr Radiology Center (MRC)
- Smart Minds
- Meer
- Noah
- Meter

### 4. Coming Soon

Projects currently under development:

- Tawzea (Real Estate Platform)
- National Finance House (NFH)
- Bazaar (Syrian Marketplace)

### 5. Contact

- Contact form
- Email: dev@mohamedmamdouh.com
- Phone: +201061715164
- Location: Giza, Egypt

## 🎨 Customization

### Updating Content

1. **Personal Information**: Edit `index.html` sections with `id="about"`
2. **Skills**: Modify the skill tags in the `.skills-tags` div
3. **Portfolio Items**: Update the app cards in `.apps-grid`
4. **Styles**: Edit `assets/styles.css` for visual customization

### Adding New Apps

To add a new app to the portfolio:

1. Add an app card in the `.apps-grid` section
2. Create a corresponding modal entry in the `appData` object
3. Include app icon URL and details

Example:

```html
<div class="app-card" onclick="openModal('app14')">
  <div class="app-icon">
    <img
      src="your-app-icon-url"
      alt="App Icon"
      style="width: 100%; height: 100%; border-radius: 20px"
    />
  </div>
  <h3 class="app-title">Your App Name</h3>
  <p class="app-description">Your app description...</p>
</div>
```

## 📧 Contact Form Configuration

The contact form uses [FormSubmit](https://formsubmit.co/) for email handling. To configure:

1. Update the form action URL in `index.html`:

   ```html
   <form action="https://formsubmit.co/your-email-hash" method="POST"></form>
   ```

2. Customize the success redirect:
   ```html
   <input
     type="hidden"
     name="_next"
     value="https://yourdomain.com/thank-you.html"
   />
   ```

## 🌐 Deployment

### GitHub Pages

1. Push code to GitHub repository
2. Go to Settings → Pages
3. Select branch (usually `main`)
4. Add CNAME file with your custom domain

### Custom Domain

The `CNAME` file contains the custom domain:

```
mohamedmamdouh.com
```

Configure your DNS settings to point to GitHub Pages:

- Type: A Record
- Host: @
- Value: GitHub Pages IP addresses

## 📱 Social Media Integration

The site includes Open Graph and Twitter Card meta tags for rich social media previews:

- Title: Mohamed Mamdouh — Crafting Digital Solutions
- Description: Crafting digital experiences that make a difference
- Image: Site logo
- Type: Website

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

This project is created for personal portfolio purposes. Feel free to use it as inspiration for your own portfolio.

## 👤 Author

**Mohamed Mamdouh Amer**

- Website: [mohamedmamdouh.com](https://mohamedmamdouh.com)
- Email: dev@mohamedmamdouh.com
- Location: Giza, Egypt

## 🙏 Acknowledgments

- Design inspiration from modern portfolio websites
- Icons and images are either original or properly licensed
- FormSubmit for contact form handling

---

**Note**: This portfolio showcases real projects and professional experience. All app information and links are current as of the last update.
