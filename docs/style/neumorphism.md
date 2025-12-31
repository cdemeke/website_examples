# Neumorphism

## Overview

Neumorphism (or soft UI) creates interface elements that appear to extrude from or press into the background. Using subtle shadows and highlights, it creates a soft, tactile 3D effect while maintaining a minimalist aesthetic.

## Key Characteristics

- **Soft, extruded elements** that appear raised or pressed
- **Matching background colors** - elements blend with surface
- **Dual shadows** - light and dark for 3D effect
- **Subtle color palette** with low contrast
- **Rounded corners** for a soft feel
- **Minimal color variation** - monochromatic schemes

## Prompts

### Neumorphic Dashboard
```
Create a dashboard using neumorphism design. Use a soft
gray background (#e0e0e0) with cards that appear to
float above it using dual box-shadows. Include raised
buttons, pressed input fields, and soft circular icons.
Keep the entire interface in a monochromatic gray palette
with one subtle accent color.
```

### Soft UI Calculator
```
Design a calculator app with neumorphism styling. Create
raised number buttons that appear to press inward on click.
Use a light gray base with darker shadows on bottom-right
and lighter shadows on top-left. The display should appear
inset into the surface.
```

### Neumorphic Music Player
```
Build a music player interface using soft UI principles.
Include a raised album art container, inset progress bar,
extruded control buttons, and a soft volume slider. Use
pastel colors with the same shadow technique throughout.
```

## Color Palettes

### Classic Neumorphism
- Background: `#E0E0E0`
- Light Shadow: `#FFFFFF`
- Dark Shadow: `#BEBEBE`
- Accent: `#6D5DFC`

### Warm Neumorphism
- Background: `#EFE5D5`
- Light Shadow: `#FFFFFF`
- Dark Shadow: `#D1C4B2`
- Accent: `#E07A5F`

### Dark Neumorphism
- Background: `#2D2D2D`
- Light Shadow: `#3D3D3D`
- Dark Shadow: `#1D1D1D`
- Accent: `#00D9FF`

## CSS Essentials

```css
/* Raised element */
.neu-raised {
  background: #e0e0e0;
  border-radius: 20px;
  box-shadow: 8px 8px 16px #bebebe,
              -8px -8px 16px #ffffff;
}

/* Pressed/inset element */
.neu-pressed {
  background: #e0e0e0;
  border-radius: 20px;
  box-shadow: inset 8px 8px 16px #bebebe,
              inset -8px -8px 16px #ffffff;
}
```

## Accessibility Note

Neumorphism has low contrast which can cause accessibility issues. Consider:
- Adding subtle borders for definition
- Using color accents for interactive states
- Ensuring text has sufficient contrast

## Best For

- Music and media players
- Calculator and utility apps
- Smart home interfaces
- Fitness and health apps
- Settings pages
- Personal dashboards
