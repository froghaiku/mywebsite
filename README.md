# benschoeffler.com

Personal website hosted on GitHub Pages.

## Structure

```
/
├── index.html              # Main placeholder page
├── vacation/               # Japan & South Korea trip itinerary
│   └── index.html
├── assets/
│   ├── css/
│   │   └── main.css       # Shared styles (adapted from WordSen design system)
│   ├── js/
│   │   └── main.js        # Minimal JavaScript interactions
│   └── images/
│       └── vacation/      # Add vacation photos here
├── _config.yml            # Jekyll configuration
└── CNAME                  # Domain configuration
```

## Adding Photos to the Vacation Page

To add photos to the vacation itinerary:

1. Add image files to `/assets/images/vacation/`
2. In `/vacation/index.html`, find the day cards with `<div class="day-image">` placeholders
3. Replace the placeholder with an `<img>` tag:

```html
<div class="day-image">
    <img src="/assets/images/vacation/your-photo.jpg" alt="Description">
</div>
```

## Local Development

To preview the site locally:

```bash
# Install Jekyll (if not already installed)
gem install bundler jekyll

# Serve the site
jekyll serve

# Visit http://localhost:4000
```

## Deployment

This site is configured to deploy automatically via GitHub Pages when you push to the `main` branch.

### First-time Setup:

1. Create a GitHub repository named `benschoeffler.com` (or any name)
2. Add the remote and push:
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/REPO_NAME.git
   git add .
   git commit -m "Initial commit: Personal website with vacation itinerary"
   git push -u origin main
   ```
3. In GitHub repository settings:
   - Go to **Settings** > **Pages**
   - Under "Source", select **Deploy from a branch**
   - Select branch: **main** and folder: **/ (root)**
   - Click **Save**
4. Configure custom domain:
   - In the same Pages settings, add `benschoeffler.com` to "Custom domain"
   - Update your DNS settings with your domain registrar:
     - Add an A record pointing to GitHub Pages IPs:
       - 185.199.108.153
       - 185.199.109.153
       - 185.199.110.153
       - 185.199.111.153
     - Or add a CNAME record pointing to `YOUR_USERNAME.github.io`

## Future Subpages

To add new independent subpages (like `/vacation`):

1. Create a new directory (e.g., `/projects/`)
2. Add an `index.html` file inside
3. The page will be accessible at `benschoeffler.com/projects`

Each subpage is self-contained and can be shared directly without linking from the main page.

## Design System

The site uses a custom design system adapted from the WordSen website:

- **Colors**: Gradient backgrounds, accent color (#dd6245)
- **Typography**: Inter font family with Dancing Script for branding
- **Components**: Cards, timelines, responsive grids
- **Mobile-first**: Fully responsive design

Styles are defined in `/assets/css/main.css` using CSS custom properties for easy customization.

## Notes

- The `WordSenWebsite copy/` folder is reference material and excluded from the site build
- All paths use absolute URLs (starting with `/`) for consistent navigation
- The vacation page features a visual timeline with alternating card layout
- Image placeholders are included—just add photos to make them come alive!

---

**Built with:** HTML, CSS, JavaScript, Jekyll, GitHub Pages
**Last updated:** October 2025
