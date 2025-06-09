# Image Setup Guide for Sneaker Mania

## How to Add Sneaker Images

### Option 1: Local Images (Recommended for Development)

1. **Add your images to the `images` folder** that was created in your project directory
2. **Use these exact filenames** for the images to work automatically:

#### Featured Products:
- `white-sneaker.jpg` - White Sneaker
- `black-sneaker.jpg` - Black Sneaker  
- `dark-sneaker.jpg` - Dark Sneaker
- `air-classic-sneaker.jpg` - Air Classic Sneaker

#### Best Sellers:
- `running-sneaker.jpg` - Running Sneaker (main)
- `ultra-boost-sneaker.jpg` - Ultra Boost Sneaker
- `classic-sneaker.jpg` - Classic Sneaker
- `air-max-sneaker.jpg` - Air Max Sneaker
- `elite-sneaker.jpg` - Elite Sneaker
- `pure-sneaker.jpg` - Pure Sneaker
- `rose-sneaker.jpg` - Rose Sneaker

#### Detail Page Color Variants:
- `white-sneaker.jpg` - White variant
- `black-sneaker.jpg` - Black variant
- `pink-sneaker.jpg` - Pink variant
- `blue-sneaker.jpg` - Blue variant

### Image Requirements:
- **Format**: JPG, PNG, or WebP
- **Size**: Recommended 400x300px or larger
- **Background**: White or transparent background works best
- **Quality**: High quality, clear images

### Option 2: Online Image URLs

If you want to use images from the internet:

1. **Find sneaker images** from stock photo websites like:
   - Unsplash (free)
   - Pexels (free)
   - Shutterstock (paid)
   - Adobe Stock (paid)

2. **Replace the image paths** in the HTML files:
   - Change `src="images/white-sneaker.jpg"` to `src="https://example.com/your-image.jpg"`

### Option 3: Placeholder Images

For testing, you can use placeholder image services:

```html
<!-- Replace any image src with: -->
src="https://via.placeholder.com/400x300/f8f8f8/666666?text=White+Sneaker"
```

### Current Setup Features:

✅ **Fallback System**: If images don't load, CSS shapes will show instead
✅ **Responsive Design**: Images scale properly on all devices
✅ **Hover Effects**: Images have smooth hover animations
✅ **Color Variants**: Detail page supports multiple color options
✅ **Cart Integration**: Images show in cart modal

### Testing Your Images:

1. Add your images to the `images` folder
2. Open `index.html` in your browser
3. Check if images load properly
4. Click on products to see detail page images
5. Test cart functionality with images

### Troubleshooting:

- **Images not showing**: Check file names match exactly (case-sensitive)
- **Images too large**: Resize to recommended dimensions
- **Images blurry**: Use higher resolution images
- **Fallback not working**: Check browser console for errors

### Next Steps:

1. Add your sneaker images to the `images` folder
2. Test the website to ensure images load correctly
3. Customize image paths if needed
4. Optimize images for web (compress if too large)

Your e-commerce store is now ready to display real sneaker images! 🎉 