# Inventronics Website with Chatbot Integration

A modern, responsive website for Inventronics featuring an integrated AI chatbot for customer support and FAQ handling.

## Features

- **Modern Design**
  - Responsive layout that works on all devices
  - Dynamic hero section with stadium background
  - Clean and professional navigation
  - Consistent branding with Inventronics orange theme

- **Interactive Chatbot**
  - AI-powered FAQ bot using Dialogflow
  - Custom styled interface matching website theme
  - Refresh functionality for chat reset
  - Persistent across page navigation
  - Mobile-friendly design

## Technology Stack

- HTML5
- CSS3 (with modern features like flexbox and gradients)
- JavaScript (ES6+)
- Dialogflow for chatbot functionality
- Google's df-messenger web component

## Setup and Installation

1. **Clone the Repository**
   ```bash
   git clone [repository-url]
   cd inventronics
   ```

2. **Local Development**
   - Simply open `index.html` in a web browser
   - No build process required
   - Live server recommended for development

3. **Deployment**
   - Deploy to any static hosting service (Netlify, GitHub Pages, etc.)
   - Ensure `index.html` is at the root level
   - Set up proper redirects if needed

## Chatbot Configuration

The chatbot uses the following configuration:
```javascript
project-id: "scrapi-development"
agent-id: "51367431-54a6-47cd-a5df-f89870317c83"
language-code: "en"
```

### Chatbot Features
- Custom styled interface
- Refresh button for conversation reset
- Responsive design
- Persistent session handling

## File Structure

```
inventronics/
├── index.html          # Main HTML file
├── .gitignore         # Git ignore file
└── README.md          # Project documentation
```

## Customization

### Styling
- All styles are contained within the `<style>` tag in `index.html`
- Main brand color: `#FF6B00`
- Gradient variations: `linear-gradient(135deg, #FF6B00, #ff8533)`

### Chatbot Customization
- Modify the chat title in the df-messenger tag
- Adjust styling variables in the CSS
- Customize refresh button behavior in the JavaScript section

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS/Android)

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request
