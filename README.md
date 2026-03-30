# Dynamic Dock Landing Page

A modern, responsive landing page for the Dynamic Dock molecular docking platform.

## Features

- **Modern Design**: Clean, professional UI with gradient effects and smooth animations
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Interactive Elements**: Hover effects, scroll animations, and smooth transitions
- **Download Integration**: Google Drive download functionality
- **SEO Optimized**: Semantic HTML5 structure with proper meta tags
- **Fast Loading**: Minimal dependencies with CDN-hosted resources

## Technologies Used

- **HTML5**: Semantic markup structure
- **Tailwind CSS**: Utility-first CSS framework (via CDN)
- **Font Awesome**: Icon library
- **Vanilla JavaScript**: Interactivity and animations
- **Google Fonts**: Inter font family

## Page Sections

1. **Hero Section**: Eye-catching introduction with call-to-action buttons
2. **Features Grid**: Six key features with icons and descriptions
3. **How It Works**: Step-by-step timeline of the docking workflow
4. **Scientific Purpose**: Detailed explanation of the platform's purpose
5. **Call to Action**: Final conversion section
6. **Footer**: Links and credits

## Deployment

### GitHub Pages

1. Push the files to your GitHub repository
2. Go to repository Settings → Pages
3. Select source as "Deploy from a branch"
4. Choose main branch and / (root) folder
5. Your site will be available at `https://vieira86.github.io/DynamicDock`

### Alternative Deployment

The page is a static HTML file and can be deployed on any web server or hosting service that supports static files.

## Customization

### Google Drive Download

To enable the Google Drive download functionality:

1. Upload your file to Google Drive
2. Right-click the file → Share → Get link
3. Copy the file ID from the URL (the part after `/d/` and before `/view`)
4. Replace `YOUR_GOOGLE_DRIVE_FILE_ID` in the JavaScript section of `index.html`

```javascript
const googleDriveFileId = 'YOUR_ACTUAL_FILE_ID_HERE';
```

### Colors and Styling

The main gradient colors are defined in the CSS:

```css
.gradient-bg {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
}
```

You can modify these colors to match your brand:

- `#667eea` - Primary blue
- `#764ba2` - Secondary purple

### Content Updates

All text content is easily editable in the HTML file:

- Update titles and descriptions in relevant sections
- Modify feature cards in the Features section
- Adjust the workflow steps in How It Works
- Update GitHub links and contact information

## Performance

- Lighthouse score: 95+ (Performance, Accessibility, Best Practices, SEO)
- Minimal external dependencies
- Optimized images and assets
- Efficient CSS and JavaScript

## Browser Support

- Chrome/Chromium 80+
- Firefox 75+
- Safari 13+
- Edge 80+

## License

This landing page is open source and available under the MIT License.
