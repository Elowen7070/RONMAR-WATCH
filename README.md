# Luxe Time - Premium Watch Store

A professional e-commerce website for luxury watches, built with HTML, CSS, and JavaScript.

## Features

- 📱 **Responsive Design** - Works perfectly on mobile, tablet, and desktop
- 🛍️ **Complete E-commerce Features**
  - Product catalog with categories
  - Product detail pages with image galleries
  - Shopping cart functionality
  - User account system
- 🤖 **AI Product Recommendations** - Personalized suggestions based on browsing history
- 💎 **Premium UI/UX** - Modern design with smooth animations and transitions
- 🎨 **Customizable** - Easy to brand and customize with your products

## Getting Started

### Prerequisites

- Node.js and npm installed
- Git installed
- Vercel account (for deployment)

### Installation

1. Clone the repository
```bash
git clone <repository-url>
cd watchstore
```

2. Install dependencies
```bash
npm install
```

3. Start development server
```bash
npm run dev
```

The site will be available at `http://localhost:3000`

## Deployment

### Option 1: Vercel (Recommended)

1. Install Vercel CLI
```bash
npm install -g vercel
```

2. Login to Vercel
```bash
vercel login
```

3. Deploy the project
```bash
vercel deploy
```

### Option 2: Netlify

1. Go to [Netlify](https://app.netlify.com) and login
2. Click "New site from Git"
3. Connect your Git repository
4. Set build command to `npm run build`
5. Set publish directory to `.`
6. Click "Deploy site"

### Option 3: GitHub Pages

1. Create a GitHub repository
2. Push your code to GitHub
3. Go to repository settings
4. Scroll down to "GitHub Pages"
5. Select branch and folder
6. Click "Save"

## Customization

### Adding Products

Edit the `products` array in the JavaScript section of `index.html` to add your own products.

### Branding

- Replace the logo image in the header
- Update the color scheme in the Tailwind config
- Modify the text content throughout the site

## File Structure

```
watchstore/
├── index.html          # Main HTML file
├── package.json        # Project configuration
├── vercel.json         # Vercel deployment config
├── .gitignore          # Git ignore file
└── README.md           # This file
```

## Technologies Used

- HTML5
- CSS3 with Tailwind CSS v3
- JavaScript (ES6+)
- Font Awesome icons
- AOS animations
- GSAP animations

## License

MIT License - feel free to use this project for personal or commercial purposes.

## Support

For any questions or issues, please contact [your email] or open an issue on GitHub.