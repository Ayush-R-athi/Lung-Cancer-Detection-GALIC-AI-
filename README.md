# PulmoScan 🫁

**AI-Powered Lung X-Ray Analysis Platform**

PulmoScan is an advanced medical AI web application that provides preliminary lung X-ray analysis and disease prediction. Built with modern web technologies and integrated with machine learning capabilities for healthcare assistance.

## ⚠️ Medical Disclaimer

**Important**: This AI system offers preliminary assessments only. Always consult a qualified medical professional for confirmed diagnosis and treatment. PulmoScan is not a substitute for professional medical advice.

## 🚀 Features

- **AI-Powered Analysis**: Advanced machine learning models for lung X-ray interpretation
- **Interactive UI**: Modern, responsive design with particle animations
- **Real-time Processing**: Instant analysis and results
- **Mobile Responsive**: Optimized for all device sizes
- **Secure Upload**: Safe and private image processing
- **Professional Interface**: Clean, medical-grade user experience

## 🛠️ Tech Stack

### Frontend
- **HTML5**: Semantic structure and accessibility
- **CSS3**: Custom animations, glassmorphism effects, neon styling
- **JavaScript (ES6+)**: Interactive features and particle systems
- **Particles.js**: Advanced particle animations and effects

### Backend Integration
- **Streamlit**: AI model deployment and processing
- **Machine Learning**: Trained models for medical image analysis

## 📁 Project Structure

```
PulmoScan/
├── index.html              # Main landing page
├── style.css               # Custom styling and animations
├── script.js               # JavaScript functionality
├── particles.js            # Particle animation library
├── particles.min.js        # Minified particles library
├── demo/                   # Particles.js demo and examples
│   ├── index.html
│   ├── particles.json
│   └── js/app.js
├── assets/
│   ├── author1.jpg         # Team member photos
│   ├── author2.jpeg
│   └── your-video.mp4
└── README.md
```

## 🎨 Design Features

- **Neon Green Theme**: Medical-inspired color scheme (#39ff14)
- **Glassmorphism**: Modern translucent design elements
- **Particle Effects**: Dynamic background animations
- **Smooth Animations**: Hover effects and transitions
- **Responsive Layout**: Mobile-first design approach

## 🚀 Deployment

### Prerequisites
- Web server (Apache, Nginx, or any static hosting)
- Modern web browser with JavaScript enabled

### Quick Deploy

1. **Clone/Download** the repository
2. **Upload files** to your web server
3. **Configure** the Streamlit backend URL in `index.html` (line 21)
4. **Test** all functionality before going live

### Hosting Options
- **GitHub Pages**: Free static hosting
- **Netlify**: Automatic deployments with CI/CD
- **Vercel**: Fast global CDN deployment
- **AWS S3**: Scalable cloud hosting
- **Traditional Web Hosting**: Any provider supporting static files

### Environment Setup

```bash
# No build process required - pure HTML/CSS/JS
# Simply serve the files from any web server
```

## 🔧 Configuration

### AI Backend Integration
Update the Streamlit app URL in `index.html`:
```javascript
onclick="window.location.href='YOUR_STREAMLIT_APP_URL'"
```

### Particle Effects
Customize particle settings in `demo/particles.json`:
```json
{
  "particles": {
    "number": { "value": 80 },
    "color": { "value": "#ffffff" },
    "shape": { "type": "circle" }
  }
}
```

## 📱 Browser Support

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 🎯 Usage

1. **Visit** the deployed website
2. **Click** "Get Started" to access the AI analysis tool
3. **Upload** a lung X-ray image
4. **Review** the AI-generated preliminary assessment
5. **Consult** with a medical professional for confirmation

## 👥 Team

### Ayush Rathi
*Full-Stack Developer & AI Specialist*
- Expertise in artificial intelligence and system architecture
- Focused on scalable, high-performance digital platforms

### Krishna PB
*Computer Science & Technology Leadership*
- Specializes in efficient systems and tech innovation
- Expert in software engineering and AI research

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## 🔗 Links

- **Live Demo**: [pulmoscan.netlify.app/]


## 📞 Support

For technical support or medical questions:
- **Technical Issues**: Use the contact form on the website
- **Medical Queries**: Consult qualified healthcare professionals
- **Feature Requests**: Open an issue in the repository

## 🔒 Privacy & Security

- No personal data stored locally
- Secure image processing
- HIPAA-compliant considerations
- Privacy-first design approach

---

**Made with ❤️ for better healthcare accessibility**

*PulmoScan - Advancing medical AI for everyone*
