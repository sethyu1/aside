# Errows.ai Landing Page - Parameter Passing & High Quality Display

## Overview
This landing page redirects users to Errows.ai while preserving all URL parameters and displaying high-quality images optimized for their screen size.

## Features

### Parameter Passing
- Automatically extracts all URL parameters from the source URL
- Parameters passed: `s`, `c`, `g`, `ad`, `acc`, `pixel`
- Adds `device` parameter based on user's device type (mobile/desktop)
- Target URL: `https://errows.ai/character/generate/`

### Image Quality Optimizations
1. **High Quality Rendering**
   - Uses smooth image rendering for better quality
   - Optimized for Retina and high-DPI displays
   - Responsive images that adapt to screen size

2. **Performance**
   - Eager loading for immediate display
   - Synchronous decoding for best quality
   - Hardware acceleration enabled
   - Optimized for all devices (mobile, tablet, desktop)

3. **Adaptive Display**
   - Different images for mobile and desktop
   - Automatically adjusts to screen dimensions
   - Maintains aspect ratio and fills viewport
   - Supports all screen sizes (portrait, landscape, ultra-wide)

### Auto-Redirect
- Automatically redirects after 5 seconds
- Users can click anywhere to redirect immediately
- Works on all devices and browsers

## Image Requirements

### Recommended Image Specifications

**Mobile Image (image/mobile.jpg)**
- Resolution: 1920x1080 (or higher for Retina)
- Aspect Ratio: 9:16 (portrait)
- Format: JPG (optimized for web)
- File Size: Keep under 500KB for fast loading

**Desktop Image (image/desktop.jpg)**
- Resolution: 3840x2160 (4K) or higher
- Aspect Ratio: 16:9 (landscape)
- Format: JPG (optimized for web)
- File Size: Keep under 2MB for fast loading

### Tips for Maximum Quality
1. Use high-resolution source images (2x+ the display size for Retina)
2. Optimize images for web (compress but maintain quality)
3. Use JPG format for photos/images with many colors
4. Keep file sizes reasonable for fast loading

## Usage

Visit the page with URL parameters:
```
https://yoursite.com/?s=value&c=c1&g=value&ad=value&acc=value&pixel=803742088964629
```

All parameters will be passed to the target URL:
```
https://errows.ai/character/generate/?s=value&c=c1&g=value&ad=value&acc=value&pixel=803742088964629&device=mobile
```

## Browser Support
- All modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome Mobile, Samsung Internet)
- Backward compatible with older browsers

## Debugging
Open browser console (F12) to see:
- Device information
- Extracted URL parameters
- Target redirect URL
- Image loading information
- Timer status

