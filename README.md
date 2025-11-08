# Macra - AI-Powered Macro Tracking Website

A modern, responsive marketing website for Macra, an AI-powered macro nutrition tracking iOS app. Built with vanilla HTML, CSS, and JavaScript for optimal performance.

## 🎯 Overview

This website showcases Macra's features including:
- AI-powered nutrition tracking with Gemini integration
- GitHub-style contribution calendar for goal visualization
- **Ranked global leaderboard system** for competitive tracking
- Beautiful dark theme with electric blue accents
- Smooth animations and interactive elements

## 🚀 Quick Start

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/emajithia3-max/MacraWebsite.git
cd MacraWebsite
```

2. Open in browser:
```bash
# Using Python's built-in server
python3 -m http.server 8000

# Or using Node.js
npx serve

# Or simply open index.html in your browser
open index.html
```

3. Visit `http://localhost:8000` in your browser

## 📁 Project Structure

```
MacraWebsite/
├── index.html          # Main HTML file with semantic structure
├── css/
│   └── style.css       # Complete styling with Macra design system
├── js/
│   └── main.js         # Animations, interactions, and scroll effects
└── README.md          # This file
```

## 🎨 Design System

### Color Palette
- **Primary Blue**: `#3B82F6` - Electric blue for CTAs and accents
- **Deep Blue**: `#1E40AF` - Gradient component
- **Lavender**: `#A78BFA` - Secondary accent color
- **Background Primary**: `#0A0E1A` - Very dark blue-black
- **Background Secondary**: `#111827` - Dark slate
- **Surface**: `#1F2937` - Card backgrounds
- **Text High**: `#F9FAFB` - Primary text
- **Text Mid**: `#9CA3AF` - Secondary text
- **Text Low**: `#6B7280` - Tertiary text

### Typography
- **Font Family**: Exo 2 (Google Fonts)
- **Headings**: 700-900 weight (Bold/ExtraBold)
- **Body**: 500-600 weight (Medium/SemiBold)
- **Style**: All caps for labels and badges with letter-spacing

### Components
- **Border Radius**: 8-16px for modern, rounded corners
- **Shadows**: Layered shadows with blue glow effects
- **Animations**: 0.3s ease transitions for smooth interactions
- **Glass Morphism**: Backdrop blur with subtle gradients

## 🌐 Deployment

### GitHub Pages

1. Push your code to GitHub:
```bash
git add .
git commit -m "Initial website deployment"
git push origin main
```

2. Enable GitHub Pages:
   - Go to repository Settings
   - Navigate to Pages section
   - Select branch: `main`
   - Select folder: `/ (root)`
   - Click Save

3. Your site will be available at:
   `https://emajithia3-max.github.io/MacraWebsite/`

### Vercel (Recommended for Production)

1. Install Vercel CLI:
```bash
npm i -g vercel
```

2. Deploy:
```bash
vercel
```

3. Follow the prompts to link your project

4. For production deployment:
```bash
vercel --prod
```

### Netlify

1. Install Netlify CLI:
```bash
npm i -g netlify-cli
```

2. Deploy:
```bash
netlify deploy
```

3. For production:
```bash
netlify deploy --prod
```

### Alternative: Drag & Drop Deployment

