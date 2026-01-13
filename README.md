# Responsive Pricing Grid

A modern, responsive pricing grid component built with HTML and CSS, demonstrating best practices in layout design and user interface development.

## 🎯 Features

- **Three Pricing Tiers**: Free, Pro, and Enterprise plans
- **Responsive Design**: Mobile-first approach that adapts seamlessly across all device sizes
- **Equal Height Columns**: Cards maintain consistent height using CSS Grid and Flexbox
- **Interactive Elements**: Hover effects and smooth transitions on cards and buttons
- **Accessible**: Semantic HTML with ARIA labels and keyboard navigation support
- **Reusable Components**: Modular card design that can be easily extended

## 🚀 Getting Started

1. Clone or download this repository
2. Open `index.html` in your web browser
3. No build process or dependencies required - pure HTML and CSS!

## 📁 Project Structure

```
Assignment_Two/
├── index.html      # Main HTML structure
├── styles.css      # All styling and responsive design
└── README.md       # Project documentation
```

## 🎨 Design Highlights

- **CSS Grid Layout**: Used for creating equal-height columns that automatically adjust
- **Flexbox**: Nested within cards to ensure proper content alignment
- **CSS Custom Properties**: Design tokens for easy theming and maintenance
- **Card Hover States**: Subtle elevation and shadow effects on interaction
- **Button Interactions**: Scale and color transitions for better UX

## 💡 Learning Objectives

This project demonstrates:

- **CSS Grid**: Multi-column responsive layouts with `grid-template-columns` and `gap`
- **Flexbox**: Flexible content alignment within card components
- **Equal Height Columns**: Using `align-items: stretch` in Grid and `flex: 1` in Flexbox
- **Card Component Design**: Reusable, modular card structure
- **Hover & Active States**: Interactive feedback with CSS transitions
- **Responsive Design**: Mobile-first approach with media queries
- **CSS Best Practices**: Custom properties, semantic naming, and organized code structure

## 📱 Responsive Breakpoints

- **Mobile**: Single column layout (< 768px)
- **Tablet**: Flexible grid with auto-fit columns (768px - 1199px)
- **Desktop**: Three-column layout (≥ 1200px)

## 🎯 Key CSS Concepts Demonstrated

1. **CSS Grid**: `display: grid`, `grid-template-columns`, `gap`, `align-items`
2. **Flexbox**: `display: flex`, `flex-direction`, `flex: 1`, `justify-content`
3. **CSS Variables**: Custom properties for theming
4. **Transitions**: Smooth animations with `transition` property
5. **Media Queries**: Responsive design with `@media` rules
6. **Pseudo-elements**: `::before` for feature checkmarks

## 🔧 Customization

The design uses CSS custom properties (variables) defined in `:root`, making it easy to customize:

- Colors: `--color-primary`, `--color-text-primary`, etc.
- Spacing: `--spacing-sm`, `--spacing-md`, `--spacing-lg`, etc.
- Typography: `--font-family`, `--font-size-*`, `--font-weight-*`
- Shadows: `--shadow-sm`, `--shadow-md`, `--shadow-lg`

Simply modify these variables in `styles.css` to change the entire theme!

## ♿ Accessibility Features

- Semantic HTML5 elements (`<article>`, `<main>`, `<header>`)
- ARIA labels for screen readers
- Keyboard navigation support
- Focus states for interactive elements
- Reduced motion support for users with motion sensitivity


