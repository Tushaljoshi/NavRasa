# NavRasa IT Solutions Frontend

This is the frontend codebase for NavRasa IT Solutions website.

## Project Structure

```
frontend/
├── css/
│   └── Styles.css          # Main stylesheet
├── js/
│   └── script.js           # Main JavaScript file
├── images/                 # Image assets
├── index.html             # Homepage
├── about.html             # About page
├── service.html           # Services page
├── contact.html           # Contact page
└── package.json           # Project dependencies
```

## Setup Instructions

1. Install dependencies:
```bash
npm install
```

2. Start the development server:
```bash
npm start
```
   This will start the server at http://localhost:3000

## Available Scripts

- `npm start` - Start development server
- `npm run build` - Build for production (minifies CSS and JS)

## Features

- Responsive design
- Modern UI/UX
- Form validation
- Interactive components
- Cross-browser compatibility

## Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)

## Development

### Available Scripts

- `npm start` - Start development server
- `npm run build` - Build for production
- `npm run minify-css` - Minify CSS
- `npm run minify-js` - Minify JavaScript
- `npm run generate-icons` - Generate icon assets

### Form Validation

The website includes comprehensive form validation for:
- Contact form
- Consultation form
- Quote request form

Validation includes:
- Required fields
- Email format
- Phone number format
- Name format
- Service selection

### Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Production Build

To create a production build:

```bash
npm run build
```

This will:
1. Generate optimized icons
2. Minify CSS
3. Minify JavaScript

## Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is proprietary and confidential. 