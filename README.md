# Meridian Property Management LLC

https://meridian-property.com

## Development

```bash
# Install dependencies
npm install

# Start development server with hot reloading
npm run dev

# Build for production
npm run build
```

## Build System

- **Tailwind CSS v4** with CLI for styling
- **Browser-sync** for development server
- **Nodemon** for HTML file watching
- Source files in `src/`, built files in `dist/`

## Deployment

Configured for Netlify deployment with form handling via the `netlify` form attribute.

## Scripts

- `npm run build:css` - Compile and minify Tailwind CSS
- `npm run build:html` - Copy HTML files to dist
- `npm run build` - Full production build
- `npm run dev` - Development mode with hot reloading
