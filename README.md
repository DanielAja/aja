# AJA - App Development Company Website

A modern, dark-themed website for showcasing apps and collecting user feedback. Built for GitHub Pages deployment.

## 🎨 Features

- **Dark Color Scheme** - Professional black/dark theme with purple accent colors
- **Multi-Page Navigation** - Home, Apps, and Feedback pages
- **Responsive Design** - Works perfectly on desktop, tablet, and mobile
- **Sound Market App** - Featured app with "Coming Soon" status
- **Feedback Form** - Dedicated page for user submissions
- **Modern UI** - Smooth animations and hover effects
- **GitHub Pages Ready** - No build process required

## 📁 Structure

```
├── index.html       # Home page with company information
├── apps.html        # Apps showcase (Sound Market + placeholders)
├── feedback.html    # Feedback/contact form
├── styles.css       # All styling (dark theme)
└── README.md        # This file
```

## 🚀 Quick Start

### Local Development

1. Open `index.html` in your browser
2. Navigate between pages using the top navigation menu
3. All pages link together seamlessly

### Deploy to GitHub Pages

1. **Create a GitHub repository:**
   ```bash
   git init
   git add .
   git commit -m "Initial commit: AJA website"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```

2. **Enable GitHub Pages:**
   - Go to your repository on GitHub
   - Click **Settings** → **Pages**
   - Under "Source", select **main** branch
   - Click **Save**
   - Your site will be live at: `https://YOUR_USERNAME.github.io/YOUR_REPO/`

## 📧 Form Setup

The feedback form on [feedback.html](feedback.html) needs a form backend to actually send submissions.

### Option 1: Formspree (Recommended - Free)

1. Sign up at [Formspree.io](https://formspree.io/)
2. Create a new form
3. Copy your form endpoint
4. In `feedback.html`, line 54, replace:
   ```html
   <form id="feedbackForm" action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```
   with your actual Formspree form ID

### Option 2: Custom Backend

You can integrate with any backend API by modifying the form submission JavaScript in `feedback.html`.

## 🎨 Customization

### Change Company Name

Replace "AJA" in the navigation logo across all three HTML files.

### Change Colors

Edit `styles.css` CSS variables at the top:
```css
:root {
    --accent-primary: #6366f1;  /* Primary accent color */
    --accent-secondary: #8b5cf6; /* Secondary accent color */
}
```

### Add More Apps

In `apps.html`, duplicate the `.app-card` section and customize:
- Change the emoji icon
- Update the title and description
- Modify the status badge
- Add feature tags

### Modify Company Info

Edit the content in `index.html`:
- Hero section (lines 24-33)
- About section (lines 36-68)
- Mission section (lines 71-79)

## 📱 Pages Overview

### Home ([index.html](index.html))
- Hero section with call-to-action buttons
- "Who We Are" section with feature cards
- Mission statement
- Call-to-action to view apps

### Apps ([apps.html](apps.html))
- Sound Market app card with "Coming Soon" badge
- Placeholder for future apps
- Newsletter/updates section

### Feedback ([feedback.html](feedback.html))
- Contact information
- Comprehensive feedback form with categories
- Success message on submission

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 📄 License

Free to use and modify for your projects.
