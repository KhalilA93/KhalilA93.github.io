# Khalil's Professional Portfolio

A modern, responsive portfolio website built with Jekyll and hosted on GitHub Pages.

## Features

- **Professional Design**: Clean, modern layout optimized for showcasing creative work
- **Video Showcase**: Prominent area for featuring your best work videos
- **Project Gallery**: Grid layout for displaying your projects with descriptions
- **Social Integration**: Navigation bar with social media links
- **Responsive**: Fully responsive design that works on all devices
- **SEO Optimized**: Proper meta tags and structure for search engines

## Structure

```
├── _config.yml          
├── _layouts/
│   └── default.html     
├── _includes/
│   └── head-custom.html 
├── assets/
│   ├── css/
│   │   └── style.scss   
│   ├── js/
│   │   └── main.js      
│   ├── images/          
│   ├── videos/          
│   ├── icons/           
│   └── README.md        
└── index.html           
```

## Setup

1. **Configure your site**: Edit `_config.yml` to update:
   - Site title and description
   - Your social media usernames
   - Contact information

2. **Add your content**:
   - Replace placeholder text in `index.html`
   - Add your images to `/assets/images/`
   - Add your videos to `/assets/videos/`
   - Add your icons to `/assets/icons/`

3. **Customize styling**: Modify `/assets/css/style.scss` for any design changes

## Adding Media

### Images
- **Profile photo**: Add as `assets/images/profile.jpg`
- **Project images**: Add as `assets/images/project1.jpg`, etc.
- **Social preview**: Add as `assets/images/og-image.jpg`

### Videos
- **Showcase video**: Add as `assets/videos/showcase-video.mp4`
- Update the video element in `index.html` to reference your video

### Icons
- **Favicon**: Add as `assets/icons/favicon.ico`
- **iOS icon**: Add as `assets/icons/apple-touch-icon.png`

## Sections

- **Navigation**: Fixed header with smooth scroll navigation
- **Hero**: Eye-catching intro with call-to-action
- **Portfolio**: Featured video and project gallery
- **About**: Personal introduction and skills
- **Contact**: Contact form and information

## Customization

### Colors
Edit the CSS variables in `style.scss` to change the color scheme.

### Social Links
Update the `social` section in `_config.yml` with your usernames.

### Projects
Edit the project cards in `index.html` to showcase your work.

## Development

To run locally:
```bash
bundle exec jekyll serve
```

## Deployment

This site is automatically deployed via GitHub Pages when you push to the main branch.

---

**Note**: Remember to update placeholder content with your actual information and media!