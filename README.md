# Jhinna Salinas - Professional Portfolio

Production-ready GitHub Pages portfolio showcasing automation engineering and wellness coaching expertise.

## Setup Instructions

### Option 1: GitHub Pages (Recommended)

1. **Create a new GitHub repository:**
   - Go to github.com and create a new repository
   - Name it: `jhinna-salinas-portfolio` (or your preferred name)
   - Make it public

2. **Upload these files:**
   - `index.html`
   - `styles.css`
   - `script.js`
   - `README.md`

3. **Enable GitHub Pages:**
   - Go to repository Settings > Pages
   - Source: Deploy from a branch
   - Branch: `main` / `root`
   - Click Save

4. **Access your site:**
   - Your portfolio will be live at: `https://[your-username].github.io/jhinna-salinas-portfolio`
   - Wait 2-3 minutes for initial deployment

### Option 2: Custom Domain (Optional)

If you want to use a custom domain (e.g., jhinnasalinas.com):

1. **Purchase domain** from provider (Namecheap, Google Domains, etc.)

2. **Configure DNS settings:**
   - Add A records pointing to GitHub Pages IPs:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153
   - Add CNAME record: `www` pointing to `[your-username].github.io`

3. **Update GitHub Pages settings:**
   - Go to repository Settings > Pages
   - Custom domain: enter your domain
   - Check "Enforce HTTPS"

## Portfolio Structure

### Two Distinct Portfolio Types

This portfolio site showcases two complementary professional identities:

#### 1. **Operations & Automation Portfolio** (Primary)
- 5 production-grade automation projects
- 1,600+ lines of code samples (sanitized)
- Measurable impact metrics (104+ hours saved, 97% efficiency gains)
- Technical skills: Google Apps Script, BigQuery, API integrations
- Target roles: Operations Manager, Solutions Engineer, Technical PM

#### 2. **Wellness & Coaching Portfolio** (Complementary)
- Duke Certified Health & Well-Being Coach
- Asana Certified Workflow Specialist
- 7+ years client experience strategy
- Energy management and sustainable performance expertise
- How wellness expertise enhances operations work

Both portfolios demonstrate:
- **Strategic problem-solving**
- **Human-centered design**
- **Cross-functional leadership**
- **Measurable results**

## Customization

### Update Contact Information

Edit `index.html` and update:
- Line 217: LinkedIn URL
- Line 448-452: Email, phone, LinkedIn links

### Update Resume Link

Add a link to your resume PDF:
1. Upload `JSalinas Resume.docx.pdf` to the repository
2. Add button in hero section:
```html
<a href="JSalinas Resume.docx.pdf" class="btn btn-secondary" download>Download Resume</a>
```

### Add More Projects

To add additional projects, copy a project-card div in `index.html` and update:
- Project title
- Challenge description
- Solution details
- Key features
- Impact metrics
- Code samples (if applicable)

## Features

- **Responsive Design**: Mobile-friendly layout
- **Smooth Scrolling**: Navigation with smooth scroll behavior
- **Code Sample Toggles**: Expandable code blocks
- **Professional Styling**: Clean, modern design
- **SEO Optimized**: Meta tags and semantic HTML
- **Performance**: Fast loading with minimal dependencies

## File Structure

```
portfolio-site/
├── index.html          # Main HTML file
├── styles.css          # All styling
├── script.js           # Interactive features
└── README.md           # This file
```

## Technical Notes

### No Proprietary Information
All code samples have been sanitized to remove:
- Company names
- Proprietary business logic
- Credentials and API keys
- Specific data structures
- Internal system details

### Browser Compatibility
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

### Performance
- No external dependencies
- Vanilla JavaScript (no frameworks)
- Optimized CSS
- Fast load times (<1s)

## Maintenance

### Updating Projects
1. Edit `index.html`
2. Update project details in the relevant project-card div
3. Commit and push to GitHub
4. Changes will be live in 1-2 minutes

### Adding New Sections
1. Add new section in `index.html`
2. Add corresponding styles in `styles.css`
3. Update navigation menu
4. Test responsive behavior

## Support

For questions about setup or customization:
- Email: Jhinna.Salinas@gmail.com
- LinkedIn: linkedin.com/in/jhinna-salinas

## License

© 2025 Jhinna Salinas. All rights reserved.

All code samples demonstrate technical approach and problem-solving methodology. Proprietary business logic and sensitive information have been removed to protect confidential company data.
