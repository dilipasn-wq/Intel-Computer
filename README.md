# Computer Sales & Services Website

A modern, responsive website for "Computer Sales & Services" business located at Kadam Chowk, Janakapur, Dhanusha, Nepal.

## 🌟 Features

### Design & User Experience
- **Modern & Clean Design**: Blue and white color scheme with professional aesthetics
- **Fully Responsive**: Mobile-first design that works on all devices
- **Smooth Animations**: Subtle animations and transitions for enhanced user experience
- **Professional Typography**: Uses Inter font family for excellent readability

### Pages
1. **Homepage** (`index.html`)
   - Hero section with welcome message
   - Services overview with icons
   - "Why Choose Us?" section highlighting business benefits
   - Call-to-action sections

2. **Services Page** (`services.html`)
   - Detailed service descriptions
   - Computer Sales, Repair & Maintenance, Accessories, Networking Solutions
   - Service features and benefits

3. **Contact Page** (`contact.html`)
   - Business contact information
   - Interactive contact form with validation
   - Google Maps integration
   - Business hours and location details

### Technical Features
- **Smooth Scrolling Navigation**: Seamless page navigation
- **Form Validation**: Client-side form validation with error handling
- **Mobile Menu**: Responsive mobile navigation
- **Scroll Animations**: Elements animate as they come into view
- **Performance Optimized**: Debounced scroll events and lazy loading support

## 🚀 Getting Started

### Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (optional, for development)

### Installation
1. Clone or download the project files
2. Open `index.html` in your web browser
3. Navigate through the website using the navigation menu

### File Structure
```
Computer Sales & Services/
├── index.html          # Homepage
├── services.html       # Services page
├── contact.html        # Contact page
├── styles.css          # Main stylesheet
├── script.js           # JavaScript functionality
└── README.md           # Project documentation
```

## 🎨 Customization

### Colors
The website uses CSS custom properties for easy color customization:

```css
:root {
    --primary-color: #2563eb;      /* Main blue */
    --primary-dark: #1d4ed8;      /* Darker blue */
    --accent-color: #3b82f6;      /* Accent blue */
    --text-dark: #1e293b;         /* Dark text */
    --text-light: #64748b;        /* Light text */
    --white: #ffffff;             /* White */
    --light-gray: #f8fafc;        /* Light gray */
}
```

### Content Updates
- **Business Information**: Update contact details, address, and business hours in all HTML files
- **Services**: Modify service descriptions in `services.html`
- **Images**: Replace placeholder icons with actual business photos
- **Contact Form**: Update form fields as needed

### Google Maps Integration
To update the map location:
1. Go to [Google Maps](https://maps.google.com)
2. Search for your business location
3. Click "Share" and select "Embed a map"
4. Copy the iframe code and replace the existing one in `contact.html`

## 📱 Responsive Design

The website is built with a mobile-first approach and includes breakpoints for:
- **Mobile**: 320px - 768px
- **Tablet**: 768px - 1024px
- **Desktop**: 1024px+

## 🔧 Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📋 Form Validation

The contact form includes comprehensive validation:
- **Name**: Minimum 2 characters
- **Email**: Valid email format
- **Phone**: Optional, but validates format if provided
- **Subject**: Required selection
- **Message**: Minimum 10 characters

## 🎭 Animations

The website includes several animation types:
- **Fade In Up**: Elements slide up and fade in
- **Fade In Left/Right**: Elements slide in from sides
- **Zoom In**: Elements scale up smoothly
- **Hover Effects**: Interactive button and card animations

## 🚀 Performance Features

- **Lazy Loading**: Images load as they come into view
- **Debounced Events**: Scroll events are optimized for performance
- **CSS Transitions**: Hardware-accelerated animations
- **Minimal Dependencies**: Only Font Awesome for icons

## 🔒 Security Considerations

- Form validation is client-side only
- No sensitive data is stored
- Consider adding CSRF protection for production use
- Implement server-side validation for production forms

## 📞 Support & Contact

For technical support or customization requests:
- **Business**: Computer Sales & Services, Kadam Chowk, Janakapur, Dhanusha
- **Email**: info@computersales.com
- **Phone**: +977-XXX-XXXXXXX

## 📄 License

This project is created for Computer Sales & Services business use. All rights reserved.

## 🆕 Future Enhancements

Potential improvements for future versions:
- **Blog/News Section**: Share industry insights and updates
- **Online Booking**: Schedule repair appointments online
- **Product Catalog**: Showcase available computers and accessories
- **Customer Reviews**: Display testimonials and ratings
- **Multi-language Support**: Nepali and English versions
- **PWA Features**: Offline functionality and app-like experience

## 🛠️ Development

### Adding New Pages
1. Create new HTML file following the existing structure
2. Update navigation in all HTML files
3. Add corresponding CSS styles
4. Include any necessary JavaScript functionality

### CSS Organization
The stylesheet is organized into logical sections:
- Reset and base styles
- Typography
- Components (buttons, forms, cards)
- Layout sections
- Responsive design
- Animations

### JavaScript Features
- Modular function organization
- Event delegation for performance
- Error handling and logging
- Accessibility improvements
- Performance optimizations

---

**Built with ❤️ for Computer Sales & Services**

*Last updated: December 2024*
