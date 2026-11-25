# 🎨 Color Palette & Component Reference

## 🎯 Complete Design System

### Primary Colors
```
Brand Green
Hex: #215C58
RGB: (33, 92, 88)
Usage: Headers, main sections, primary text

Dark Green
Hex: #0D2422
RGB: (13, 36, 34)
Usage: Footer, dark backgrounds

Accent Pink/Magenta
Hex: #8C2851
RGB: (140, 40, 81)
Usage: Buttons, links, highlights

Light Color
Hex: #FAFCFC
RGB: (250, 252, 252)
Usage: Light text, card backgrounds

Light Gray
Hex: #F4F7F7
RGB: (244, 247, 247)
Usage: Secondary light background
```

---

## 📐 Component Library

### Button Styles

#### Primary Button
```css
Background: #8C2851 (Accent Pink)
Text: #FAFCFC (Light)
Size: Large (15px 30px)
Hover: Lighter pink background
Border Radius: 8px
Font Weight: Bold
```
Used for: "Shop Now", "Subscribe", "Get Offer", "Add to Cart"

#### Secondary Button
```css
Background: Transparent
Border: 2px solid #FAFCFC
Text: #FAFCFC
Size: Large (15px 30px)
Hover: Fill with light background
Border Radius: 8px
Font Weight: Bold
```
Used for: "Learn More", optional actions

---

### Card Components

#### Product Card
```
┌──────────────────────┐
│   Product Image      │ (250px height)
├──────────────────────┤
│ Product Name (H5)    │
│ Description Text     │
├──────────────────────┤
│ $Price    [Add >]    │
└──────────────────────┘

Background: #FAFCFC
Shadow: 0 4px 15px rgba(0,0,0,0.1)
Hover: Transform translateY(-8px)
Border Radius: 12px
Padding: 20px
```

#### Promotion Card
```
┌──────────────────────┐
│   🏷️ 30% OFF       │
│                      │
│ Premium Coffee       │
│ Limited Time!        │
│                      │
│   [Get Offer]        │
└──────────────────────┘

Background: White
Shadow: 0 6px 20px rgba(0,0,0,0.1)
Hover: Transform translateY(-5px)
Border Radius: 16px
Padding: 40px
```

---

### Typography System

#### Display Fonts (Headings)
```
Font Family: Bricolage Grotesque
H1 (Display 5): 2.5rem, Bold, #FAFCFC
H2 (Display 6): 1.8rem, Bold, #FAFCFC
H3: 1.5rem, Bold, #8C2851
H4: 1.25rem, Bold, #344645
H5: 1.1rem, Bold, #344645
```

#### Body Fonts
```
Font Family: Geist
Size: 1rem
Line Height: 1.5-1.8
Weight: 400 (regular)
Color: #F4F7F7 (light), #344645 (dark)
```

#### Accent Fonts
```
Font Family: Space Mono (Monospace)
Used for: Pricing, special elements
Size: 1.5rem
Weight: 700 (bold)
Color: #8C2851
```

---

### Section Styling

#### Featured Section
```
Background: linear-gradient(135deg, #215C58 0%, #0D2422 100%)
Padding: 3rem vertical, 1rem horizontal
Text Color: #FAFCFC
Rounded Corners: 16px on images
```

#### Products Section
```
Background: #215C58
Padding: 3rem
Grid Columns: 3 (desktop), 2 (tablet), 1 (mobile)
Gap Between Cards: 16px
Section Title Color: #FAFCFC
Section Subtitle Color: #F4F7F7
```

#### Promotion Section
```
Background: linear-gradient(135deg, #8C2851 0%, #215C58 100%)
Padding: 3rem
Card Background: White
Card Count: 2 cards, 50% width each
Icon Color: #8C2851
Icon Size: 2rem
```

#### FAQ Section
```
Background: #215C58
Padding: 3rem
Accordion Item Background: rgba(255,255,255,0.05)
Accordion Item Border: 1px solid rgba(255,255,255,0.1)
Accordion Button Background: rgba(255,255,255,0.05)
Accordion Button Hover: rgba(255,255,255,0.1)
Text Color: #FAFCFC
Rounded Corners: 10px
```

#### Subscribe Section
```
Background: linear-gradient(135deg, #8C2851 0%, #215C58 100%)
Content Background: rgba(250,252,252,0.95)
Content Padding: 3rem
Input Border: 2px solid #8C2851
Input Focus: Box shadow 0 0 0 0.25rem
Button: Primary style
Rounded Corners: 16px content
```

---

### Form Elements

