# 🌐 Popular Websites & Services Directory

A comprehensive, professional, **child-safe** directory website featuring links to popular websites, services, and platforms including Google services, social media, AI platforms, gaming, video streaming, and more. All links are verified official sources with minimal malware/virus risk.

![Website Preview](https://img.shields.io/badge/Status-Live-brightgreen) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## ✨ Features

- **🛡️ Child-Safe**: All websites are official, verified sources with minimal malware/virus risk
- **300+ Websites Listed**: Comprehensive collection of popular services and platforms
- **20+ Categories**: Organized into logical sections for easy navigation
- **Modern Design**: Professional UI with gradient backgrounds and smooth animations
- **Search Functionality**: Real-time search to filter through all services
- **Responsive Layout**: Works seamlessly on desktop, tablet, and mobile devices
- **Dark Mode Support**: Favicon adapts to browser dark/light mode preferences
- **Color-Coded Categories**: Each category has its own distinct colored header bar
- **Family-Friendly**: Curated content suitable for all ages

## 📂 Project Structure

```
PopSite/
├── index.html          # Main website file
├── favicon.svg         # Site icon (GS logo)
└── README.md          # This file
```

## 🎯 Categories Included

### Google Services
- Core Google Services
- Developer & Enterprise Tools
- Advertising & Marketing
- Communication & Social
- AI & Machine Learning
- Hardware & Devices
- Education & Research
- Security & Privacy
- Shopping & Commerce
- Other Google Services

### Popular Websites
- **Popular AI Platforms** - ChatGPT, Claude, Midjourney, DALL-E, and more
- **Popular Social Media** - TikTok, Instagram, Facebook, Twitter/X, Reddit, etc.
- **Popular Video Platforms** - YouTube, Netflix, Hulu, Disney+, etc.
- **Popular Gaming & Communication** - Discord, Roblox, Minecraft, Steam, etc.
- **Popular Communication Tools** - WhatsApp, Telegram, Signal, Zoom, etc.
- **Popular Entertainment** - Spotify, Apple Music, Twitch, etc.
- **Popular News & Media** - CNN, BBC, New York Times, etc.
- **Popular Shopping** - Amazon, eBay, AliExpress, etc.
- **Other Popular Sites** - Wikipedia, GitHub, Stack Overflow, etc.

## 🚀 Getting Started

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/popsite.git
   cd popsite
   ```

2. **Open the website**
   - Simply open `index.html` in your web browser
   - Or use a local server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (http-server)
     npx http-server
     ```

3. **View the site**
   - Open `http://localhost:8000` in your browser

## 🌐 Deployment

### Option 1: GitHub Pages (Recommended)

1. Push your code to a GitHub repository
2. Go to repository Settings → Pages
3. Select source branch (usually `main` or `master`)
4. Select `/ (root)` folder
5. Your site will be live at `https://yourusername.github.io/repository-name`

### Option 2: Netlify

1. Visit [Netlify Drop](https://app.netlify.com/drop)
2. Drag and drop your project folder
3. Get instant deployment with a free URL

### Option 3: Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project directory
3. Follow the prompts to deploy

### Option 4: Cloudflare Pages

1. Visit [Cloudflare Pages](https://pages.cloudflare.com)
2. Connect your GitHub repository or upload files
3. Deploy with one click

## 🎨 Customization

### Changing Colors

Edit the CSS gradient colors in `index.html`:
- Background gradient: `.body` selector
- Category headers: `.category[data-category="..."]` selectors
- Service items: `.service-item` border colors

### Adding New Categories

1. Copy an existing category structure
2. Update the `data-category` attribute
3. Add corresponding CSS styling for the header color
4. Add your service links in the list

### Modifying the Favicon

Edit `favicon.svg` to change the icon. The current icon displays "GS" in blue (adapts to dark/light mode).

## 🔍 Search Functionality

The website includes built-in search that filters services in real-time across all categories. Simply type in the search box at the top of the page.

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## 🤝 Contributing

Contributions are welcome! If you'd like to add more websites or improve the design:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- All website logos and trademarks belong to their respective owners
- This is a directory/aggregation site linking to external services

## 📧 Contact

For questions or suggestions, please open an issue on GitHub.

---

**Made with ❤️ for easy access to popular websites and services**

