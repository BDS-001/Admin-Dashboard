# Dashboard Project

## Overview
A responsive dashboard UI built with CSS Grid, featuring a clean and modern design. This project demonstrates advanced CSS Grid layout techniques to create a fully functional dashboard interface.

## Features

- **Intuitive Navigation Panel**: Side navigation with categorized menu items using Bootstrap icons
- **Header with Search Functionality**: Search bar and user profile information
- **Project Cards**: Display of multiple project cards with consistent styling
- **Announcements Section**: Dedicated area for important announcements
- **Trending Users**: Section showcasing trending users with avatars

## Technologies Used

- HTML5
- CSS3 (with extensive use of Grid Layout)
- Bootstrap Icons for visual elements

## Project Structure

```
├── index.html            # Main HTML structure
├── styles.css            # CSS styling with Grid layouts
├── icons/                # Directory containing avatar icons
│   ├── trees-icon.jpeg
│   ├── orange-icon.png
│   ├── snail-icon.png
│   └── fish-icon.png
└── README.md             # Project documentation
```

## Implementation Details

### Grid Layout

The project extensively uses CSS Grid for layout at multiple levels:

- Main page structure using a 2x2 grid for sidebar, header, and content areas
- Nested grids within the sidebar for navigation grouping
- Project cards area with auto-fit responsive layout
- Info panels with flexbox/grid hybrid approach

### Color Scheme

The project uses a clean, professional color scheme with:

- Primary Blue: #1992d4
- Accent Orange: #f0b429
- Neutral Gray: #e2e8f0
- White: #ffffff

### Responsive Design

The dashboard features responsive elements:
- Project cards section using `grid-template-columns: repeat(auto-fit, 350px)`
- Flexible search bar that adjusts to available space
- Properly scaled icons and text elements

## Getting Started

1. Clone this repository
2. Open index.html in your browser
3. No build process or dependencies required

## Future Enhancements

- Add dark mode toggle
- Implement interactive functionality for project cards
- Create mobile-optimized view for smaller screens
- Add data visualization components

## Credits

- Icons from [Bootstrap Icons](https://icons.getbootstrap.com/)
- Project structure inspired by The Odin Project curriculum

## License

[MIT License](LICENSE)
