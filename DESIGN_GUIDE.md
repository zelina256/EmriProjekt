# Coffee Cup Website - Design Guide

## 🎨 Color Scheme

### Primary Colors (from CSS variables)
- **Brand Green**: `#215C58` (Primary brand color)
- **Dark Green**: `#0D2422` (Footer background)
- **Pink/Magenta**: `#8C2851` (Accent color for buttons and highlights)
- **Light**: `#FAFCFC` (Primary light color)
- **Light Gray**: `#F4F7F7` (Secondary light color)

### Usage
- **Headers**: Brand Green + Gradient backgrounds
- **Buttons**: Pink/Magenta primary, Gradient on hover
- **Text**: Light colors on dark backgrounds
- **Cards**: Light backgrounds with dark text

---

## 📐 Layout Sections

### 1. Navigation Bar
- Sticky navbar with logo and menu
- Search functionality
- Dropdown category menu
- Responsive hamburger menu on mobile

### 2. Hero Carousel
- Automatic image slider
- 3 featured products/promotions
- Smooth transitions between slides
- Indicators and navigation buttons

### 3. Featured Section
- Welcome section with gradient background
- Two-column layout (text + image)
- Dual CTAs: "Shop Now" and "Learn More"
- Responsive stacking on mobile

### 4. Products Grid
- 6 product cards in 3-column layout
- Each card shows:
  - Product image
  - Product name
  - Description
  - Price
  - "Add to Cart" button
- Hover effects: lift and shadow
- Mobile responsive: 1-2 columns

### 5. Promotion Banner
- Full-width gradient background
- 2 promotional offer cards
- Icons for visual interest
- Special offers: 30% OFF & Free Shipping
- Call-to-action buttons

### 6. About Section
- Two-column layout (text + map)
- Features list with checkmarks
- Embedded Google Map
- Brand story and values
- Responsive stacking

### 7. FAQ Section
- Beautiful accordion interface
- 5 common questions answered
- Icons for question indicators
- Smooth expand/collapse animations
- Mobile-friendly

### 8. Subscribe Section
- Email subscription form
- Privacy messaging
- Newsletter benefits highlighted
- Large input fields for easy interaction
- Full-width promotional background

### 9. Footer
- 4-column layout (Company info, Links, Contact, Subscribe)
- Social media links
- Quick navigation links
- Copyright and legal links
- Newsletter subscription form

---

## 🎯 Color Usage by Section

| Section | Background | Text | Accent |
|---------|-----------|------|--------|
| Featured | Gradient (Brand to Dark) | Light | Pink |
| Products | Brand Green | Light | Pink |
| Promotions | Gradient (Pink to Brand) | Light | White |
| FAQ | Brand Green | Light | Pink |
| Subscribe | Gradient (Pink to Brand) | Light | Dark |
| Footer | Dark Green | Light | Pink |

---

## 📱 Responsive Breakpoints

```css
Desktop (> 992px):
- 3-column product grid
- 2-column sections
- Full-width layout

Tablet (768px - 992px):
- 2-column product grid
- Responsive columns
- Adjusted padding

Mobile (< 768px):
- 1-column product grid
- Stacked sections
- Full-width buttons
- Smaller fonts
- Adjusted spacing
```

---

## ✨ Interactive Elements

### Hover Effects
- **Cards**: Lift up with shadow increase
- **Buttons**: Background color change, smooth transition
- **Links**: Color change to accent (Pink)

### Animations
- Smooth transitions (0.3s)
- Transform on hover (translateY)
- Shadow depth changes
- Accordion smooth collapse/expand

---

## 🔤 Typography

### Fonts
- **Headers**: "Bricolage Grotesque" (Bold, Large)
- **Body Text**: "Geist" (Regular, Readable)
- **Accent**: "Space Mono" (Monospace, Pricing)

### Font Sizes
- **H1/H2 (Display)**: 2.5rem - 3.5rem
- **H3/H4**: 1.5rem - 2rem
- **Body**: 1rem
- **Small**: 0.875rem

---

## 🎁 Product Card Specifications

```html
Height: Flexible
Width: 1/3 desktop, 1/2 tablet, full mobile
Image Height: 250px desktop, 200px mobile
Image Fit: Cover (maintains aspect ratio)
Padding: 20px inside card
Margin: 16px between cards
Border Radius: 12px
Shadow: 0 4px 15px rgba(0,0,0,0.1)
```

---

## 📋 Form Elements

### Input Fields
- Border: 2px solid Pink
- Border Radius: 8px
- Padding: 12px
- Focus State: Pink background with shadow
- Placeholder: Semi-transparent text

### Buttons
- Padding: 10px 20px (small), 15px 30px (large)
- Border Radius: 8px
- Font Weight: Bold
- Transition: 0.3s ease
- Hover: Background color change

---

## 🎨 Gradient Backgrounds

### Primary Gradient
```css
linear-gradient(135deg, #215C58 0%, #0D2422 100%)
Used in: Featured section, About section
```

### Accent Gradient
```css
linear-gradient(135deg, #8C2851 0%, #215C58 100%)
Used in: Promotion banner
```

### Subscribe Gradient
```css
linear-gradient(135deg, #8C2851 0%, #215C58 100%)
Used in: Subscribe section background
```

---

## 🔍 Accessibility Features

- Semantic HTML structure (main, section, header, footer)
- Proper heading hierarchy (h2, h4)
- ARIA labels on interactive elements
- Sufficient color contrast
- Keyboard navigation support
- Form labels associated with inputs
- Alt text on images

---

## 📊 Spacing System

### Padding
- Sections: `py-5` (3rem) on desktop
- Containers: `px-3` (1rem) on mobile
- Cards: `p-5` (3rem)
- Mobile reduction: `py-3` to `py-4`

### Margins
- Section spacing: 20px - 30px
- Text margins: 12px - 20px
- Button gaps: `gap-3` (1rem)

---

## 🎯 Call-to-Action Buttons

### Primary CTA
- Background: Pink (`#8C2851`)
- Text: Light (`#FAFCFC`)
- Size: Large (btn-lg)
- Text: "Shop Now", "Subscribe", "Get Offer"

### Secondary CTA
- Background: Transparent
- Border: Light
- Text: Light
- Size: Large (btn-lg)
- Text: "Learn More", "Shop Now"

---

## 📸 Image Specifications

### Product Images
- Format: JPG/PNG
- Size: 400x300px or larger
- Aspect Ratio: 4:3
- Optimization: Compressed for web

### Section Images
- Full responsive width
- Min-height: 300px mobile, 400px desktop
- Object-fit: Cover

---

## 🚀 Performance Tips

1. Optimize images for web
2. Use CSS variables for consistency
3. Lazy load images below the fold
4. Minify CSS and JavaScript
5. Use Bootstrap CDN efficiently
6. Cache static assets

---

## 📞 Contact & Support

For design questions or updates, refer to:
- CSS Variables: `css/style.css`
- Component Styles: `css/style.css`
- HTML Structure: `index.html`

