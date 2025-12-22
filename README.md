# Helium AI Investor Pitch Deck

A modern, interactive investor pitch deck for Helium AI - The AI Operating System.

## Features

- Responsive slide deck with smooth navigation
- Professional design with consistent branding
- Interactive charts and visualizations
- Mobile-friendly interface
- Built with vanilla HTML, CSS, and JavaScript

## Local Development

```bash
# Install dependencies
npm install

# Start development server
npm run dev

# Open http://localhost:3000 in your browser
```

## Vercel Deployment

### Method 1: GitHub Integration (Recommended)

1. **Push to GitHub**:
   ```bash
   git add .
   git commit -m "Deploy investor pitch deck"
   git push origin main
   ```

2. **Connect to Vercel**:
   - Go to [vercel.com](https://vercel.com)
   - Click "New Project"
   - Import your GitHub repository
   - Vercel will automatically detect the configuration and deploy

### Method 2: Vercel CLI

```bash
# Install Vercel CLI globally
npm i -g vercel

# Deploy
vercel

# For production deployment
vercel --prod
```

## Configuration

- `vercel.json`: Vercel deployment configuration
- `package.json`: Project metadata and scripts
- `investor-deck.html`: Main pitch deck file
- `styles.css`: Styling and animations
- `public/`: Static assets (logos, images)

## Project Structure

```
investor-pitch/
├── investor-deck.html      # Main pitch deck
├── styles.css             # Styles and animations
├── vercel.json           # Vercel configuration
├── package.json          # Project metadata
├── README.md             # This file
└── public/
    └── logo.svg          # Company logo
```

## Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with CSS Grid and Flexbox
- **JavaScript**: Interactive navigation and animations
- **Lucide Icons**: Beautiful, consistent iconography
- **Google Fonts**: Professional typography (Manrope)

## Browser Support

- Chrome 80+
- Firefox 75+
- Safari 13+
- Edge 80+

## License

MIT License - see LICENSE file for details.
