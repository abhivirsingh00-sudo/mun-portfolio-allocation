# MUN Portfolio Allocation System

**Live Demo:** https://abhivirsingh00-sudo.github.io/mun-portfolio-allocation/

A web-based application for automatically allocating Model United Nations (MUN) portfolios to delegates as they are added.

## Features

- 🎯 **Automatic Portfolio Assignment**: When you add a delegate name, they are automatically assigned a unique portfolio
- 📋 **12 Different Portfolios**: Including Secretary-General, Security Council members, and various ambassadors
- 📊 **Committee Grouping**: View delegates organized by their assigned committees
- 💾 **Persistent Storage**: Allocations are saved to browser localStorage
- 📱 **Responsive Design**: Works seamlessly on desktop and mobile devices
- 🎨 **Visual Feedback**: Color-coded portfolios and smooth animations
- ⚙️ **Customizable**: Add, edit, delete, and import/export portfolios

## Quick Start

1. **Open the app:** Visit https://abhivirsingh00-sudo.github.io/mun-portfolio-allocation/
2. **Add delegates:** Type a name and click "Add Delegate"
3. **Customize:** Click the ⚙️ Settings button to manage portfolios

## Portfolios Included

### General Assembly
- Secretary-General
- President of General Assembly
- Ambassador - United States
- Ambassador - Germany
- Ambassador - India
- Ambassador - Brazil
- Ambassador - Japan

### Security Council
- Security Council Chair
- Ambassador - China
- Ambassador - Russia
- Ambassador - United Kingdom
- Ambassador - France

## How to Use

1. **Open the Application**: https://abhivirsingh00-sudo.github.io/mun-portfolio-allocation/
2. **Add a Delegate**: 
   - Type a delegate name in the input field
   - Click "Add Delegate" or press Enter
3. **View Allocations**: 
   - See the delegate card with their assigned portfolio
   - Check the portfolio summary below to see all delegates by committee
4. **Customize Portfolios**:
   - Click ⚙️ Settings button
   - Add new portfolios
   - Edit existing ones
   - Delete portfolios you don't need
5. **Import/Export**:
   - Export your configuration as JSON
   - Import saved configurations
   - Restore default portfolios anytime
6. **Remove a Delegate**: Click the "Remove" button on any delegate card
7. **Data Persistence**: Your allocations are automatically saved to your browser

## Portfolio Allocation Logic

Portfolios are assigned in a rotating sequence based on when delegates are added:
- 1st delegate → Portfolio 1
- 2nd delegate → Portfolio 2
- 3rd delegate → Portfolio 3
- And so on, cycling through all available portfolios

This ensures fair and balanced distribution across all available positions.

## Technical Stack

- **HTML5**: Structure and markup
- **CSS3**: Styling with gradients and animations
- **Vanilla JavaScript**: No dependencies required
- **localStorage API**: Client-side data persistence

## Files

- `index.html` - Main HTML structure
- `styles.css` - All styling and responsive design
- `script.js` - Main application logic and customization
- `portfolioData.js` - Portfolio definitions and allocation functions
- `README.md` - This file

## Features You Can Customize

- Add more portfolios directly in the app
- Edit names, committees, descriptions, and colors
- Delete portfolios you don't need
- Modify colors and styling in `styles.css`
- Update portfolio descriptions
- Export and import your configurations

## Browser Compatibility

Works on all modern browsers that support:
- ES6 JavaScript
- localStorage API
- CSS Grid and Flexbox

## Future Enhancements

- Preset portfolio configurations for different MUN conferences
- Role description tooltips
- Random allocation option
- Team/country assignment pairing
- Database integration for multi-device sync

---

Built for Model United Nations conferences to streamline delegate portfolio allocation.

**Questions or Issues?** Open an issue on the [GitHub repository](https://github.com/abhivirsingh00-sudo/mun-portfolio-allocation/issues)
