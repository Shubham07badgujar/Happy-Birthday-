# 🎉 Happy Birthday Interactive Website

A beautiful, animated birthday website with personalized messages, background music, and interactive elements. This project creates an engaging birthday experience with smooth animations and a heartfelt personal touch.

## ✨ Features

- **Interactive Welcome Prompt**: Music permission dialog using SweetAlert2
- **Smooth Animations**: Powered by GSAP (GreenSock Animation Platform)
- **Background Music**: Auto-playing birthday music (`duniya.opus`)
- **Personalized Messages**: Custom birthday messages in multiple languages
- **Photo Gallery**: Interactive profile pictures with hover effects
- **Animated Elements**: 
  - Floating balloons
  - Rotating birthday hats
  - Pulsing animations
  - Text reveals with typewriter effects
- **Responsive Design**: Mobile-friendly layout
- **Particle Effects**: Colorful SVG circles with explosion animations

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with animations and responsive design
- **JavaScript (ES6+)**: Interactive functionality
- **GSAP (GreenSock)**: Professional animation library
- **SweetAlert2**: Beautiful alert dialogs
- **Google Fonts**: Poppins font family
- **SVG**: Scalable vector graphics for balloons and effects

## 📁 Project Structure

```
Happy-Birthday/
├── index.html          # Main HTML file
├── style/
│   └── main.css        # Stylesheet with animations
├── script/
│   └── main.js         # JavaScript animations and interactions
├── img/
│   ├── bg.jpg          # Background image
│   ├── favicon.png     # Site favicon
│   ├── hat.svg         # Birthday hat SVG
│   ├── ballon1.svg     # Balloon graphics
│   ├── ballon2.svg
│   ├── ballon3.svg
│   └── [profile-pics]  # Personal photos (sej1.jpg - sej8.jpg, ss.jpg)
├── music/
│   └── duniya.opus     # Background music file
├── README.md           # This file
└── LICENSE             # Project license
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (optional, for better audio support)

### Installation

1. **Clone or download the repository**
   ```bash
   git clone <repository-url>
   cd Happy-Birthday
   ```

2. **Replace personal content**
   - Update photos in the `img/` folder
   - Modify messages in `index.html`
   - Replace the music file in `music/` folder

3. **Run the website**
   - Open `index.html` directly in a browser, or
   - Use a local server for better audio support:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (with live-server)
     npx live-server
     ```

4. **Access the website**
   - Direct: Open `index.html` in your browser
   - Server: Navigate to `http://localhost:8000`

## 🎨 Customization

### Personalizing the Content

1. **Update the title and name**
   ```html
   <title>Happy Birthday [Name]!!! :)</title>
   <span id="name">[Your Message] ❤️🫂</span>
   ```

2. **Modify messages**
   - Edit text in `.three`, `.four`, `.five`, and `.nine` sections
   - Update the birthday wish in `.wish-hbd`

3. **Replace images**
   - Add your photos to the `img/` folder
   - Update image paths in `index.html`
   - Maintain the naming convention or update references

4. **Change music**
   - Replace `duniya.opus` with your preferred audio file
   - Update the source path in the HTML audio element

### Styling Customizations

- **Colors**: Modify CSS custom properties and color values
- **Fonts**: Change the Google Fonts import and font-family declarations
- **Animations**: Adjust GSAP timeline parameters in `main.js`
- **Layout**: Modify CSS grid and flexbox properties

## 🎭 Animation Timeline

The website follows a carefully choreographed animation sequence:

1. **Welcome screen** with name reveal
2. **Intro message** fade-in/fade-out
3. **Chat-style message** with typing effect
4. **Idea sequence** with multiple animated text reveals
5. **Photo gallery** with staggered image animations
6. **Balloon release** with floating effects
7. **Final message** with celebratory elements

## 📱 Responsive Design

The website is optimized for various screen sizes:

- **Desktop**: Full animation experience
- **Tablet**: Adapted layouts and sizing
- **Mobile**: Optimized touch interactions and scaled elements

## 🎵 Audio Features

- **Background music**: Loops automatically when permitted
- **User control**: Permission-based audio playback
- **Format support**: OPUS audio format for quality and compression

## 🌟 Browser Compatibility

- ✅ Chrome (Recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ⚠️ IE11 (Limited support)

## 🤝 Contributing

This is a personal birthday project template. Feel free to:

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Submit a pull request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **GSAP**: For powerful animation capabilities
- **SweetAlert2**: For beautiful alert dialogs
- **Google Fonts**: For typography
- **SVG graphics**: For scalable balloon illustrations

## 📧 Contact

For questions, suggestions, or customization requests, please open an issue in the repository.

---

Made with ❤️ for special birthdays! 🎂✨
