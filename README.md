# Muhammad Shumail Affan - Cloud Portfolio

A modern, responsive portfolio website showcasing my skills, experience, and projects in cloud computing and software engineering.

## 🚀 Features

- **Responsive Design**: Mobile-first approach with Bootstrap 5 and Tailwind CSS
- **Dark/Light Theme**: Toggle between dark and light modes with persistent preference
- **Modern UI**: Glassmorphism effects, smooth animations, and gradient accents
- **Contact Form**: Functional contact form with validation
- **Cloud-Ready**: Optimized for deployment on Netlify, Vercel, or any static hosting platform

## 🛠️ Tech Stack

- **HTML5**: Semantic markup
- **CSS3**: Custom styles with CSS variables for theming
- **JavaScript (ES6+)**: Interactive features and animations
- **Bootstrap 5**: Responsive grid and components
- **Tailwind CSS**: Utility-first styling
- **Bootstrap Icons**: Icon library

## 📦 Project Structure

```
Cloud/
├── index.html          # Main HTML file
├── style.css           # Custom styles and theme variables
├── script.js           # JavaScript for interactivity
├── netlify.toml        # Netlify deployment config
├── vercel.json         # Vercel deployment config
└── README.md           # Project documentation
```

## 🌐 Deployment

### Option 1: Netlify (Recommended)

1. **Install Netlify CLI** (optional):
   ```bash
   npm install -g netlify-cli
   ```

2. **Deploy via Netlify CLI**:
   ```bash
   netlify deploy --prod
   ```

3. **Or Deploy via Netlify Dashboard**:
   - Go to [Netlify](https://app.netlify.com)
   - Drag and drop the `Cloud` folder
   - Your site will be live instantly!

### Option 2: Vercel

1. **Install Vercel CLI**:
   ```bash
   npm install -g vercel
   ```

2. **Deploy**:
   ```bash
   vercel --prod
   ```

### Option 3: GitHub Pages

1. Push code to GitHub repository
2. Go to Settings → Pages
3. Select branch and root folder
4. Save and your site will be live!

### Option 4: Local Development

Simply open `index.html` in your browser, or use a local server:

```bash
# Python 3
python -m http.server 8000

# Node.js (with http-server)
npx http-server -p 8000
```

Then visit `http://localhost:8000`

## ✨ Features Breakdown

### Theme Toggle
- Persistent theme preference using localStorage
- Smooth transitions between dark and light modes
- Custom CSS variables for easy theming

### Contact Form
- Client-side validation
- Success/error feedback
- Ready for backend integration (EmailJS, Formspree, etc.)

### Animations
- Intersection Observer API for scroll animations
- Smooth hover effects
- Glassmorphism card effects

## 🎨 Customization

### Update Colors
Edit CSS variables in `style.css`:

```css
:root {
    --primary: #38bdf8;
    --secondary: #818cf8;
    /* ... more variables */
}
```

### Update Content
Edit `index.html` to update:
- Personal information
- Projects
- Skills
- Experience
- Contact details

## 📧 Contact Form Integration

To make the contact form functional, integrate with:

1. **EmailJS**: Add EmailJS SDK and update `script.js`
2. **Formspree**: Add action URL to form element
3. **Netlify Forms**: Add `netlify` attribute to form
4. **Custom Backend**: Create API endpoint and update fetch URL

## 📄 License

© 2025 Muhammad Shumail Affan. All rights reserved.

## 🤝 Connect

- **Email**: shumailaffan502@gmail.com
- **Phone**: +92-321-4605158
- **Location**: Lahore, Pakistan

---

**Built with ❤️ using HTML, CSS, JavaScript, Bootstrap 5, and Tailwind CSS**
