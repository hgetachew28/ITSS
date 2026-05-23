# UTD Grade Page Clone

A responsive website that replicates the look and functionality of the UT Dallas grade viewing page.

## Features

- **Header Section**: Dark green header with "My Academics" title
- **Semester Information**: Displays current semester and allows changing semester
- **Sidebar Navigation**: Menu with various academic options
- **GPA Statistics**: Shows Term GPA, Cumulative GPA, and Academic Standing
- **Grades Table**: Displays current courses with details like units, grades, and grade points
- **Responsive Design**: Works on desktop and mobile devices

## Files

- `index.html` - Main HTML structure
- `styles.css` - Styling and responsive layout
- `script.js` - Interactive functionality and JavaScript utilities

## How to Use

1. Open `index.html` in your web browser
2. Click on navigation items to see the sidebar interactions
3. Click on rows to see additional details
4. Use the "Change" button to modify semester (demo functionality)

## Customization

### Adding a New Course

Use the `addGradeEntry()` function in the browser console:

```javascript
addGradeEntry('COURSE 1234', '3.00', 'Graded - Undergraduate Courses', 'A', '12.000', 'A');
```

### Updating GPA Values

Use the `updateGPA()` function:

```javascript
updateGPA('3.5', '3.4', 'Good Standing');
```

## Styling

The color scheme matches the UTD system:
- Header: `#2d5f3f` (Dark Green)
- Active Sidebar: `#9b4c3f` (Brown)
- Background: Light grays and whites

## Browser Support

- Chrome/Chromium
- Firefox
- Safari
- Edge
- Mobile browsers

## Features Included

✅ Responsive layout
✅ Interactive sidebar navigation
✅ Clickable table rows
✅ GPA statistics display
✅ Smooth hover effects
✅ Mobile-friendly design
✅ Accessible HTML structure

## Future Enhancements

- Add actual backend integration for real grade data
- Implement semester switching functionality
- Add grade history visualization charts
- Export grades to PDF
- Dark mode toggle
