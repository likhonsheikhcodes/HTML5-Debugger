# 🚀 HTML5 Game Debugger Pro

<div align="center">

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://github.com/likhonsheikhcodes/HTML5-Debugger)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://github.com/likhonsheikhcodes/HTML5-Debugger)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://github.com/likhonsheikhcodes/HTML5-Debugger)

An advanced debugging tool for HTML5 games and web applications with real-time analysis, performance monitoring, and comprehensive debugging capabilities.

[Live Demo](https://html-5-debugger.vercel.app/) • [Report Bug](https://github.com/likhonsheikhcodes/HTML5-Debugger/issues) • [Request Feature](https://github.com/likhonsheikhcodes/HTML5-Debugger/issues)

</div>

## ✨ Key Features

### 🎮 Game Analysis Tools
- **Instant Game Loading** - Quick test functionality with predefined game URLs
- **Multi-Resolution Testing** - Test games across different device resolutions
- **Performance Metrics** - Real-time FPS monitoring and performance analysis
- **Resource Tracking** - Monitor and analyze game resource usage

### 🔍 Advanced Debugging Features
- **Real-time DOM Inspector** - Analyze and manipulate DOM elements live
- **Network Monitor** - Track all network requests and responses
- **Console Integration** - Capture and analyze console outputs
- **Performance Profiler** - Monitor CPU and memory usage

### 🛠️ Developer Tools
- **Resource Extraction** - Extract and analyze game assets
- **Error Tracking** - Comprehensive error logging system
- **Memory Analysis** - Identify and track memory leaks
- **Network Analysis** - Debug network requests and responses

## 🚀 Quick Start

```bash
# Clone the repository
git clone https://github.com/likhonsheikhcodes/HTML5-Debugger.git

# Navigate to project directory
cd HTML5-Debugger

# Open in your browser
open index.html
```

## 💻 Usage

1. **Quick Test**
   ```javascript
   // Default test URL for quick debugging
   const testUrl = "https://m.pgsoft-games.com/100/index.html?l=en&ot=ca7094186b309ee149c55c8822e7ecf2&btt=2&from=https://clashofslots.com/&language=en-EN&__refer=m.pg-redirect.net&or=static.pgsoft-games.com";
   ```

2. **Custom URL Testing**
   - Enter your game URL in the input field
   - Click "Load URL" to begin debugging
   - Use the toolbar to access different debugging features

3. **Resolution Testing**
   - Select from preset device resolutions
   - Test responsive behavior
   - Monitor performance across different screen sizes

## 📊 Features in Detail

### Network Monitoring
```javascript
// Network request tracking
function monitorNetwork() {
    const originalFetch = window.fetch;
    window.fetch = async (...args) => {
        logRequest(args[0]);
        return originalFetch(...args);
    };
}
```

### Performance Analysis
```javascript
// Performance monitoring
const performanceMetrics = {
    fps: true,
    memory: true,
    network: true,
    resources: true
};
```

### DOM Inspection
```javascript
// DOM element analysis
function analyzeDOMElement(element) {
    return {
        tagName: element.tagName,
        attributes: element.attributes,
        children: element.children.length
    };
}
```

## 🎯 Key Benefits

- **Real-time Analysis**
  - Instant feedback on game performance
  - Live network request monitoring
  - Immediate error detection

- **Comprehensive Debugging**
  - Full DOM inspection capabilities
  - Network traffic analysis
  - Resource usage monitoring

- **Developer-Friendly**
  - Intuitive interface
  - Quick test functionality
  - Extensive debugging tools

## 🔧 Configuration

### Basic Setup
```javascript
const debuggerConfig = {
    autoStart: true,
    networkTracking: true,
    performanceMonitoring: true,
    consoleCapture: true
};
```

### Advanced Options
```javascript
const advancedConfig = {
    resolution: {
        desktop: "1920x1080",
        tablet: "1024x768",
        mobile: "375x667"
    },
    monitoring: {
        interval: 1000, // ms
        metrics: ['fps', 'memory', 'network']
    }
};
```

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- PG Soft Games for testing integration
- HTML5 Game Development Community
- All contributors to this project

## 📫 Contact

Likhon Sheikh - [@likhonsheikhcodes](https://github.com/likhonsheikhcodes)

Project Link: [https://github.com/likhonsheikhcodes/HTML5-Debugger](https://github.com/likhonsheikhcodes/HTML5-Debugger)

---

<div align="center">

Made with ❤️ by [Likhon Sheikh](https://github.com/likhonsheikhcodes)

[⬆ Back to Top](#-html5-game-debugger-pro)

</div>
