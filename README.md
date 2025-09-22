# Today in History - Landing Page

Official landing page for the Today in History Chrome Extension.

## 🎨 Design Features

- **Consistent Theming**: Uses the same purple gradient theme as the Chrome extension (`#4f46e5` to `#7c3aed`)
- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Modern UI**: Glass morphism effects, smooth animations, and elegant card designs
- **Interactive Demo**: Live preview of the extension interface with working controls
- **Performance Optimized**: Fast loading with optimized images and code

## 📁 File Structure

```
today-in-history-website/
├── index.html           # Main landing page
├── privacy-policy.html  # Privacy policy page
├── styles.css          # Main stylesheet
├── package.json        # Project configuration
├── vercel.json         # Vercel deployment configuration
└── README.md           # This file
```

## 🚀 Local Development

```bash
# Method 1: Using Python simple server
python -m http.server 8000

# Method 2: Using Node.js live-server
npx live-server

# Method 3: Direct browser opening
open index.html
```

Then visit: http://localhost:8000

## 🌐 Deployment Options

### 1. Vercel (Recommended)
1. Upload project files to Vercel
2. Automatic deployment and updates
3. Custom domain support
4. Built-in analytics

### 2. Netlify
1. Drag entire folder to netlify.com
2. Get free `.netlify.app` domain
3. Continuous deployment support

## 🔗 Privacy Policy URL

After deployment, the privacy policy URL will be:
```
https://history.thebesttools.net/privacy-policy
```

This URL can be used in the Chrome Web Store privacy policy field.

## ✨ Features

### Landing Page Sections
- **Hero Section**: Extension introduction with 3D mockup
- **Features Grid**: 6 key feature highlights with icons
- **Interactive Preview**: Working demo with theme/view toggles
- **Call-to-Action**: Installation prompts and benefits
- **Footer**: Links, resources, and contact information

### Interactive Elements
- **Extension Mockup**: 3D-animated preview window
- **Live Demo**: Functional tabs, theme switching, and view modes
- **Smooth Scrolling**: Anchor link navigation
- **Mobile Menu**: Responsive navigation for mobile devices
- **Header Effects**: Scroll-based transparency changes

### Demo Features
- **Tab Switching**: Events, Births, Deaths categories
- **Theme Toggle**: Light/dark mode preview
- **View Toggle**: Normal/compact mode switching
- **Date Picker**: Historical date selection
- **Sample Data**: Realistic historical events display

## 🎯 SEO & Performance

- **Meta Tags**: Complete OpenGraph and Twitter Card support
- **Semantic HTML**: Proper heading structure and landmarks
- **Fast Loading**: Optimized CSS and inline critical styles
- **Mobile First**: Responsive design with mobile optimization
- **Accessibility**: Keyboard navigation and screen reader support

## 📱 Responsive Breakpoints

- **Desktop**: 1200px+ (Full grid layout)
- **Tablet**: 768px-1199px (Adjusted grid, smaller text)
- **Mobile**: <768px (Single column, stacked layout)

## 🔧 Customization

### Colors
Update these CSS variables in `styles.css`:
```css
:root {
  --primary: #4f46e5;
  --secondary: #7c3aed;
  --accent: #667eea;
  --background: #f8fafc;
}
```

### Content
- **Hero Section**: Update text in index.html around line 50
- **Features**: Modify feature cards around line 100
- **Demo Data**: Edit sampleData object in JavaScript section

### Branding
- **Logo**: Replace emoji in logo-icon class
- **Favicon**: Update the SVG favicon in the head section
- **Title**: Change page titles and meta descriptions

## 📝 Post-Launch Updates

When the Chrome extension is updated:

1. **Update Install Links**: Keep Chrome Web Store URL current
2. **Add Analytics**: Optional Google Analytics or Vercel Analytics
3. **Update Contact Info**: Keep contact information current
4. **Add Reviews**: Include user testimonials and ratings
5. **SEO Optimization**: Add sitemap.xml and robots.txt

## 🎨 Brand Colors

Consistent with Chrome extension:
- **Primary Gradient**: `linear-gradient(135deg, #4f46e5 0%, #7c3aed 100%)`
- **Success**: `#22c55e` (green)
- **Warning**: `#f59e0b` (amber)  
- **Danger**: `#ef4444` (red)
- **Background**: `#f8fafc` (light gray)
- **Card Shadow**: `rgba(0,0,0,0.1)` to `rgba(0,0,0,0.3)`

## 🚀 Performance Tips

- All CSS is inline for critical path optimization
- JavaScript is defer-loaded to not block rendering
- Images use modern formats and proper sizing
- Fonts use system font stack for faster loading

## 📊 Analytics Setup

To add analytics after deployment:

```html
<!-- Google Analytics (optional) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 📄 License

All rights reserved.

## 📞 Support

- **Email**: support@thebesttools.net
- **Chrome Web Store**: <a href="https://chromewebstore.google.com/detail/today-in-history/cdiehfmgdlomnklkkmpoliodmjfblcph">Leave a review or report issues</a>
- **Documentation**: Check this README for common questions

---

Built with ❤️ for the Today in History Chrome Extension
