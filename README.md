# Praveen Balu Photography Portfolio

A modern, responsive photography portfolio website showcasing the work of Praveen Balu, a professional photographer and cinematographer. The site features work from Yorker Films and Lime Light Creations.

## 🚀 Features

- **Responsive Design**: Optimized for all device sizes
- **Modern UI**: Built with Tailwind CSS for a clean, professional look
- **Fast Loading**: Optimized images and lightweight code
- **SEO Optimized**: Meta tags and structured data for better search visibility
- **Dark Theme**: Elegant dark mode interface

## 📋 Prerequisites

Before you begin, ensure you have the following installed:
- [Git](https://git-scm.com/)
- [Node.js](https://nodejs.org/) (version 14 or higher)
- [npm](https://www.npmjs.com/) (comes with Node.js)
- [Live Server extension](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) for VS Code

## 🛠️ Installation & Setup

Follow these steps to get the project running locally:

### 1. Clone the Repository
```bash
git clone https://github.com/fingers10/praveenbalu.git
cd praveenbalu
```

### 2. Navigate to Source Directory
```bash
cd src
```

### 3. Install Dependencies
```bash
npm install
```
or if you prefer to update existing packages:
```bash
npm update
```

### 4. Build Tailwind CSS
Run the Tailwind CSS compiler to generate the styles:
```bash
npm run dev
```

This command will:
- Take `style.css` as input
- Generate `app.css` as output with all Tailwind styles
- Watch for changes and automatically rebuild when you modify files

**Alternative**: You can also run the full command directly:
```bash
npx @tailwindcss/cli -i style.css -o app.css --watch
```

### 5. Start Development Server
1. Open the project in VS Code
2. Navigate to `src/index.html`
3. Right-click on the file and select "Open with Live Server"
4. Your portfolio will open in the browser at `http://127.0.0.1:5500/src/`

## 📁 Project Structure

```
praveenbalu/
├── LICENSE
├── README.md
└── src/
    ├── app.css              # Generated Tailwind CSS (don't edit manually)
    ├── data.json           # Portfolio data
    ├── index.html          # Main HTML file
    ├── package.json        # Node.js dependencies
    ├── style.css           # Source Tailwind CSS
    ├── tailwind.config.js  # Tailwind configuration
    └── images/             # Image assets
        ├── favicon.jpg
        ├── lime-light-logo.png
        ├── praveen-balu.jpeg
        ├── praveen-photography-logo.jpg
        └── yorker-films-logo.jpg
```

## 🎨 Development Workflow

1. **Start development**: Run `npm run dev` to start Tailwind CSS watching for changes
2. **Edit source files**: Make changes to `style.css`, `index.html`, or other source files
3. **Auto-reload**: Live Server will automatically refresh the browser when files change
4. **Build CSS**: Tailwind will automatically rebuild `app.css` when you save changes

## 📦 Available Scripts

- `npm run dev` - Start Tailwind CSS in watch mode for development
- `npm run build` - Build Tailwind CSS for production (minified)

## 🔧 Customization

- **Styles**: Edit `style.css` to add custom Tailwind directives
- **Content**: Update `data.json` to modify portfolio content
- **Layout**: Modify `index.html` to change the page structure
- **Tailwind Config**: Adjust `tailwind.config.js` for custom design tokens

## 📱 Browser Compatibility

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## 🚀 Deployment

For production deployment:

1. Run the production build command:
   ```bash
   npm run build
   ```

2. Upload the `src/` folder contents to your web server

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📧 Contact

Praveen Balu - Professional Photographer & Cinematographer

- Website: [https://www.praveenbalu.com](https://www.praveenbalu.com)
- Portfolio includes work from:
  - **Yorker Films**
  - **Lime Light Creations**

## 📄 License

This project is licensed under the terms found in the [LICENSE](LICENSE) file.

---

⭐ **Star this repository if you found it helpful!**