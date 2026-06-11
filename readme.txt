# SD Media Gallery

> A professional WordPress project gallery plugin with fullscreen lightbox, thumbnail navigation, category filtering, Custom CSS editor, and responsive layouts.

Built by **[Shohidul Dev](https://threads.net/@shohiduldev)** · `#shohiduldev`

---

## 📌 Overview

**SD Media Gallery** helps you showcase renovation projects, portfolios, construction work, case studies, and image collections in a clean and professional gallery.

Each project supports unlimited images. Visitors can browse from a responsive grid and open a fullscreen lightbox with thumbnail navigation, keyboard controls, and mobile swipe support.

**Perfect for:**
- Renovation Companies & Construction Businesses
- Interior Designers & Architects
- Agencies & Freelance Portfolios
- Before & After Project Showcases

---

## ✨ Features

### 🖼 Project Gallery System
- Custom Post Type for Projects
- Unlimited images per project
- Featured image support
- Drag & Drop image ordering
- Project sorting via Menu Order

### ⚡ Modern Gallery Experience
- Responsive grid layout (1–4 columns)
- Fullscreen lightbox
- Thumbnail strip navigation
- Previous / Next controls
- Keyboard navigation
- Mobile swipe support

### 🎨 Customization
- Built-in Custom CSS editor
- Quick CSS presets
- Animation toggle
- Default column settings

### 🏷 Organization
- Gallery Categories taxonomy
- Category filtering via shortcode
- Clean project management workflow

### 📊 Admin Dashboard
- Gallery statistics
- Recent projects overview
- Setup guide
- Shortcode reference
- Warning system for incorrect shortcode usage

---

## ⚙️ Requirements

| Requirement | Version |
| ----------- | ------- |
| WordPress   | 5.8+    |
| PHP         | 7.4+    |
| MySQL       | 5.6+    |

---

## 🚀 Installation

### Upload via WordPress Admin

1. Go to **WordPress Admin → Plugins → Add New**
2. Click **Upload Plugin**
3. Upload `sd-media-gallery.zip`
4. Click **Install Now** → **Activate**

### Manual Installation

Upload the plugin folder to:

```
/wp-content/plugins/sd-media-gallery/
```

Then activate from **WordPress Admin → Plugins**.

You'll find the plugin at **Admin Sidebar → SD Gallery**.

---

## 📖 How To Use

### 1. Create a Project

Go to **SD Gallery → Add New Project** and add:
- Project Title
- Featured Image
- Gallery Images
- Categories *(optional)*

Publish the project.

### 2. Display the Gallery

**Basic shortcode:**
```shortcode
[sd_gallery]
```

**Recommended shortcode:**
```shortcode
[sd_gallery columns="3" heading="Our Projects" subheading="Browse our latest work"]
```

---

## 🔧 Shortcode Parameters

| Parameter    | Description                  |
| ------------ | ---------------------------- |
| `columns`    | Grid columns (1–4)           |
| `heading`    | Section heading text         |
| `subheading` | Section subheading text      |
| `category`   | Category slug to filter by   |

### Example

```shortcode
[sd_gallery
  columns="3"
  category="bathroom"
  heading="Bathroom Renovations"
  subheading="Recent completed projects"]
```

> ⚠️ **Important:** Always include `heading=""` and `subheading=""` attributes.  
> Without them, the gallery heading will be missing, mobile layout may break, and an admin warning notice will appear.

---

## 🎨 CSS Classes

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

## 📋 Changelog

### v3.0.0
- Renamed plugin to **SD Media Gallery**
- New shortcode `[sd_gallery]`
- Warning system for missing heading/subheading
- Custom CSS presets
- Settings page
- Social media integration
- Admin frontend notices

### v2.0.0
- Custom dashboard
- Custom CSS editor
- Improved admin interface

### v1.1.0
- Initial public release
- Custom Post Type for projects
- Unlimited gallery images
- Lightbox support
- Category filtering

---

## ⬆️ Upgrading From Older Versions

Old shortcode:
```shortcode
[safi_gallery]
```

New shortcode:
```shortcode
[sd_gallery]
```

Update all existing pages after upgrading.

---

## 📄 License

Licensed under the **[GNU General Public License v2.0+](https://www.gnu.org/licenses/old-licenses/gpl-2.0.en.html)**

---

## 🤝 Support & Contributions

If you find this plugin useful:

- ⭐ **Star** this repository
- 🐞 **Report** issues
- 🚀 **Suggest** new features
- 🤝 **Contribute** improvements

---

## 👤 Author

**Shohidul Dev**  
Shopify & WordPress Developer · Head of Operations at InsoSpark Agency

[![GitHub](https://img.shields.io/badge/GitHub-@shohiduldev-181717?style=flat&logo=github)](https://github.com/shohiduldev)
[![Threads](https://img.shields.io/badge/Threads-@shohiduldev-000000?style=flat&logo=threads)](https://threads.net/@shohiduldev)
[![Telegram](https://img.shields.io/badge/Telegram-@shohiduldev-2CA5E0?style=flat&logo=telegram)](https://t.me/shohiduldev)

---

*Built with ❤️ by Shohidul Dev · `#shohiduldev`*
