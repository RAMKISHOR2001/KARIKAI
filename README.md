# ToteBag Co. - Premium Tote Bag Website

A professional, modern e-commerce website for a premium tote bag business. Built with clean HTML, CSS, and JavaScript.

## 📁 Project Structure

```
frontend/
├── index.html           # Homepage with hero section and featured products
├── products.html        # Product listing page with filtering
├── product.html         # Individual product detail page
├── about.html          # Company information and team
├── contact.html        # Contact form and company details
├── products.csv        # Product database in CSV format
├── assets/
│   └── style.css       # Complete responsive stylesheet
└── images/             # Product images directory
```

## 🎨 Features

### Pages Included
- **Homepage (index.html)** - Eye-catching hero section, featured collections, value propositions, and newsletter signup
- **Products (products.html)** - Complete product catalog with filtering by type (Canvas, Leather, Eco-Friendly, Designer)
- **Product Details (product.html)** - Individual product pages with images, descriptions, reviews, and related products
- **About Us (about.html)** - Company story, values, team members, and statistics
- **Contact (contact.html)** - Contact form, location information, FAQ, and customer support details

### Design Features
- Responsive mobile-first design
- Modern color scheme (earthy tones - browns, beiges, and warm accents)
- Sticky navigation bar
- Product filtering system
- Customer reviews section
- Newsletter subscription form
- FAQ accordion-style content
- Professional footer with links and social media

### Functionality
- Dynamic product listing from CSV file
- Product filtering by category
- Contact form with validation
- Add to Cart functionality
- Wishlist feature
- Product rating system
- Responsive grid layouts

## 📦 Product Categories

The website features three main product categories:

1. **Canvas Totes** - Classic, durable canvas bags for daily use
2. **Eco-Friendly Totes** - Sustainable, organic cotton options
3. **Premium Leather Totes** - Luxurious leather construction
4. **Designer Totes** - Unique patterns and artistic designs

## 🎯 Product Data

Products are stored in `products.csv` with the following fields:
- id
- name
- price
- image
- description
- type

## 🛠️ Customization

### Colors
Edit the CSS variables in `assets/style.css`:
```css
:root {
    --primary-color: #8a5a44;      /* Main brand color */
    --secondary-color: #d4a574;    /* Secondary accent */
    --accent-color: #f5b87c;       /* Call-to-action color */
}
```

### Products
Add new products by editing `products.csv` and adding product images to the `images/` folder.

### Contact Information
Update the contact details in `contact.html` with your business information.

### Social Media
Update social media links in the footer sections of all pages.

## 📱 Responsive Breakpoints

- **Desktop**: Full layout with multi-column grids
- **Tablet (768px)**: Adjusted grid columns and spacing
- **Mobile (480px)**: Single-column layouts, optimized touch targets

## 🚀 Getting Started

1. Copy all files to your web server
2. Ensure the directory structure is maintained
3. Update `products.csv` with your product information
4. Add product images to the `images/` folder
5. Update contact information in `contact.html`
6. Customize colors and branding in `assets/style.css`

## 📄 File Details

### HTML Files
- Clean, semantic HTML5 structure
- Accessibility-friendly markup
- Meta tags for SEO optimization
- Mobile viewport configuration

### CSS
- Modern CSS Grid and Flexbox layouts
- Mobile-first responsive design
- Custom CSS properties for easy theming
- Smooth transitions and hover effects
- Print-friendly styles

### JavaScript
- Dynamic product loading from CSV
- Form handling and validation
- Interactive filter functionality
- Event listeners for shopping interactions

## 🎁 Special Sections

- **Newsletter Signup** - Gradient section with email subscription
- **Featured Collections** - Showcase top products on homepage
- **Why Choose Us** - Four key value propositions
- **Team Section** - About page featuring company team
- **Customer Reviews** - Product testimonials and ratings
- **Related Products** - Cross-selling recommendations
- **FAQ Section** - Common customer questions

## 📞 Contact & Support

The website includes:
- Contact form for customer inquiries
- Multiple contact methods (email, phone, social media)
- FAQ section for quick answers
- Shipping and return information
- Business hours and response time expectations

## 🔐 Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📝 Notes

- All images use placeholder URLs from Unsplash (update with your own product photos)
- The CSV-based product system is simple for small catalogs (consider a database for larger inventories)
- Email functionality requires backend implementation
- Shopping cart functionality requires backend integration

## 🎨 Design Credits

- Color scheme inspired by natural, sustainable fashion brands
- Typography uses system fonts for fast loading
- Icons use Unicode emoji characters

---

Created for ToteBag Co. - Premium sustainable tote bags for the modern lifestyle.
