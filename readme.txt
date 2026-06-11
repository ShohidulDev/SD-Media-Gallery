# SD Media Gallery — WordPress Project Gallery Plugin

Professional project gallery plugin with fullscreen lightbox, thumbnail navigation, category filtering, Custom CSS editor, and responsive layouts.

Built by Shohidul Dev · #shohiduldev

---

## What It Does

SD Media Gallery helps you showcase renovation projects, portfolios, construction work, case studies, and image collections in a clean and professional gallery.

Each project can contain unlimited images. Visitors can browse projects from a responsive grid and open a fullscreen lightbox with thumbnail navigation, keyboard controls, and mobile swipe support.

Perfect for:

* Renovation Companies
* Construction Businesses
* Interior Designers
* Architects
* Agencies
* Portfolio Websites
* Before & After Project Showcases

---

## Features

### 🖼 Project Gallery System

* Custom Post Type for Projects
* Unlimited images per project
* Featured image support
* Drag & Drop image ordering
* Project sorting via Menu Order

### ⚡ Modern Gallery Experience

* Responsive grid layout
* 1–4 column support
* Fullscreen lightbox
* Thumbnail strip navigation
* Previous / Next controls
* Keyboard navigation
* Mobile swipe support

### 🎨 Customization

* Built-in Custom CSS editor
* Frontend-only styling changes
* Quick CSS presets
* Animation toggle
* Default column settings

### 🏷 Organization

* Gallery Categories taxonomy
* Category filtering via shortcode
* Clean project management workflow

### 📱 Mobile Optimized

* Fully responsive design
* Touch-friendly gallery controls
* Optimized for phones and tablets

### 📊 Admin Dashboard

* Gallery statistics
* Recent projects
* Setup guide
* Shortcode reference
* Warning system for incorrect shortcode usage

---

## Installation

### Upload ZIP

1. Go to WordPress Admin → Plugins → Add New
2. Click Upload Plugin
3. Upload `sd-media-gallery.zip`
4. Click Install Now
5. Activate the plugin

### Manual Installation

Upload the plugin folder to:

```text
/wp-content/plugins/sd-media-gallery/
```

Then activate it from:

```text
WordPress Admin → Plugins
```

You'll find the plugin at:

```text
Admin Sidebar → SD Gallery
```

---

## How To Use

### Create a Project

1. Navigate to:

```text
SD Gallery → Add New Project
```

2. Add:

* Project Title
* Featured Image
* Gallery Images
* Categories (optional)

3. Publish the project

---

### Display Gallery

Basic shortcode:

```shortcode
[sd_gallery]
```

Recommended shortcode:

```shortcode
[sd_gallery
columns="3"
heading="Our Projects"
subheading="Browse our latest work"]
```

---

## Shortcode Parameters

| Parameter  | Description          |
| ---------- | -------------------- |
| columns    | Grid columns (1–4)   |
| heading    | Section heading      |
| subheading | Section subheading   |
| category   | Category slug filter |

### Example

```shortcode
[sd_gallery
columns="3"
category="bathroom"
heading="Bathroom Renovations"
subheading="Recent completed projects"]
```

---

## Important

Always include:

```shortcode
heading=""
subheading=""
```

Without these attributes:

* Gallery heading will be missing
* Mobile layout may not display correctly
* Admin warning notice will appear

---

## Example Gallery Structure

| Project            | Images    |
| ------------------ | --------- |
| Kitchen Renovation | 12 Images |
| Bathroom Remodel   | 8 Images  |
| Office Interior    | 15 Images |
| Home Extension     | 20 Images |

Each project opens inside a fullscreen lightbox with thumbnail navigation.

---

## Available CSS Classes

### Gallery Layout

```css
.safi-gallery-section
.safi-gallery-grid
.safi-gallery-card
```

### Card Elements

```css
.safi-card-overlay
.safi-card-title
.safi-card-count
```

### Section Header

```css
.safi-gallery-heading
.safi-gallery-subheading
```

### Lightbox

```css
.safi-lightbox
.safi-lb-img
.safi-lb-thumb
```

---

## Requirements

| Requirement | Version |
| ----------- | ------- |
| WordPress   | 5.8+    |
| PHP         | 7.4+    |
| MySQL       | 5.6+    |

---

## Changelog

### v3.0.0

* Renamed plugin to SD Media Gallery
* New shortcode `[sd_gallery]`
* Dashboard screenshots section
* Warning system for missing heading/subheading
* Admin frontend notices
* Custom CSS presets
* Settings page
* Social media integration

### v2.0.0

* Added custom dashboard
* Added Custom CSS editor
* Added settings page
* Improved admin interface

### v1.1.0

* Initial public release
* Custom Post Type for projects
* Unlimited gallery images
* Lightbox support
* Category filtering

---

## Upgrade Notice

### Upgrading From Older Versions

Old shortcode:

```shortcode
[safi_gallery]
```

New shortcode:

```shortcode
[sd_gallery]
```

Update existing pages after upgrading.

---

## Author

### Shohidul Dev

Shopify & WordPress Developer

Head of Operations at InsoSpark Agency

GitHub: @shohiduldev

---

## License

GPL-2.0+

Licensed under the GNU General Public License.

---

## Support

If you find this plugin useful:

⭐ Star the repository

🐞 Report issues

🚀 Suggest features

🤝 Contribute improvements

Built with ❤️ by Shohidul Dev

#shohiduldev

Threads:   https://threads.net/@shohiduldev
Telegram:  https://t.me/shohiduldev

#shohiduldev
