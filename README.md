# Portfolio - Daniel Arnouk

This is a portfolio showcasing GIS and cartography projects.

## 📁 Project Structure (Reorganized December 2024)

```
Portfolio/
├── index.html              # Home page with project gallery
├── about.html              # About page
├── resume.html             # Resume/CV page
├── contact.html            # Contact information and form
│
├── projects/               # All project detail pages (NEW)
│   ├── guadalupe.html      # Guadalupe Mountains Contour Map
│   ├── hexagon.html        # Healthcare Expenditures Hexagon Map
│   ├── wyoming.html        # Wyoming Tourist Attractions Map
│   ├── spooky.html         # Wisconsin's Ghoulish Wonders Map
│   ├── infographic.html    # Broadband Disparity Infographic
│   └── broadband.html      # Dane County Internet Speed Map
│
├── css/
│   ├── style.css           # Consolidated custom styles
│   └── bootstrap.min.css   # Bootstrap framework styles
│
├── js/                     # JavaScript files (MOVED from lib/)
│   ├── jquery-3.5.1.min.js
│   └── bootstrap.min.js
│
└── assets/
    ├── pfp.png             # Profile picture
    ├── 2.png               # Infographic asset
    └── images/             # Organized image folders (NEW)
        ├── thumbnails/     # Project thumbnail images
        │   ├── Broadband-thumbnail.png
        │   ├── Guadalupe-thumbnail.jpg
        │   ├── Hexagon-thumbnail.png
        │   ├── Infographic-thumbnail.png
        │   ├── Spooky-thumbnail.png
        │   └── Wyoming-thumbnail.png
        │
        └── maps/           # Full-size project maps
            ├── Guadalupe-map.png
            ├── Hexagon_Map.png
            ├── Hexagon_Map_Layout.png
            ├── Spooky-map.png
            ├── Wyoming-map.png
            └── Halloween-map.png
```

## 🔄 What Changed?

### Code Improvements
- ✅ **Removed all inline styles** - Consolidated into `css/style.css`
- ✅ **Consistent Bootstrap usage** - Standardized on Bootstrap 4 syntax throughout
- ✅ **Cleaner HTML** - Removed redundant style blocks and duplicate code
- ✅ **Proper script paths** - Consistent JS file references across all pages
- ✅ **Added page-specific body classes** - `secondary-page` for styling consistency

### File Organization
- ✅ **Projects folder** - All project pages now in `/projects/`
- ✅ **Image organization** - Separated thumbnails and full maps
- ✅ **JS folder** - Renamed from `lib/` to `js/` for clarity
- ✅ **Better titles** - More descriptive page titles in `<title>` tags

### Visual Design
- ⚠️ **NO CHANGES** to styling, colors, or visual appearance
- ⚠️ Your existing design, colors, and layout remain exactly the same
- ⚠️ All navbar colors, jumbotron styles, and card layouts preserved

## 🗑️ Old Files to Remove

The following files in the root directory are now obsolete and can be deleted:
- `broadband.html` (moved to `projects/`)
- `guadalupe.html` (moved to `projects/`)
- `hexagon.html` (moved to `projects/`)
- `infographic.html` (moved to `projects/`)
- `spooky.html` (moved to `projects/`)
- `wyoming.html` (moved to `projects/`)
- `bootstrap.html` (unused file)
- `lib/` folder (files moved to `js/`)
- `lib/npm.js` (unused file)

## 🚀 Next Steps (Optional)

When you're ready to modernize further, consider:
1. Add a build system (Webpack, Vite, or Parcel)
2. Create interactive maps with Leaflet or Mapbox
3. Add a projects data file (JSON) to drive the gallery dynamically
4. Implement responsive image loading
5. Add SEO meta tags and Open Graph tags
6. Consider migrating to a static site generator or modern framework

## 📝 Notes

- All external links (ArcGIS Experience Builder iframe) remain functional
- Bootstrap Solar theme still loaded from CDN
- All existing content and copy unchanged
- File structure is now more maintainable and scalable