#### Input Field
```
Border: 2px solid #8C2851
Border Radius: 8px
Padding: 12px 15px
Background: White
Font: Geist, 1rem
Placeholder Color: rgba(13,36,34,0.5)

Focus State:
  Border Color: #8C2851
  Box Shadow: 0 0 0 0.25rem rgba(140,40,81,0.25)
  Outline: None
```

#### Select/Dropdown
```
Inherits input styling
Padding: 12px 15px
Font: Geist, 1rem
Icon Color: #8C2851
```

---

### Spacing System

#### Padding Scale
```
xs: 8px (p-1)
sm: 12px (p-2)
md: 16px (p-3)
lg: 20px (p-4)
xl: 30px (p-5)
```

#### Margin Scale
```
xs: 8px (m-1)
sm: 12px (m-2)
md: 16px (m-3)
lg: 20px (m-4)
xl: 30px (m-5)
```

#### Gap (Flexbox/Grid)
```
Tight: 8px (gap-1)
Normal: 16px (gap-3)
Loose: 24px (gap-4)
Extra: 30px (gap-5)
```

---

### Shadow System

#### Light Shadow
```
box-shadow: 0 1px 3px rgba(0,0,0,0.1);
```

#### Medium Shadow (Card Hover)
```
box-shadow: 0 4px 15px rgba(0,0,0,0.1);
```

#### Large Shadow (Promoted Items)
```
box-shadow: 0 8px 25px rgba(0,0,0,0.15);
```

#### Deep Shadow (Modals)
```
box-shadow: 0 10px 30px rgba(0,0,0,0.2);
```

---

### Animation & Transitions

#### Smooth Transition
```css
transition: all 0.3s ease;
```
Applied to: Buttons, cards, links

#### Card Hover Animation
```css
transform: translateY(-8px);
box-shadow: 0 8px 25px rgba(0,0,0,0.15);
```

#### Button Hover
```css
background-color: (lighter shade);
transform: translateY(-2px);
box-shadow: 0 4px 12px rgba(0,0,0,0.15);
```

#### Accordion Animation
```css
max-height: (auto);
opacity: 1;
transition: max-height 0.3s ease, opacity 0.3s ease;
```

---

### Border Radius Scale

```
Small: 4px (borders)
Medium: 8px (inputs, buttons)
Large: 12px (cards)
Extra Large: 16px (sections)
Full Round: 50% (avatars)
```

---

### Icon System

#### Usage
Font: Font Awesome 7.3.1
Size Scale:
- Small: 1rem
- Medium: 1.5rem
- Large: 2rem
- Extra Large: 2.5rem

#### Color
Primary Icon: #8C2851
Secondary Icon: #215C58
Light Icon: #FAFCFC
Success Icon: #28a745

---

## 🎯 Responsive Breakpoints

### Mobile-First Approach
```
Small (mobile): 0px - 576px
Medium (tablet): 576px - 768px
Large (tablet/small desktop): 768px - 992px
Extra Large (desktop): 992px - 1200px
XXL (large desktop): 1200px+
```

### Key Breakpoint: 768px
- Product grid: 3 columns → 1 column
- Sections: 2 columns → 1 column
- Padding reduced: 3rem → 1rem
- Font sizes scaled down
- Touch targets increased

---

## 🎨 Gradient Combinations

### Primary Gradient (Brand)
```
Direction: 135deg
Colors: #215C58 → #0D2422
Used in: Featured, About sections
```

### Secondary Gradient (Accent)
```
Direction: 135deg
Colors: #8C2851 → #215C58
Used in: Promotion, Subscribe sections
```

### Overlay Gradient
```
Colors: rgba(255,255,255,0.05) → rgba(255,255,255,0.1)
Used in: Accordion items, overlays
```

---

## ✨ Visual Hierarchy

### Weight Distribution
1. **Headlines** (Display 5-6): Largest, boldest
2. **Section Titles** (H2-H3): Large, bold
3. **Card Titles** (H5): Medium, bold
4. **Body Text**: Regular weight, good line height
5. **Small Text**: Muted color, 0.875rem

### Color Hierarchy
1. **Primary**: Light (#FAFCFC) on dark backgrounds
2. **Secondary**: Gray (#F4F7F7) on dark backgrounds
3. **Accent**: Pink (#8C2851) for CTAs and highlights
4. **Muted**: Dark gray (#8C2851 50% opacity)

---

## 🎁 Ready-to-Use Components

All components are:
✅ Fully styled
✅ Responsive
✅ Accessible
✅ Interactive
✅ Production-ready

Just customize content and deploy!

---

**Design System Version**: 1.0  
**Last Updated**: November 25, 2026  
**Status**: Complete & Production Ready

