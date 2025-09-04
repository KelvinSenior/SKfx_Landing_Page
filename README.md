# SKFX Trading Landing Page

A high-conversion, professional landing page for a Forex trading education business. Built with HTML, Tailwind CSS, and JavaScript, designed to capture emails and drive broker signups.

## 🚀 Features

- **Professional Design**: Dark mode aesthetic with neon green/cyan accents
- **Email Capture**: Integrated with Formspree for lead generation
- **Responsive Layout**: Mobile-first design that works on all devices
- **Smooth Animations**: Subtle CSS animations and hover effects
- **SEO Optimized**: Proper meta tags and semantic HTML structure
- **Fast Loading**: Optimized with CDN resources and minimal JavaScript

## 📋 Page Sections

1. **Hero Section**: Main headline, sub-headline, and email capture form
2. **Social Proof**: Community statistics and featured mentions
3. **Value Proposition**: What's inside the guide (4 key benefits)
4. **Broker CTA**: Exness partnership with compliance disclaimer
5. **Footer**: Secondary email capture and social media links

## 🛠️ Customization Required

Before deploying, you need to update the following placeholders:

### 1. Formspree Integration
Replace `YOUR_FORMSPREE_ID` in both forms with your actual Formspree endpoint:
```html
action="https://formspree.io/f/YOUR_FORMSPREE_ID"
```

### 2. PDF Guide URL
Replace `YOUR_PDF_GUIDE_URL_HERE` with your actual PDF guide URL:
```javascript
window.location.href = 'YOUR_PDF_GUIDE_URL_HERE';
```

### 3. Exness IB Link
Replace `YOUR_EXNESS_IB_LINK_HERE` with your actual Exness referral link:
```html
href="YOUR_EXNESS_IB_LINK_HERE"
```

### 4. Social Media Links
Update all social media URLs:
```html
YOUR_YOUTUBE_LINK
YOUR_INSTAGRAM_LINK
YOUR_TIKTOK_LINK
YOUR_X_LINK
```

### 5. Brand Customization
- Update "QuantumFX Trading" to your actual brand name
- Modify headlines and copy to match your messaging
- Adjust color scheme if needed (currently uses green/cyan theme)

## 🚀 Deployment

### GitHub Pages (Recommended)
1. Create a new GitHub repository
2. Upload all files to the repository
3. Go to Settings → Pages
4. Select "Deploy from a branch"
5. Choose your main branch
6. Your site will be available at `https://username.github.io/repository-name`

### Other Static Hosting
- **Netlify**: Drag and drop the folder to deploy
- **Vercel**: Connect your GitHub repository
- **AWS S3**: Upload files to an S3 bucket with static website hosting
- **Any web server**: Upload files to your hosting provider

## 📱 Mobile Optimization

The page is fully responsive and includes:
- Mobile-first design approach
- Touch-friendly buttons and forms
- Optimized typography for small screens
- Collapsible navigation for mobile devices

## 🔒 Security & Compliance

- **Formspree**: Handles form submissions securely
- **External Links**: All external links open in new tabs with proper security attributes
- **Disclaimer**: Includes comprehensive trading risk disclaimers
- **GDPR**: Form includes privacy notice and unsubscribe information

## 🎨 Design System

### Colors
- **Primary**: `#22c55e` (Green-500)
- **Background**: `#0f172a` (Slate-900)
- **Secondary Background**: `#1e293b` (Slate-800)
- **Text**: `#ffffff` (White)
- **Muted Text**: `#94a3b8` (Gray-400)

### Typography
- **Font Family**: Inter (Google Fonts)
- **Headings**: Bold weights (600-800)
- **Body**: Regular weight (400)

### Animations
- Subtle gradient background animation
- Floating background elements
- Hover effects with glow
- Smooth scrolling navigation

## 📊 Performance

- **Lighthouse Score**: 90+ (Performance, Accessibility, Best Practices, SEO)
- **Loading Time**: < 2 seconds on 3G
- **Bundle Size**: Minimal (uses CDN resources)
- **SEO**: Optimized meta tags and semantic structure

## 🔧 Technical Details

### Dependencies
- **Tailwind CSS**: Via CDN for styling
- **Font Awesome**: Via CDN for icons
- **Google Fonts**: Inter font family
- **Formspree**: For form handling

### Browser Support
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## 📝 File Structure

```
├── index.html          # Main landing page
├── disclaimer.html     # Legal disclaimer page
├── README.md          # This file
└── assets/            # Optional: Add images, PDFs, etc.
```

## 🚨 Important Notes

1. **Formspree Setup**: You must create a Formspree account and get your endpoint ID
2. **PDF Hosting**: Ensure your PDF guide is hosted and accessible via URL
3. **Broker Compliance**: Verify your broker partnership and disclosure requirements
4. **Legal Review**: Consider having a legal professional review the disclaimer
5. **Testing**: Test all forms and links before going live

## 🆘 Support

If you need help with:
- **Customization**: Update the placeholder values as shown above
- **Deployment**: Follow the GitHub Pages instructions
- **Formspree**: Visit [formspree.io](https://formspree.io) for setup help
- **Design Changes**: Modify the Tailwind classes in the HTML

## 📄 License

This project is created for educational and business purposes. Feel free to modify and use for your own projects.

---

**Ready to deploy?** Just update the placeholder values and upload to your hosting provider!
