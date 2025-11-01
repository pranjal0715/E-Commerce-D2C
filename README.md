# Areica - Shopify E-commerce Theme

A modern, feature-rich Shopify theme designed for jewelry and fashion e-commerce stores. This theme is built on the Wpbingo framework and extensively customized for optimal performance and user experience.

## 📋 Table of Contents

- [About](#about)
- [Features](#features)
- [Theme Structure](#theme-structure)
- [Installation](#installation)
- [Configuration](#configuration)
- [Customization](#customization)
- [File Structure](#file-structure)
- [Technology Stack](#technology-stack)
- [Support](#support)
- [License](#license)

## 🎯 About

**Areica** is a premium Shopify theme specifically customized for jewelry and fashion e-commerce stores. Built on the Wpbingo theme framework (v1.0.2), this theme has been extensively customized and enhanced to provide a seamless shopping experience with modern design patterns and advanced functionality.

### Key Highlights

- **6 Different Header Layouts** - Choose from multiple header styles
- **Advanced Product Display** - Multiple product card hover styles (9 variations)
- **Comprehensive Filtering** - Multiple sidebar and filter layouts
- **Multi-language Support** - 51+ language translations included
- **Multi-currency Support** - Built-in currency converter
- **Responsive Design** - Fully optimized for mobile, tablet, and desktop
- **RTL Support** - Right-to-left language support

## ✨ Features

### Header & Navigation

- **6 Header Layouts** - Multiple header styles to choose from
- **Sticky Header** - Sticky navigation option
- **Mobile Menu** - Optimized mobile navigation
- **Search Functionality** - Advanced product search with suggestions
- **Account Integration** - Login/Register popup with custom branding
- **Cart Integration** - Multiple cart styles (Modal, Drawer, Page)

### Product Features

- **9 Product Card Hover Styles** - Choose from various hover effects
- **Product Image Zoom** - 360° image rotation and zoom functionality
- **Quick View** - Quick product preview modal
- **Product Compare** - Side-by-side product comparison
- **Wishlist** - Add products to wishlist
- **Product Reviews** - Integrated review system
- **Variants Display** - Color, size, and image variant selectors
- **Size Chart** - Configurable size chart (HTML or Image)
- **Stock Countdown** - Low stock notifications
- **Sale Notifications** - Real-time purchase notifications

### Collection & Catalog

- **Multiple Filter Layouts** - 8 different filter sidebar styles
- **Grid/List Views** - Toggle between grid and list views
- **Sorting Options** - Multiple sorting criteria
- **Pagination** - Traditional, Load More, and Infinite scroll options
- **Collection Images** - Custom collection banners
- **Product Tabs** - Tabbed product displays

### Shopping Cart

- **3 Cart Styles** - Modal, Drawer, and Full Page cart
- **Free Shipping Bar** - Progress bar showing free shipping threshold
- **Gift Wrap** - Optional gift wrap functionality
- **Shipping Calculator** - Real-time shipping cost calculation
- **Coupon Support** - Discount code integration
- **Order Notes** - Add custom notes to orders

### Homepage Sections

- **Slideshow** - Full-width image slider with customizable content
- **Featured Products** - Showcase best-selling products
- **Product Tabs** - Tabbed product collections
- **Banner Sections** - Multiple banner layouts
- **Lookbook** - Instagram-style product lookbooks
- **Testimonials** - Customer testimonials carousel
- **Newsletter** - Email subscription popup
- **Brand Logos** - Partner/brand showcase
- **Policy Section** - Shipping, returns, and service policies

### Blog & Content

- **4 Blog Layouts** - List, Grid, Modern, and Standard
- **Blog Sidebar** - Customizable blog sidebar
- **Article Templates** - Multiple article layouts
- **Portfolio** - Portfolio showcase template
- **FAQ Templates** - 2 FAQ page layouts
- **Custom Pages** - 4 custom page templates

### Special Features

- **Christmas Effects** - Seasonal decoration effects
- **Before You Leave Popup** - Exit-intent popup with offers
- **Verify Popup** - Age verification popup
- **Cookie Consent** - GDPR-compliant cookie notice
- **Sale Notifications** - Real-time purchase notifications
- **Social Sharing** - Share products on social media
- **RTL Support** - Right-to-left language support
- **51+ Languages** - Pre-translated language files

## 📁 Theme Structure

This theme follows Shopify's standard theme structure:

```
Theme 3rd/
├── assets/          # CSS, JavaScript, images, fonts
├── blocks/          # Reusable block components (48 files)
├── config/          # Theme settings and configuration
├── layout/          # Main theme layouts
├── locales/         # Language translation files (51 languages)
├── sections/        # Page sections (67 sections)
├── snippets/        # Reusable code snippets (86 snippets)
└── templates/       # Page templates (42 templates)
```

## 🚀 Installation

### Prerequisites

- Active Shopify store
- Admin access to your Shopify store
- Shopify CLI (optional, for local development)

### Method 1: Manual Upload via Shopify Admin

1. **Prepare Theme Files**
   - Download or clone this repository
   - Zip the entire theme folder (make sure `config/`, `sections/`, `templates/`, etc. are in the root of the zip)

2. **Upload to Shopify**
   - Log in to your Shopify Admin
   - Navigate to **Online Store > Themes**
   - Click **"Add theme" > "Upload zip file"**
   - Select your theme zip file
   - Wait for upload to complete

3. **Publish Theme**
   - Click **"Actions"** on the uploaded theme
   - Select **"Publish"**

### Method 2: Using Shopify CLI

```bash
# Install Shopify CLI (if not installed)
npm install -g @shopify/cli @shopify/theme

# Navigate to theme directory
cd "Theme 3rd"

# Login to Shopify
shopify auth login

# Push theme to store
shopify theme push
```

## ⚙️ Configuration

### Initial Setup

1. **Go to Theme Customizer**
   - In Shopify Admin, navigate to **Online Store > Themes**
   - Click **"Customize"** on your active theme

2. **Basic Settings**
   - **Colors**: Set your theme colors (primary, secondary, text, background)
   - **Typography**: Configure fonts for headings and body text
   - **Header**: Choose header layout (1-6) and configure menu
   - **Footer**: Configure footer content and links

3. **Product Settings**
   - **Product Card**: Choose hover style and configure product card options
   - **Product Page**: Configure product page layout and features
   - **Quickview**: Enable/disable quick view functionality

4. **Collection Settings**
   - **Filter Layout**: Choose sidebar or dropdown filter style
   - **Product Display**: Configure grid/list views
   - **Pagination**: Select pagination type

5. **Cart Settings**
   - **Cart Type**: Choose Modal, Drawer, or Page
   - **Free Shipping**: Set minimum order for free shipping
   - **Gift Wrap**: Enable gift wrap option

### Customization Settings

Access all settings via **Theme Customizer**:
- Colors & Typography
- Header & Footer
- Product Display Options
- Collection Page Settings
- Cart Configuration
- Blog Layout
- Social Media Integration
- Newsletter Popup
- Sale Notifications
- Multi-currency & Language Settings

## 🎨 Customization

### Logo & Branding

The login/register popup automatically displays:
- Store logo (if configured in header settings)
- Store name (fallback if no logo)

To customize:
1. Go to **Theme Customizer > Header**
2. Upload your logo image
3. The login popup will automatically use this logo

### Custom CSS

Add custom CSS via:
- **Theme Customizer > Theme Settings > Additional CSS**
- Or edit CSS files in `assets/` folder directly

### Custom JavaScript

Add custom JavaScript via:
- **Theme Customizer > Theme Settings > Additional JavaScript**
- Or edit JS files in `assets/` folder

### Modifying Templates

- **Sections**: Edit files in `sections/` folder
- **Snippets**: Edit reusable components in `snippets/` folder
- **Templates**: Edit page templates in `templates/` folder
- **Layouts**: Edit main layout in `layout/theme.liquid`

⚠️ **Important**: Always backup your theme before making customizations!

## 📂 File Structure

### Key Files & Directories

```
assets/
  ├── css-*.css          # Stylesheet files for different sections
  ├── *.js               # JavaScript libraries and custom scripts
  ├── *.woff, *.ttf      # Font files
  └── *.svg              # SVG icons and currency flags

blocks/
  ├── _*.liquid          # Block components (columns, slides, etc.)
  └── *.liquid           # Block types (banners, products, testimonials)

config/
  ├── settings_schema.json   # Theme settings configuration
  └── settings_data.json     # Current theme settings values

layout/
  ├── theme.liquid          # Main theme layout wrapper
  └── password.liquid       # Password-protected store layout

sections/
  ├── header_*.liquid       # 6 Header layout variations
  ├── featured-*.liquid     # Homepage featured sections
  ├── product-*.liquid      # Product page sections
  ├── collection-*.liquid  # Collection page sections
  └── blog-*.liquid         # Blog sections

snippets/
  ├── login-register.liquid    # Custom login/register popup
  ├── product-card.liquid      # Product card component
  ├── header-*.liquid          # Header components
  └── *.liquid                 # Various reusable snippets

templates/
  ├── index.json               # Homepage template
  ├── product.json             # Product page template
  ├── collection.json          # Collection page template
  ├── customers/                # Customer account templates
  └── *.json, *.liquid         # Various page templates

locales/
  └── *.json                   # 51 language translation files
```

### Important Customizations

**Login/Register Popup** (`snippets/login-register.liquid`)
- Displays store logo/name at top center
- "Sign In" heading centered
- Customized styling for brand consistency

## 💻 Technology Stack

### Frontend Technologies

- **Liquid** - Shopify's templating language
- **HTML5** - Semantic markup
- **CSS3** - Modern styling with custom properties
- **JavaScript (ES6+)** - Interactive functionality
- **jQuery 3.5.1** - DOM manipulation and utilities

### Libraries & Frameworks

- **Bootstrap** - CSS framework (minified)
- **Slick.js** - Carousel/slider functionality
- **PhotoSwipe** - Image gallery and zoom
- **LazySizes** - Lazy loading images
- **Velocity.js** - Animation library
- **Handlebars** - Templating
- **Lodash** - JavaScript utility library

### Shopify Features

- Shopify Liquid Objects
- Shopify AJAX API
- Shopify Theme App Extensions
- Shopify Sections & Blocks
- Shopify Locale Files

## 🌍 Multi-language Support

The theme includes pre-translated language files for **51 languages**:

- English (Default)
- Spanish, French, German, Italian
- Portuguese (BR & PT)
- Chinese (Simplified & Traditional)
- Japanese, Korean
- Arabic, Hebrew, Turkish
- Russian, Polish, Czech
- Dutch, Swedish, Norwegian
- And many more...

To activate a language:
1. Go to **Settings > Languages** in Shopify Admin
2. Add your desired language
3. Theme will automatically use appropriate translation file

## 💱 Multi-currency Support

The theme supports multiple currencies with:

- **Shopify Multi-currency** (Shopify Payments)
- **Custom Currency Converter** (Wpbingo implementation)
- **Customer Geolocation** - Auto-detect customer currency
- **Currency Flags** - Visual currency selector
- **Checkout Notification** - Inform customers about checkout currency

## 📱 Responsive Design

The theme is fully responsive across:

- **Desktop** - 1200px and above
- **Laptop** - 992px to 1199px
- **Tablet** - 768px to 991px
- **Mobile** - Below 768px

All sections include mobile-specific settings for:
- Font sizes
- Image sizes
- Spacing and padding
- Layout adjustments

## 🔧 Development

### Local Development Setup

```bash
# Install Shopify CLI
npm install -g @shopify/cli @shopify/theme

# Login to Shopify
shopify auth login

# Start local development server
shopify theme dev

# Pull theme from store
shopify theme pull

# Push theme to store
shopify theme push
```

### File Naming Conventions

- **Sections**: `kebab-case.liquid` (e.g., `featured-products.liquid`)
- **Snippets**: `kebab-case.liquid` (e.g., `product-card.liquid`)
- **Blocks**: `_block-name.liquid` (prefixed with underscore)
- **Assets**: `kebab-case.ext` (e.g., `css-product.css`)

## 📚 Additional Resources

### Documentation Links

- [Shopify Theme Development](https://shopify.dev/themes)
- [Liquid Documentation](https://shopify.dev/api/liquid)
- [Shopify CLI Documentation](https://shopify.dev/themes/tools/cli)

### Base Theme Information

- **Base Theme**: Wpbingo v1.0.2
- **Base Theme Author**: Wpbingo
- **Base Theme Documentation**: https://wpbingo.com/guide/wpbingo
- **Base Theme Support**: https://wpbingo.ticksy.com

## 🐛 Known Issues & Limitations

- Some features require specific Shopify apps or settings
- Custom JavaScript may need updates for new Shopify versions
- Third-party app integrations may require additional configuration

## 🔄 Updates & Maintenance

### Before Updating

1. **Backup Current Theme**
   - Download current theme as backup
   - Document any custom changes

2. **Review Changelog**
   - Check for breaking changes
   - Review new features

3. **Test in Development**
   - Upload to development theme
   - Test all functionality
   - Check responsive design

4. **Deploy to Live**
   - Only after thorough testing
   - Consider off-peak deployment

## 🤝 Support

For issues, questions, or contributions:

1. **Theme-Specific Issues**: Open an issue in this repository
2. **Shopify-Related Issues**: Contact Shopify Support
3. **Base Theme Issues**: Refer to Wpbingo documentation

## 📄 License

This theme is based on the Wpbingo theme framework. 

**Important Notes:**
- This customized version is for use on Shopify stores
- Respect Shopify's Terms of Service
- Commercial use requires appropriate Shopify plan
- Custom modifications made for Areica store

## 👨‍💻 Development Credits

- **Customization & Development**: Areica Development Team
- **Base Theme**: Wpbingo v1.0.2
- **Theme Framework**: Wpbingo

## 📝 Changelog

### Current Version
- Customized login/register popup with brand logo/name
- Centered "Sign In" heading
- Extensive customization for jewelry e-commerce
- Enhanced product display options
- Improved mobile responsiveness

---

**Note**: This theme has been extensively customized for the Areica store. Some features and customizations are specific to the store's requirements.

**For GitHub**: This repository contains a customized Shopify theme based on the Wpbingo framework, developed specifically for jewelry and fashion e-commerce stores.

