# WP Production Snippets

Curated, production-ready WordPress snippets for real-world projects.

## Structure

| Folder | Contents |
|---|---|
| `admin/` | Admin UI and dashboard tweaks |
| `security/` | Security hardening |
| `performance/` | Speed and optimization |
| `frontend/` | Theme and frontend helpers |
| `seo/` | SEO and URL improvements |
| `block-theme/` | Block theme utilities |
| `woocommerce/` | WooCommerce-specific utilities |

## Usage

Each snippet is a standalone `.php` file. Either:
- Copy the contents into your theme's `functions.php`, or
- Add it via a custom functionality plugin (e.g. Code Snippets).

All snippets are tested on WordPress 6.x.

## Snippets

### `admin/editable-username.php`
Allows admins or users to change their WordPress username from the profile screen. Performs a direct database update — use with care.

### `frontend/live-clock-shortcode.php`
Real-time clock shortcode `[live_clock]` displaying either the site's timezone or the visitor's local time. Configurable via in-file settings.

### `seo/remove-category-tag-base.php`
Strips `/category/` and `/tag/` from taxonomy URLs with 301 redirects for old paths. Supports hierarchical categories and pagination.

### `block-theme/time-based-style-variation-switcher.php`
Automatically switches a block theme's style variation based on the site's local time of day.

### `performance/lightweight-cache-control.php`
Basic cache control without a plugin — includes cache headers, CSS/JS versioning, and an admin bar purge button.

### `admin/duplicate-posts-pages.php`
Adds a "Duplicate" row action to posts and pages, creating a draft copy with content, taxonomies, and custom fields.

### `admin/per-post-visibility-toggles.php`
Per-post sidebar toggles to hide the featured image or excerpt on the frontend.

---

Built by [Tomi Abe Studio](https://studio.tomiabe.com)