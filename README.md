# Cameron Detig - VFX & Animation Portfolio

A clean, minimalist portfolio website showcasing VFX and animation work, inspired by the original camerondetig.com.

## 🎨 Features

- **Minimalist Design**: Clean, modern aesthetic with a light header and dark content area
- **Responsive Layout**: Fully responsive design that works on all devices
- **Three Main Pages**:
  - **Demo Reel**: Showcases main preview reels (Ahsoka, Predator)
  - **Related Work**: Additional projects including motion capture research
  - **About**: Biography, contact information, and resume download

## 🚀 Getting Started

### Local Development

Simply open `index.html` in your web browser to view the site locally.

Alternatively, you can use a local server:

```bash
# Using Python 3
python3 -m http.server 8000

# Using Node.js (http-server)
npx http-server -p 8000
```

Then visit `http://localhost:8000` in your browser.

## 📁 Project Structure

```
VFX_Anim_Portfolio_Site/
├── index.html              # Main page (Demo Reel)
├── related-work.html       # Related Work page
├── about.html              # About page
├── styles.css              # Main stylesheet
├── images/                 # Image assets
│   └── profile-placeholder.jpg
├── assets/                 # Other assets
│   └── resume.pdf
└── README.md              # This file
```

## 🎯 Customization

### Adding Your Content

1. **Profile Image**: Replace `images/profile-placeholder.jpg` with your photo
2. **Resume**: Add your resume PDF to `assets/resume.pdf`
3. **Social Links**: Update the social media URLs in the header of each HTML file
4. **Project Content**: Modify the project descriptions and add your own work

### Embedding Videos

To add Vimeo embeds, replace the `.video-placeholder` div with:

```html
<div class="video-container">
    <iframe src="https://player.vimeo.com/video/YOUR_VIDEO_ID" 
            frameborder="0" 
            allow="autoplay; fullscreen; picture-in-picture" 
            allowfullscreen>
    </iframe>
</div>
```

### Color Scheme

The color scheme is defined in CSS variables at the top of `styles.css`:

```css
:root {
    --color-bg-light: #f8f9fa;
    --color-bg-dark: #0a0a0a;
    --color-accent: #2563eb;
    /* ... more variables */
}
```

## 🌐 Deployment

### GitHub Pages

1. Create a new repository on GitHub
2. Push your code to the repository
3. Go to Settings → Pages
4. Select your main branch as the source
5. Your site will be live at `https://yourusername.github.io/repository-name`

### Netlify

1. Create a free account at [Netlify](https://www.netlify.com)
2. Drag and drop your project folder
3. Your site will be live instantly with a custom URL

### Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project directory
3. Follow the prompts to deploy

## 📝 License

This is a personal portfolio template. Feel free to use and modify for your own portfolio.

## 🔗 Links

- Original Site: [camerondetig.com](https://camerondetig.com)
- LinkedIn: [linkedin.com/in/camerondetig](https://www.linkedin.com/in/camerondetig)
- GitHub: [github.com/camerondetig](https://github.com/camerondetig)