Both Vercel and Netlify support drag-and-drop deployment:
1. Visit [vercel.com](https://vercel.com) or [netlify.com](https://netlify.com)
2. Drag the project folder onto the deployment zone
3. Your site will be live in seconds!

## ✨ Features

### Navigation
- Fixed navbar with blur effect
- Smooth scroll to sections
- Mobile-responsive hamburger menu
- Active scroll indicator

### Hero Section
- Animated gradient orbs background
- Parallax scrolling effects
- Animated statistics counter
- Dual CTAs (Download + Preview)

### Leaderboard Highlight (Featured)
- **Prominent global leaderboard showcase**
- Real-time ranking visualization
- Streak multiplier system
- Interactive leaderboard entries with hover effects
- Competitive badges and achievements
- Staggered animation on scroll

### Features Grid
- 9 feature cards in 3x3 responsive grid
- Hover animations with glow effects
- Icon-based visual hierarchy
- Signature feature highlight (Contribution Calendar)

### Preview Section
- 4 interactive app mockups
- iPhone frame with realistic screens
- Mock dashboard, calendar, chat, and detail views
- 3D transform on hover
- Lazy loading support

### Download CTA
- Large App Store button
- Compatibility information
- Feature highlights (Free, No Ads, No Subscriptions)

### Footer
- Multi-column layout
- Social media links
- Legal links (Privacy, Terms)
- Copyright notice

## 🔧 Customization

### Update App Store Link

In `index.html`, update the placeholder links:
```html
<!-- Line ~450 -->
<a href="YOUR_APP_STORE_LINK" class="btn btn-appstore">
```

### Modify Statistics

In `index.html`, update the hero stats:
```html
<!-- Lines ~95-110 -->
<div class="stat-value">10K+</div>  <!-- Update number -->
<div class="stat-value">4.9★</div>  <!-- Update rating -->
```

### Change Colors

In `css/style.css`, modify the CSS variables:
```css
:root {
    --color-primary-blue: #3B82F6;  /* Change primary color */
    --color-deep-blue: #1E40AF;     /* Change secondary color */
    /* ... other colors */
}
```

### Add Custom Sections

1. Add HTML in `index.html`
2. Style in `css/style.css`
3. Add animations in `js/main.js` if needed

## 📊 Performance

### Optimization Features
- Vanilla JavaScript (no heavy frameworks)
- Intersection Observer for scroll animations
- Debounced scroll events
- Lazy loading support for images
- Minimal CSS with efficient selectors
- Google Fonts with display swap

### Expected Lighthouse Scores
- **Performance**: 95+
- **Accessibility**: 95+
- **Best Practices**: 95+
- **SEO**: 100

## 🔍 SEO

### Included Optimizations
- Semantic HTML5 structure
- Meta description and keywords
- Open Graph tags for social sharing
- Twitter Card tags
- Proper heading hierarchy
- Alt text ready for images
- Mobile-responsive design
- Fast loading times

### To Improve SEO Further
1. Add `sitemap.xml`
2. Add `robots.txt`
3. Submit to Google Search Console
4. Add structured data (JSON-LD)
5. Optimize images with WebP format
6. Add real app screenshots

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile Safari (iOS 12+)
- Chrome Mobile (Android 8+)

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Custom properties, Grid, Flexbox, Animations
- **JavaScript (ES6+)**: Intersection Observer, Event Listeners
- **Google Fonts**: Exo 2 font family
- **No dependencies**: Zero npm packages required

## 📝 Sections Breakdown

1. **Navigation** - Fixed navbar with smooth scroll
2. **Hero** - Eye-catching introduction with animated background
3. **Leaderboard Highlight** - Featured competitive ranking system (PROMINENTLY DISPLAYED)
4. **Features** - 9-card grid showcasing app capabilities
5. **Preview** - Interactive app mockups
6. **Download CTA** - Clear call-to-action for App Store
7. **Footer** - Links and information

## 🎯 Key Highlights

### Ranked Leaderboard System
The website prominently features the **global leaderboard** system, showcasing:
- Real-time competitive rankings
- Streak-based scoring system
- Exclusive badges for top performers
- Global and filtered leaderboards
- Visual hierarchy with medal indicators
- User position highlighting

This is the **most prominently featured** aspect of the app, positioned early in the page flow to immediately communicate the competitive and gamified nature of Macra.

## 🤝 Contributing

This is a marketing website for Macra. For contributions:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

© 2024 Macra. All rights reserved.

## 📧 Support

For questions or support:
- Email: support@macra.app
- Website: https://macra.app

## 🚀 Next Steps

1. **Add Real Screenshots**: Replace mockup content with actual app screenshots
2. **Update App Store Link**: Add the real App Store URL when available
3. **Add Analytics**: Integrate Google Analytics or similar
4. **Create Favicon**: Design and add a proper favicon
5. **Privacy Policy**: Create and link privacy policy page
6. **Terms of Service**: Create and link terms page
7. **Blog/News**: Consider adding a blog section for updates
8. **Email Capture**: Add newsletter signup for launch notifications

---

Built with ❤️ for health-conscious individuals tracking their nutrition goals.

**Track your macros. Master your goals. Dominate the leaderboard.** 🎯
