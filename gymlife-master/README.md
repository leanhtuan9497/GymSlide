# GymLife - Modern Gym Website

A modern, responsive gym website built with HTML, CSS, and JavaScript. This project showcases a professional gym website with multiple pages including home, about, services, classes, team, and contact pages.

## 🚀 Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean and professional design
- **Multiple Pages**: Home, About, Services, Classes, Team, Contact, Blog, Gallery
- **Interactive Elements**: Sliders, carousels, and dynamic content
- **BMI Calculator**: Built-in fitness calculator
- **Class Timetable**: Dynamic class scheduling display

## 📁 Project Structure

```
gymlife-master/
├── index.html          # Main homepage
├── index.js            # Node.js server file
├── package.json        # Project dependencies
├── css/               # Stylesheets
├── js/                # JavaScript files
├── img/               # Images and media
├── fonts/             # Font files
└── other HTML pages   # About, Services, etc.
```

## 🛠️ Installation & Setup

### Prerequisites
- Node.js (version 14 or higher)
- npm (comes with Node.js)

### Local Development

1. **Clone the repository**
   ```bash
   git clone <your-repository-url>
   cd gymlife-master
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```
   or for development with auto-reload:
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000`

## 🌐 Deployment Options

### Option 1: GitHub Pages (Recommended for Static Sites)

1. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

2. **Enable GitHub Pages**
   - Go to your repository on GitHub
   - Navigate to Settings > Pages
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click Save

3. **Your site will be available at**: `https://yourusername.github.io/your-repo-name`

### Option 2: Vercel (Recommended for Node.js)

1. **Install Vercel CLI**
   ```bash
   npm install -g vercel
   ```

2. **Deploy**
   ```bash
   vercel
   ```

3. **Follow the prompts** and your site will be deployed automatically

### Option 3: Heroku

1. **Create a Procfile**
   ```
   web: node index.js
   ```

2. **Deploy to Heroku**
   ```bash
   heroku create your-app-name
   git push heroku main
   ```

## 📱 Available Pages

- **Home** (`/`) - Main landing page
- **About Us** (`/about-us`) - Company information
- **Services** (`/services`) - Gym services offered
- **Classes** (`/class-details`) - Available classes
- **Team** (`/team`) - Staff and trainers
- **Contact** (`/contact`) - Contact information
- **Blog** (`/blog`) - Fitness blog
- **Gallery** (`/gallery`) - Photo gallery
- **BMI Calculator** (`/bmi-calculator`) - Fitness calculator

## 🎨 Customization

### Colors
The main color scheme can be modified in `css/style.css`:
- Primary Orange: `#f36100`
- Secondary Colors: Various grays and whites

### Content
- Update images in the `img/` folder
- Modify text content in HTML files
- Adjust styling in CSS files

## 🔧 Scripts

- `npm start` - Start the production server
- `npm run dev` - Start development server with auto-reload
- `npm run build` - Build command (no build required for static site)

## 📄 License

This project is licensed under the MIT License.

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 Support

If you have any questions or need help with deployment, please open an issue on GitHub.

---

**Made with ❤️ for the fitness community** 