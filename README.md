# AEGIS Project Website

This is the official project website for **AEGIS: Automated Error Generation and Identification for Multi-Agent Systems**.

## 🎯 About

AEGIS is a novel framework that automatically generates large-scale datasets of realistic Multi-Agent System failures with verifiable ground-truth labels. This website showcases our research findings, methodology, and comprehensive experimental results.

## 🚀 Features

- **Modern, responsive design** optimized for all devices
- **Interactive animations** and smooth scrolling effects
- **Comprehensive results table** with all AEGIS-Bench performance metrics
- **Visual framework overview** with methodology diagrams
- **Direct links** to paper, code, dataset, and models
- **Complete author information** with affiliations

## 📁 Project Structure

```
AEGIS_website/
├── index.html              # Main website file
├── assets/
│   └── images/
│       ├── main.png        # Framework overview diagram
│       ├── radar.pdf       # Performance radar chart
│       └── aegis.png       # AEGIS logo
└── README.md               # This file
```

## 🛠️ Setup Instructions

### Local Development

1. **Clone or download** this repository
2. **Open** `index.html` in any modern web browser
3. **No build process required** - it's a static website

### GitHub Pages Deployment

1. **Push** this folder to a GitHub repository
2. **Enable GitHub Pages** in repository settings
3. **Select source** as `main` branch and root folder
4. **Access** your site at `https://yourusername.github.io/repositoryname`

### Custom Domain (Optional)

To use a custom domain:
1. Add a `CNAME` file with your domain name
2. Configure DNS settings to point to GitHub Pages
3. Enable custom domain in repository settings

## 🔧 Customization

### Update Links

Replace placeholder links in `index.html`:
- **Paper**: Line ~507 - Add your arXiv URL
- **Code**: Line ~512 - Add your GitHub repository URL  
- **Dataset**: Line ~517 - Add your dataset download link
- **Models**: Line ~694 - Add Hugging Face model links

### Add Images

- **Main diagram**: Replace `assets/images/main.png`
- **Radar chart**: Replace `assets/images/radar.pdf` (or convert to PNG)
- **Logo**: Replace `assets/images/aegis.png`

### Modify Content

Key sections to customize:
- **Abstract**: Lines 526-533
- **Method description**: Lines 540-541
- **Performance highlights**: Lines 557-574
- **Contact information**: Footer section

## 🎨 Design Features

- **CSS Variables** for easy color customization
- **Smooth animations** with scroll reveal effects
- **Glassmorphism** header with backdrop blur
- **Gradient backgrounds** and modern shadows
- **Responsive tables** with horizontal scrolling on mobile
- **Interactive hover effects** throughout

## 📱 Browser Support

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+

## 📊 Performance Metrics

The website includes a comprehensive results table showcasing:
- **26 different models** tested on AEGIS-Bench
- **Multiple evaluation metrics** (Pair, Agent, Error levels)
- **Clear highlighting** of best-performing methods
- **Organized categories** (Small, Medium, Large-scale models)

## 🤝 Contributing

To contribute improvements:
1. Fork this repository
2. Make your changes
3. Test across different browsers
4. Submit a pull request

## 📄 License

This project website is open source. Please credit the AEGIS team when using or adapting this template.

## 📧 Contact

For questions about the website:
- **Technical issues**: Open a GitHub issue
- **Research questions**: Contact the authors at the emails provided in the paper

---

**Built with ❤️ by the AEGIS Team**