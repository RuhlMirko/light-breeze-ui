# Light Breeze UI

A minimal CSS template inspired by early 2000s Frutiger Aero aesthetics. Copy the CSS file into any project for glossy, translucent, glass-effect components.

## Features

- **Pure CSS** - No JavaScript dependencies
- **Glass effects** - Backdrop blur and translucent overlays
- **Responsive** - Mobile-friendly design
- **Customizable** - CSS variables for easy theming

## Components

- Buttons (Primary, Secondary, Ghost)
- Cards with glass effect
- Form inputs
- Badges
- Alerts

## Usage

1. Copy `src/styles/global.css` into your project
2. Add the stylesheet to your HTML:
   ```html
   <link rel="stylesheet" href="global.css">
   ```
3. Use the classes:
   ```html
   <button class="lb-button lb-button-primary">Click me</button>
   ```

## Development

```bash
# Install dependencies
pnpm install

# Start dev server
pnpm dev

# Build for production
pnpm build
```

## License

ISC
