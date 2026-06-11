=== SD Media Gallery ===
Contributors:      shohiduldev
Tags:              gallery, image gallery, lightbox, project gallery, portfolio, renovation
Requires at least: 5.8
Tested up to:      6.5
Stable tag:        3.0.0
Requires PHP:      7.4
License:           GPLv2 or later
License URI:       https://www.gnu.org/licenses/gpl-2.0.html

Professional project image gallery with lightbox, thumbnail strip, Custom CSS editor, and category filtering. Built for Safi Works renovation site.

== Description ==

SD Media Gallery is a clean, fast, and professional project gallery plugin for WordPress. It is built specifically for renovation, construction, and portfolio websites that need to showcase multiple projects with multiple images per project.

Each project card supports unlimited images. Visitors can click a card to open a full-screen lightbox with a thumbnail strip, keyboard navigation, and touch swipe support on mobile.

= Key Features =

* Custom post type for projects — clean and organized
* Multiple images per project — unlimited gallery images
* Drag & drop reorder images inside each project
* Full-screen lightbox with thumbnail strip
* Keyboard navigation (← → Escape)
* Touch swipe support on mobile
* Category filtering via shortcode
* Custom CSS editor — restyle without touching files
* Quick CSS presets (Dark, Rounded, Minimal, Large Gap)
* Settings panel — default columns, hover animation toggle
* Responsive grid — 1 to 4 columns
* Admin dashboard with stats, how-to guide, and shortcode reference
* Warning system — alerts admin if heading/subheading missing in shortcode
* Built by Shohidul Dev (@ShohidulDev)

= Shortcode =

Basic usage:
[sd_gallery]

Recommended full usage (required for mobile):
[sd_gallery columns="3" heading="Toteuttamiamme projekteja" subheading="Katso esimerkkejä laadukkaista remonteistamme"]

= Shortcode Options =

* columns       – Number of grid columns. 1 to 4. Default: 3
* heading       – Section heading text. REQUIRED for proper mobile display
* subheading    – Section subheading text. REQUIRED for proper mobile display
* category      – Filter projects by category slug. Default: all

= Important Warning =

Always include heading and subheading in your shortcode.
Without them, the gallery section header will be missing and the layout can break on mobile devices.

Correct:
[sd_gallery columns="3" heading="Our Projects" subheading="Browse our latest work"]

Wrong (mobile may break):
[sd_gallery columns="3"]

== Installation ==

1. Upload the sd-media-gallery folder to /wp-content/plugins/
   OR go to WP Admin → Plugins → Add New → Upload Plugin → select sd-media-gallery.zip
2. Activate the plugin through the Plugins menu in WordPress
3. Go to SD Gallery in the left admin menu
4. Click Add New Project to create your first project
5. Set a Featured Image for each project (used as the card cover)
6. Add gallery images using the Project Images meta box (drag to reorder)
7. Paste [sd_gallery columns="3" heading="..." subheading="..."] on any page or post

== Frequently Asked Questions ==

= What shortcode do I use? =
[sd_gallery] — but always add heading and subheading attributes for correct mobile display.

= Can I add more than one image per project? =
Yes. Each project supports unlimited images. Add them in the Project Images meta box on the edit screen. Drag to reorder. First image = lightbox start position.

= How do I filter by category? =
First assign a category to your projects using the Gallery Categories taxonomy on the project edit screen. Then use category="your-slug" in the shortcode.
Example: [sd_gallery category="bathroom"]

= How do I change the gallery style? =
Go to SD Gallery → Custom CSS. Write your own CSS or choose a quick preset. Changes apply to the gallery on the frontend only and are safe from plugin updates.

= What CSS classes can I target? =
Main classes:
.safi-gallery-section    — outer section wrapper
.safi-gallery-grid       — card grid container
.safi-gallery-card       — individual project card
.safi-card-overlay       — gradient overlay on card
.safi-card-title         — project title on card
.safi-card-count         — image count on card
.safi-gallery-heading    — section heading
.safi-gallery-subheading — section subheading
.safi-lightbox           — lightbox container
.safi-lb-img             — main lightbox image
.safi-lb-thumb           — thumbnail strip items

= Is it mobile responsive? =
Yes. The grid collapses automatically on smaller screens. Lightbox supports touch swipe. Always use heading and subheading in your shortcode for best mobile layout.

= How do I reorder projects? =
Set the Menu Order field on each project edit screen (lower number = shown first).

== Screenshots ==

1. Dashboard — stats, how-to guide, shortcode reference, and recent projects
2. Frontend gallery grid — 3-column responsive card layout
3. Lightbox — full screen image viewer with thumbnail strip
4. Custom CSS editor — with quick presets and class reference
5. Add New Project — image meta box with drag-to-reorder
6. Warning message — shown when shortcode is missing heading/subheading

== Changelog ==

= 3.0.0 =
* Renamed plugin to SD Media Gallery
* New shortcode: [sd_gallery] (replaces [safi_gallery])
* Added screenshots section in dashboard
* Added warning system for missing heading/subheading
* Admin-only inline warning on frontend when shortcode is incomplete
* Added required badges on heading and subheading in shortcode reference
* Improved dashboard UI with stats, recent projects, and social links
* Custom CSS editor with 5 quick presets
* Settings page with default columns and animation toggle
* Full social links in footer: GitHub, LinkedIn, Instagram, X, Facebook

= 2.0.0 =
* Added custom admin dashboard
* Added Custom CSS editor
* Added Settings page
* Added ShohidulDev branding and social links
* Improved admin UI with visual stats and how-to guide

= 1.1.0 =
* Initial public release
* Custom post type for projects
* Multiple images per project with drag reorder
* Lightbox with thumbnail strip
* Keyboard and touch navigation
* Category filtering via shortcode

== Upgrade Notice ==

= 3.0.0 =
Shortcode changed from [safi_gallery] to [sd_gallery]. Please update all pages where you use the gallery shortcode after upgrading.

== Credits ==

Built by Shohidul Dev (@ShohidulDev)
Head of Operations at InsoSpark Agency
Shopify & WordPress developer

GitHub:    https://github.com/ShohidulDev
LinkedIn:  https://linkedin.com/in/shohiduldev
Instagram: https://instagram.com/shohiduldev
X:         https://x.com/shohiduldev
Facebook:  https://facebook.com/shohiduldev
Threads:   https://threads.net/@shohiduldev
Telegram:  https://t.me/shohiduldev

#shohiduldev
