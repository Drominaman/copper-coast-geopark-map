# Copper Coast Geopark Interactive Map

## Deployment Instructions

### Drag & Drop to Netlify:

1. Go to https://app.netlify.com/drop
2. Drag the entire **website** folder onto the page
3. Wait for deployment to complete
4. Your site will be live with a random URL (e.g., `random-name-123456.netlify.app`)

### Admin Panel

After deployment, you can access:
- **Map:** `https://your-site.netlify.app/`
- **Admin Panel:** `https://your-site.netlify.app/admin.html`

### How to Edit Content:

1. Go to `/admin.html` on your deployed site
2. Edit location titles and descriptions
3. Click **"💾 Save & Apply to Map"** for instant preview
4. Click **"📥 Download JSON"** to save changes permanently
5. Replace `tooltips-data.json` on your computer
6. Re-deploy to Netlify by dragging the folder again

## Files:
- `index.html` - Main interactive map
- `admin.html` - Content management panel
- `tooltips-data.json` - Location data
- `css/` - Stylesheets
- `js/` - JavaScript files
- `images/` - Map images

## Features:
- 33 interactive location markers
- Mobile responsive with pan/zoom
- Admin panel for easy content editing
- Live preview with localStorage
