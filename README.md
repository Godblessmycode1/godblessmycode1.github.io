# Personal Academic Website

A modern, responsive personal website template designed for PhD students and academics. This website showcases your research, publications, and academic profile in a professional and visually appealing manner.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Academic Focus**: Sections for research, publications, education, and contact information
- **Interactive Elements**: Smooth scrolling, mobile navigation, typing animations
- **SEO Friendly**: Optimized for search engines
- **Fast Loading**: Optimized performance with lazy loading and efficient code

## Quick Start

1. **Download/Clone** this repository
2. **Customize** the content with your information
3. **Add your profile photo** to the `assets` folder
4. **Deploy** to GitHub Pages

## Customization Guide

### 1. Personal Information

Edit the following in `index.html`:

- Replace "Your Name" with your actual name
- Update "[Your Field]" with your research field
- Replace "[Your Department]" and "[Your University]" with your details
- Update the hero description with your research interests
- Add your actual email, GitHub, LinkedIn, and other social links

### 2. Profile Photo

- Add your profile photo as `assets/profile.jpg`
- Recommended size: 280x280 pixels or larger (square format)
- The image will be automatically cropped to a circle

### 3. Research & Publications

- Update the research interests section
- Add your actual research projects
- Replace placeholder publications with your real publications
- Update publication links to point to actual PDFs, DOI links, etc.

### 4. Contact Information

- Update email address in both HTML and JavaScript files
- Add your office location and contact details
- Update office hours

### 5. Colors & Styling

The website uses a blue color scheme. To change colors, edit `styles.css`:

- Primary color: `#3b82f6` (blue)
- Secondary colors are defined throughout the CSS file
- Search for color codes to customize the theme

## GitHub Pages Deployment

### Method 1: Direct Repository Upload

1. **Create a new repository** on GitHub named `yourusername.github.io` (replace `yourusername` with your actual GitHub username)

2. **Upload your files**:
   - Go to your repository on GitHub
   - Click "uploading an existing file"
   - Drag and drop all files from the `personal-website` folder
   - Commit the changes

3. **Enable GitHub Pages**:
   - Go to repository Settings
   - Scroll down to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

4. **Access your website**:
   - Your website will be available at `https://yourusername.github.io`
   - It may take a few minutes to become active

### Method 2: Git Command Line

1. **Create repository** on GitHub named `yourusername.github.io`

2. **Clone and setup**:
   ```bash
   git clone https://github.com/yourusername/yourusername.github.io.git
   cd yourusername.github.io
   ```

3. **Copy your files**:
   ```bash
   # Copy all files from personal-website folder to the repository folder
   cp -r /path/to/personal-website/* .
   ```

4. **Commit and push**:
   ```bash
   git add .
   git commit -m "Initial website setup"
   git push origin main
   ```

5. **Enable GitHub Pages** (if not automatically enabled):
   - Follow steps 3-4 from Method 1

### Method 3: Using a Custom Domain

If you have your own domain:

1. **Follow Method 1 or 2** to set up the basic GitHub Pages site

2. **Add CNAME file**:
   - Create a file named `CNAME` (no extension) in your repository root
   - Add your domain name (e.g., `www.yourname.com`)

3. **Configure DNS**:
   - Add a CNAME record pointing to `yourusername.github.io`
   - Or add A records pointing to GitHub's IP addresses

4. **Update repository settings**:
   - Go to Settings > Pages
   - Add your custom domain
   - Enable "Enforce HTTPS"

## File Structure

```
personal-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js           # JavaScript functionality
├── assets/             # Images and documents
│   ├── profile.jpg     # Your profile photo
│   └── cv.pdf          # Your CV (optional)
└── README.md           # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Performance Tips

1. **Optimize images**: Compress your profile photo and any other images
2. **Update content**: Remove placeholder text and add real content
3. **Test responsiveness**: Check the website on different screen sizes
4. **Validate HTML**: Use W3C validator to check for errors

## Customization Examples

### Adding a Blog Section

To add a blog section, you can:

1. Add a new navigation item in the HTML
2. Create a new section with blog posts
3. Style it similar to the publications section

### Adding More Social Links

To add more social media links:

1. Find the social-links section in HTML
2. Add new anchor tags with appropriate icons
3. Update the CSS if needed for spacing

### Changing Fonts

To change fonts:

1. Update the Google Fonts link in the HTML head
2. Modify the font-family in CSS

## Troubleshooting

### Website Not Loading

- Check that your repository is named correctly (`yourusername.github.io`)
- Ensure GitHub Pages is enabled in repository settings
- Wait a few minutes for changes to propagate

### Images Not Displaying

- Check file paths are correct
- Ensure images are in the `assets` folder
- Verify image file names match those referenced in HTML

### Mobile Menu Not Working

- Check that JavaScript file is properly linked
- Ensure there are no JavaScript errors in browser console

## Support

If you encounter issues:

1. Check the browser console for JavaScript errors
2. Validate your HTML and CSS
3. Ensure all file paths are correct
4. Test locally before deploying

## License

This template is free to use for personal and academic purposes. Feel free to modify and customize it according to your needs.

---

**Note**: Remember to replace all placeholder content with your actual information before deploying your website!
# yitongguo.github.io
