# Glassmorphism

## Overview

Glassmorphism creates a frosted glass effect using transparency, blur, and subtle borders. This modern aesthetic adds depth and hierarchy while maintaining a clean, ethereal appearance.

## Key Characteristics

- **Frosted glass effect** with background blur
- **Semi-transparent backgrounds** (opacity 0.1-0.4)
- **Subtle light borders** for definition
- **Vivid gradient backgrounds** behind glass elements
- **Soft shadows** for depth
- **Light, airy feel** overall

## Prompts

### Glassmorphism Dashboard
```
Create a dashboard with glassmorphism styling. Use a
vibrant purple-to-blue gradient background with floating
glass cards. Each card should have a frosted effect
(backdrop-filter: blur), 20% white background opacity,
and a 1px semi-transparent white border. Add subtle
shadows for depth.
```

### Glass UI Landing Page
```
Design a landing page using glassmorphism. Feature a
colorful abstract gradient background with floating
glass panels for content sections. Include a frosted
navigation bar, glass cards for features, and transparent
buttons with glass effects. Keep text crisp and readable.
```

### Glassmorphism Login
```
Build a login form with glassmorphism styling. Center a
frosted glass card on a vibrant gradient background.
The form should have transparent input fields with
glass-style borders, a blurred card background, and
soft glow effects on focus states.
```

## Color Palettes

### Vibrant Glass
- Background Gradient: `#667eea` to `#764ba2`
- Glass Fill: `rgba(255, 255, 255, 0.15)`
- Border: `rgba(255, 255, 255, 0.3)`
- Text: `#FFFFFF`

### Soft Glass
- Background Gradient: `#a8edea` to `#fed6e3`
- Glass Fill: `rgba(255, 255, 255, 0.25)`
- Border: `rgba(255, 255, 255, 0.4)`
- Text: `#2D3748`

### Dark Glass
- Background Gradient: `#0f0c29` to `#302b63` to `#24243e`
- Glass Fill: `rgba(255, 255, 255, 0.1)`
- Border: `rgba(255, 255, 255, 0.2)`
- Text: `#FFFFFF`

## CSS Essentials

```css
.glass-card {
  background: rgba(255, 255, 255, 0.15);
  backdrop-filter: blur(10px);
  -webkit-backdrop-filter: blur(10px);
  border: 1px solid rgba(255, 255, 255, 0.3);
  border-radius: 16px;
  box-shadow: 0 8px 32px rgba(0, 0, 0, 0.1);
}
```

## Best For

- Modern SaaS products
- Mobile app landing pages
- Fintech applications
- Music and entertainment sites
- Portfolio websites
- Login and signup pages
