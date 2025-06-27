# NEET Prep 2025 - Netlify Deployment Package

This package contains all the files needed to deploy your NEET preparation app on Netlify.

## Files Included:
- `/client` - Complete React application source code
- `/public` - Static assets (favicon, manifest, service worker)
- `netlify.toml` - Netlify deployment configuration
- `package.json` - Dependencies and build configuration
- `_redirects` - URL routing configuration for single-page app
- Configuration files (Vite, Tailwind, TypeScript, etc.)

## Deployment Instructions:

### Option 1: Drag and Drop (Recommended)
1. Create a ZIP file from this entire `netlify-deploy` folder
2. Go to https://app.netlify.com/
3. Drag and drop the ZIP file onto the deployment area
4. Netlify will automatically build and deploy your app

### Option 2: Git Integration
1. Push this code to a GitHub repository
2. Connect the repository to Netlify
3. Set build command: `npm run build`
4. Set publish directory: `dist`

## Environment Variables:
Make sure to add these in your Netlify dashboard under Site Settings > Environment Variables:
- `VITE_FIREBASE_API_KEY`
- `VITE_FIREBASE_PROJECT_ID` 
- `VITE_FIREBASE_APP_ID`

## Features Included:
- Complete NEET preparation platform
- Firebase authentication
- Mock tests and practice sessions
- Analytics dashboard
- Responsive design
- Progressive Web App capabilities