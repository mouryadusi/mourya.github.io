# Mourya Dusi - Portfolio Website

> Professional portfolio showcasing AI & Data Science projects, skills, and experience.

**Live Site:** https://mouryadusi.github.io/mourya.github.io/profile.html

---

## 📁 Repository Structure

```
mourya.github.io/
├── profile.html                  ← Main portfolio page (updated)
├── smart-exit-reminder.html      ← Product showcase page (new)
├── README.md                     ← This file
└── .gitignore
```

---

## 🚀 Deployment Instructions

### Quick Deploy (3 Minutes)

1. **Upload Files to Your Repository**
   ```bash
   # Navigate to your repo
   cd mourya.github.io
   
   # Copy the updated files
   # Place profile.html and smart-exit-reminder.html in the root
   
   # Stage files
   git add profile.html smart-exit-reminder.html
   
   # Commit
   git commit -m "Add Smart Exit Reminder project showcase"
   
   # Push to GitHub
   git push origin main
   ```

2. **Enable GitHub Pages** (if not already enabled)
   - Go to: Settings → Pages
   - Source: Deploy from branch `main`
   - Folder: `/` (root)
   - Save

3. **Wait 2-3 minutes** for GitHub Pages to rebuild

4. **Visit Your Site**
   ```
   https://mouryadusi.github.io/mourya.github.io/profile.html
   ```

---

## ✨ What's New

### Smart Exit Reminder Project
- **NEW**: Complete product showcase page with full technical details
- **Location**: First project in the Portfolio section
- **Features**:
  - Comprehensive problem/solution analysis
  - 5 technical implementation approaches with pros/cons
  - System architecture diagram
  - UI/UX mockups
  - Tech stack breakdown
  - 6 core features overview

### How It Works
1. User visits portfolio → Scrolls to Projects section
2. Sees "Smart Exit Reminder" as the featured project
3. Clicks **"View Full Product Details →"** button
4. Navigates to dedicated product showcase page
5. Can return via **"← Back to Portfolio"** button

---

## 🔗 Navigation Flow

```
profile.html (Portfolio)
    ↓
    User clicks "View Full Product Details →"
    ↓
smart-exit-reminder.html (Product Showcase)
    ↓
    User clicks "← Back to Portfolio"
    ↓
profile.html#projects (Returns to Projects section)
```

---

## 📂 File Details

### profile.html
- **Purpose**: Main portfolio page
- **Size**: ~50KB
- **Sections**:
  - Hero/About
  - Skills & Expertise
  - **Projects (NEW: Smart Exit Reminder added)**
  - Education
  - Contact

### smart-exit-reminder.html
- **Purpose**: Detailed product showcase
- **Size**: ~29KB
- **Sections**:
  - Hero with stats
  - Problem/Solution cards
  - 6 Core Features
  - 5 Technical Approaches (with pros/cons)
  - Architecture Diagram
  - UI Mockup
  - Tech Stack
  - CTA Section

---

## 🎨 Design Features

- **Modern Dark Theme**: Professional gradient design
- **Responsive**: Works perfectly on mobile, tablet, desktop
- **Smooth Animations**: Hover effects and transitions
- **Gradient Accents**: Cyan to purple color scheme
- **Clean Typography**: Inter font family
- **Fast Loading**: All CSS embedded, no external dependencies

---

## 🔧 Customization

### Update Smart Exit Reminder Content
Edit `smart-exit-reminder.html`:
- Problem/Solution text
- Feature descriptions
- Technical approaches
- Architecture layers
- Tech stack badges

### Add More Projects
In `profile.html`, duplicate a project card:
```html
<div class="project-card">
    <div class="project-header">
        <span class="project-tag">Your Category</span>
        <h3>Your Project Title</h3>
    </div>
    <div class="project-body">
        <p>Your description...</p>
        <div class="tech-stack">
            <span class="tech-badge">Tech 1</span>
            <span class="tech-badge">Tech 2</span>
        </div>
        <!-- Optional: Add link to showcase page -->
        <a href="your-project.html" class="project-link">View Details →</a>
    </div>
</div>
```

