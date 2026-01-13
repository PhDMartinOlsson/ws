# Academic Personal Webpage

A modern, responsive personal academic webpage showcasing CV/resume and basic academic information. This site is designed to be hosted for free on GitHub Pages.

## Features

- ✅ Fully responsive design (mobile, tablet, desktop)
- ✅ Fast loading (static HTML/CSS/JS)
- ✅ SEO-friendly structure
- ✅ Accessible design
- ✅ Easy to update content
- ✅ Professional academic appearance
- ✅ Print-friendly styles

## File Structure

```
Homepage/
├── index.html          # Main webpage
├── css/
│   └── style.css       # All styling
├── js/
│   └── main.js         # Interactive features
├── assets/             # Images, icons (optional)
├── README.md           # This file
└── .gitignore          # Git ignore file
```

## Getting Started

### 1. Customize Your Content

Edit `index.html` and replace the placeholder content with your information:

- **Header**: Update your name and academic title
- **About Section**: Add your bio and research interests
- **Education**: List your degrees and institutions
- **Experience**: Add your academic positions and roles
- **Skills**: Include your research areas and technical skills
- **Contact**: Update your contact information and academic profile links

### 2. Customize Styling (Optional)

Edit `css/style.css` to change colors, fonts, or layout. The CSS uses CSS variables for easy customization:

```css
:root {
    --primary-color: #2c3e50;
    --secondary-color: #3498db;
    --accent-color: #e74c3c;
    /* ... more variables */
}
```

### 3. Deploy to GitHub Pages

#### Step 1: Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in (or create an account)
2. Click the "+" icon in the top right and select "New repository"
3. Name your repository (e.g., `academic-website` or `yourname.github.io`)
4. Choose "Public" (required for free GitHub Pages)
5. **Do NOT** initialize with README, .gitignore, or license
6. Click "Create repository"

#### Step 2: Upload Your Files

**Option A: Using GitHub Web Interface**

1. In your new repository, click "uploading an existing file"
2. Drag and drop all your files (index.html, css/, js/, etc.)
3. Commit the changes

**Option B: Using Git Command Line**

```bash
# Navigate to your project directory
cd /path/to/Homepage

# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit: Academic webpage"

# Add your GitHub repository as remote
git remote add origin https://github.com/yourusername/your-repo-name.git

# Push to GitHub
git branch -M main
git push -u origin main
```

#### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on "Settings" tab
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Click "Save"
7. Your site will be available at: `https://yourusername.github.io/repository-name/`

**Note**: If you name your repository `yourusername.github.io`, your site will be available at `https://yourusername.github.io` (without the repository name).

### 4. Update Your Site

After making changes to your files:

**Using Git:**
```bash
git add .
git commit -m "Update content"
git push
```

Changes will be live within a few minutes.

**Using GitHub Web Interface:**
1. Navigate to the file you want to edit
2. Click the pencil icon to edit
3. Make your changes
4. Commit the changes

## Custom Domain (Optional)

GitHub Pages supports custom domains for free:

1. Purchase a domain from a registrar (e.g., Namecheap, Google Domains)
2. In your repository Settings → Pages, enter your custom domain
3. Configure DNS records as instructed by GitHub
4. GitHub will automatically set up HTTPS for your custom domain

## Browser Support

This webpage works on all modern browsers:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

Feel free to use this template for your personal academic webpage. Modify it as needed!

## Support

For GitHub Pages documentation, visit: https://docs.github.com/en/pages

For questions about customizing the webpage, refer to the HTML, CSS, and JavaScript comments in the code.
