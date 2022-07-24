## Common template for Solid-based chrome extension

A simple setup for personal use

Basically it's just a plain Vite app with some additions

Detailed:

- Vite
- Solid plugin for Vite
- Typescript
- Sass
- Manifest for Chrome extension app
- CRX plugin for Vite used to compile app as chrome extension
- Chrome types (@types/chrome)

### Known issues

CRX plugin works normally with Vite 3, but it causes dependency error. You can ignore it I suppose