---

## 🐛 Troubleshooting

### Links Not Working
- **Issue**: 404 when clicking "View Full Details"
- **Fix**: Ensure `smart-exit-reminder.html` is in the same directory as `profile.html`
- **Check**: File name is exactly `smart-exit-reminder.html` (lowercase, with hyphens)

### Page Not Updating
- **Issue**: Changes not visible after push
- **Fix**: 
  1. Clear browser cache (Ctrl+Shift+R / Cmd+Shift+R)
  2. Wait 2-3 minutes for GitHub Pages to rebuild
  3. Check GitHub Actions tab for deployment status

### Styles Not Loading
- **Issue**: Page looks broken
- **Fix**: All CSS is embedded in HTML files, so this shouldn't happen
- **Check**: Make sure you uploaded the complete HTML file

---

## 📊 Analytics & SEO

### Page URLs
- **Portfolio**: `/profile.html`
- **Smart Exit Reminder**: `/smart-exit-reminder.html`

### Shareable Links
You can now share direct links to specific projects:
```
Full Portfolio: https://mouryadusi.github.io/mourya.github.io/profile.html
Smart Exit Reminder: https://mouryadusi.github.io/mourya.github.io/smart-exit-reminder.html
```

---

## 📱 Mobile Responsive

Both pages are fully responsive:
- ✅ Mobile (320px - 480px)
- ✅ Tablet (481px - 768px)
- ✅ Desktop (769px+)

Tested on:
- iPhone (Safari)
- Android (Chrome)
- iPad
- Desktop browsers (Chrome, Firefox, Safari, Edge)

---

## 🎯 Future Enhancements

### Potential Additions
1. **More Project Showcases**
   - Student Performance Predictor → `student-predictor.html`
   - University Chatbot → `chatbot.html`

2. **Blog Section**
   - Technical articles
   - Project case studies

3. **Analytics Integration**
   - Google Analytics
   - Track project page views

4. **Contact Form**
   - Working email form
   - FormSpree or similar service

---

## 📝 Maintenance

### Regular Updates
1. Keep project descriptions current
2. Add new certifications
3. Update tech stack as skills grow
4. Add new projects as completed

### Content Updates
- **Profile**: Update experience, education, stats
- **Projects**: Add new showcases
- **Contact**: Keep links current

---

## 💼 Professional Use

### For Job Applications
Share specific project links:
```
"I designed a smart mobile app for everyday use. 
Full details: https://mouryadusi.github.io/mourya.github.io/smart-exit-reminder.html"
```

### For LinkedIn
- Update LinkedIn profile with portfolio link
- Share project showcases as posts
- Use in "Featured" section

---

## 📞 Support

If you need help with deployment or customization:
1. Check this README first
2. Review the HTML comments in the files
3. GitHub Issues for bugs
4. Email: mouryadusi@outlook.com

---

## 📄 License

© 2025 Mourya Dusi. All rights reserved.

---

## ✅ Deployment Checklist

Before going live, verify:

- [ ] `profile.html` uploaded to repository root
- [ ] `smart-exit-reminder.html` uploaded to repository root
- [ ] GitHub Pages enabled in Settings
- [ ] Portfolio page loads: `/profile.html`
- [ ] Smart Exit Reminder loads: `/smart-exit-reminder.html`
- [ ] "View Full Product Details →" button works
- [ ] "← Back to Portfolio" button works
- [ ] All navigation links functional
- [ ] Mobile responsive (test on phone)
- [ ] Contact links work (email, LinkedIn, GitHub)
- [ ] No console errors (F12 → Console)

---

**Last Updated**: January 2025

**Status**: ✅ Ready for Production Deployment
