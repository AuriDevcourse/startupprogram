# Design System Documentation

## Base Layout Structure

### Container System
- Main container width: 1200px
- Auto margins for centering
- Card-based grid layout
- Content organized in sections with headline titles

## Typography

### Font Families
- Headlines and titles: 'Archivo Expanded'
- General text: 'Inter'

### Text Styling
- Gradient text effect for headlines using linear-gradient
- Font size hierarchy:
  - Headlines: 57px (line height: 68px)
  - Card titles: 18px
  - Subtitles: 11px

## Card Design

### Visual Style
- Background: Dark theme (rgba(17, 17, 17, 0.9))
- Decorative dotted pattern using radial-gradient
- Border: 1px solid rgba(242, 242, 242, 0.5)
- Border radius: 20px
- Padding: 2rem
- Minimum height: 200px

### Interactive States
- Hover effect:
  - 5px upward translation
  - Border color changes to #FF0028

## Grid System

### Layout Options
1. `.grid`: Basic responsive grid
2. `.grid-3-columns`: Three-column layout
- Gap spacing: 2rem between items
- Uses CSS Grid with auto-fit and minmax
- Responsive breakpoints for different screen sizes

## Card Components

### Image Area
- Height: 100px
- Border radius: 10px
- Semi-transparent background

### Icons
- Material Icons implementation
- Size: 3rem
- Color: White with 0.8 opacity
- Centered in card image area

## Popup System

### Structure
- Fixed position overlay
- Dark semi-transparent background
- Centered content with max-width
- Smooth transitions for opening/closing
- Scrollable content area
