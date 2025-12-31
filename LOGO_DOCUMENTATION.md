# SM Monogram Logo System

## Overview
Professional minimal monogram logo designed for an AI/ML portfolio website. The logo features a clean, modern design suitable for internship applications and tech roles.

## Files Included

### 1. **logo.svg** - Main Header Logo
- **Dimensions**: 200×200px (scalable SVG)
- **Usage**: Navigation bar, header branding
- **Style**: "SM" monogram in rounded sans-serif
- **Colors**: 
  - Background: Deep Blue (#0A2540)
  - Text: White
  - Accent: Cyan (#00D4FF) border + glow effect
- **Features**: 
  - Circular design with gradient overlay
  - Subtle cyan accent dot (top-right)
  - Professional glow filter

### 2. **logo-code.svg** - Code-Style Variant
- **Dimensions**: 200×200px (scalable SVG)
- **Usage**: Footer branding, alternative header logo, social media
- **Style**: `<S/>` code-style monogram
- **Colors**: Same color palette
- **Features**: Monospace font for code brackets, modern tech aesthetic

### 3. **favicon.svg** - Browser Favicon
- **Dimensions**: 32×32px (scalable SVG)
- **Usage**: Browser tab, bookmarks
- **Style**: Simplified "S" monogram
- **Features**: Optimized for small display sizes

## Color Palette
| Element | Color | Hex Code |
|---------|-------|----------|
| Background | Deep Blue | #0A2540 |
| Accent | Cyan | #00D4FF |
| Text | White | #FFFFFF |

## Integration Details

### In test.html
1. **Favicon**: Linked in `<head>` tag
   ```html
   <link rel="icon" type="image/svg+xml" href="favicon.svg">
   ```

2. **Navbar Logo**: SVG embedded directly in the navbar
   - Responsive and scales on mobile/desktop
   - No external dependencies
   - Fast loading time

### CSS Styling
Updated `.profile-img` CSS to support both `<img>` and `<svg>` elements:
- Flexbox centering for proper alignment
- Maintains circular shape with border-radius
- 50×50px display size

## Design Features

✅ **ATS-Safe**: Simple, scannable design (no complex graphics)
✅ **Professional**: Suitable for tech internships and entry-level roles
✅ **Scalable**: Vector format ensures crispness at any size
✅ **Performance**: SVG format = minimal file size
✅ **Accessible**: High contrast (Deep Blue + White)
✅ **Modern**: Gradient effects and subtle animations
✅ **Responsive**: Works seamlessly on desktop & mobile

## Customization Guide

### Change Colors
1. Replace `#0A2540` with your preferred dark color
2. Replace `#00D4FF` with your preferred accent color
3. Update both SVG files and favicon

### Change Text
1. Modify the `<text>` elements in SVG files
2. Replace "SM" with your initials
3. Adjust `font-size` and positioning if needed

### Export to PNG
To create PNG versions:
1. Open SVG in browser
2. Right-click → Save as PNG
3. Or use online converters (cloudconvert.com, convertio.co)

## Browser Support
✅ All modern browsers (Chrome, Firefox, Safari, Edge)
✅ Mobile browsers (iOS Safari, Chrome Mobile)
✅ IE 11+ (with fallback)

## Performance Notes
- SVG format: ~2-3 KB per file
- No additional HTTP requests when embedded
- Scales perfectly for retina displays
- Favicon caching by browsers

## Future Enhancements
- PNG versions at 32×32, 64×64, 128×128
- Animated logo version (optional)
- Dark mode variant
- Social media sized versions (1:1, 16:9)

---

**Created**: January 2026  
**Designed for**: AI/ML Portfolio - Shaista Mulla
