# Language Switcher Setup for Intel Computer Website

## Overview
The Intel Computer website now supports both Nepali (नेपाली) and English languages with a user-friendly language switcher. Nepali is set as the default language.

## Features
- **Dual Language Support**: Full website content in both Nepali and English
- **Language Switcher**: Easy-to-use dropdown in the header
- **Persistent Preference**: Remembers user's language choice using localStorage
- **Responsive Design**: Works on all device sizes
- **Automatic Translation**: All text content switches instantly between languages

## File Structure
```
languages/
├── nepali.js          # Nepali language content
├── english.js         # English language content
└── language-switcher.js # Language switching functionality

HTML Files:
├── index.html         # Homepage
├── services.html      # Services page
└── contact.html       # Contact page

CSS:
└── styles.css         # Language switcher styles
```

## How It Works

### 1. Language Files
- **`nepali.js`**: Contains all Nepali text content
- **`english.js`**: Contains all English text content
- Both files export language objects with key-value pairs

### 2. Language Switcher
- **`language-switcher.js`**: Main functionality for switching languages
- Automatically loads language files
- Creates language switcher UI in header
- Handles language switching and content updates

### 3. Integration
- Language switcher script is included in all HTML pages
- Automatically initializes when page loads
- Saves user preference in browser localStorage

## Usage

### For Users
1. **Language Switcher Location**: Located in the header next to the logo
2. **Current Language Display**: Shows "ने" for Nepali or "EN" for English
3. **Switching Languages**: Click the language switcher to open dropdown
4. **Language Options**: 
   - नेपाली (Nepali)
   - English
5. **Automatic Save**: Language preference is automatically saved

### For Developers

#### Adding New Content
To add new text content that supports both languages:

1. **Add to Language Files**:
```javascript
// In nepali.js
"new_key": "नयाँ नेपाली पाठ"

// In english.js  
"new_key": "New English Text"
```

2. **Add to HTML with data attribute**:
```html
<span data-lang="new_key">Default Text</span>
```

3. **Or update via JavaScript**:
```javascript
// In language-switcher.js updatePageContent method
this.updateElement('.new-element', languageData.new_key);
```

#### Customizing Language Switcher
- **Position**: Modify CSS in `styles.css` under `.language-switcher`
- **Styling**: Update colors, fonts, and layout in CSS
- **Languages**: Add more languages by creating new language files

## Technical Details

### Language Detection
- Default: Nepali (नेपाली)
- User preference stored in `localStorage.intel_computer_language`
- Automatically loads saved preference on page visit

### Content Updates
- **Dynamic Content**: All text content updates instantly
- **Form Elements**: Placeholders and labels switch languages
- **Navigation**: Menu items and links update
- **Page-Specific**: Different content for services and contact pages

### Performance
- Language files loaded asynchronously
- Content updates happen in real-time
- No page reload required for language switching

## Browser Support
- **Modern Browsers**: Chrome, Firefox, Safari, Edge (latest versions)
- **Local Storage**: Required for saving language preference
- **JavaScript**: Must be enabled for functionality

## Troubleshooting

### Common Issues
1. **Language not switching**: Check browser console for JavaScript errors
2. **Content not updating**: Verify language files are loaded correctly
3. **Styling issues**: Check CSS file is properly linked

### Debug Mode
Open browser console to see:
- Language file loading status
- Current language setting
- Content update operations

## Future Enhancements
- **More Languages**: Easy to add additional languages
- **RTL Support**: Right-to-left language support
- **Auto-Detection**: Browser language detection
- **Translation API**: Integration with translation services

## Support
For technical support or questions about the language switcher, refer to the main project documentation or contact the development team.
