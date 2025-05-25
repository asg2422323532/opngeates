# 📱 Open Gate Camera App

A professional iPhone camera app that enables **Open Gate** shooting - capturing the full sensor area without typical video format crops for maximum post-production flexibility.

## 🎯 What is Open Gate?

Open Gate refers to utilizing the **full camera sensor area** instead of cropping to standard video formats (like 16:9). This provides:

- **Maximum image data** for post-production
- **4:3 aspect ratio** capturing the full sensor
- **Professional flexibility** for cropping in post
- **Higher resolution** than standard video modes

## ✨ Features

### 📹 Core Camera Features
- **Full Sensor Utilization** - Capture maximum image data
- **4:3 Aspect Ratio** - True Open Gate format
- **High-Quality Recording** - Up to 15 Mbps bitrate
- **Multiple Modes** - Photo, Video, and Cinematic
- **Real-time Preview** - Live Open Gate viewfinder

### 🎮 iPhone-Optimized Controls
- **Touch to Focus** - Tap anywhere to focus
- **Pinch to Zoom** - 1×, 2×, 3× zoom levels
- **Swipe Mode Switching** - Horizontal swipes to change modes
- **Camera Flip** - Switch between front/back cameras
- **Haptic Feedback** - Native iOS-style vibrations

### 🎨 Professional UI
- **iPhone-Native Design** - Follows iOS design guidelines
- **Safe Area Support** - Optimized for iPhone notch and Dynamic Island
- **Recording Indicators** - Live timer and status
- **Visual Guides** - Open Gate frame overlay
- **Dark Mode Ready** - Automatic dark mode support

## 📱 iPhone Compatibility

### ✅ Supported Features
- **Safari Browser** - Full functionality
- **Camera Access** - Front and back cameras
- **Media Recording** - High-quality video/photo capture
- **Touch Gestures** - Native iOS-style interactions
- **Full Screen Mode** - Immersive camera experience

### 📋 Requirements
- **iOS 12+** recommended
- **Safari browser** (required for camera access)
- **HTTPS connection** (for camera permissions)
- **Camera/Microphone permissions**

## 🚀 Installation & Setup

### Option 1: GitHub Pages (Recommended)
1. Fork this repository
2. Enable GitHub Pages in Settings
3. Visit your GitHub Pages URL on iPhone Safari
4. Add to Home Screen for app-like experience

### Option 2: Local Development
```bash
# Clone the repository
git clone https://github.com/yourusername/opengate-camera.git

# Navigate to directory
cd opengate-camera

# Start local server (Python)
python -m http.server 8000

# Or use Node.js
npx serve .

# Access on iPhone Safari: http://your-ip:8000
```

### Option 3: Direct Hosting
Upload `index.html` to any web hosting service that supports HTTPS:
- Netlify
- Vercel  
- Firebase Hosting
- AWS S3 + CloudFront

## 📖 Usage Guide

### 🎬 Recording Open Gate Video
1. **Launch the app** in Safari
2. **Grant permissions** for camera and microphone
3. **Select Video mode** (default)
4. **Frame your shot** using the Open Gate guides
5. **Tap capture button** to start/stop recording
6. **Files auto-download** to your device

### 📸 Capturing Open Gate Photos
1. **Switch to Photo mode**
2. **Compose your shot** with full sensor preview
3. **Tap capture button** to take photo
4. **Photo downloads** automatically

### 🎯 Advanced Features
- **Touch to Focus**: Tap anywhere on screen
- **Zoom Control**: Use 1×, 2×, 3× buttons
- **Mode Switching**: Swipe left/right or use buttons
- **Camera Flip**: Tap the flip button (🔄)

## ⚙️ Technical Specifications

### 📹 Video Recording
- **Resolution**: Up to 1920×1440 (4:3)
- **Format**: WebM (VP9 codec)
- **Bitrate**: 15 Mbps for maximum quality
- **Frame Rate**: 30 FPS
- **Audio**: Opus codec, stereo

### 📸 Photo Capture
- **Resolution**: Full sensor resolution
- **Format**: JPEG (95% quality)
- **Aspect Ratio**: 4:3 Open Gate
- **Color Space**: sRGB

### 🔧 Browser APIs Used
- **MediaDevices API** - Camera access
- **MediaRecorder API** - Video recording
- **Canvas API** - Photo capture
- **Blob API** - File handling

## 🛠️ Development

### 📁 Project Structure
```
opengate-camera/
├── index.html          # Main app file
├── README.md          # This file
└── assets/           # Screenshots (optional)
```

### 🔨 Customization
The app is built as a single HTML file for easy deployment. Key areas for customization:

- **Video Quality**: Modify `videoBitsPerSecond` in `startRecording()`
- **UI Colors**: Update CSS custom properties
- **Aspect Ratios**: Adjust Open Gate dimensions
- **Recording Formats**: Change `mimeType` options

### 🧪 Testing
```bash
# Test on different devices
# iPhone Safari (primary target)
# iPad Safari
# Desktop Safari (limited functionality)
```

## 🐛 Troubleshooting

### Common Issues

**❌ Camera not working**
- Ensure you're using Safari (not Chrome/Firefox)
- Check camera permissions in Settings
- Verify HTTPS connection
- Try refreshing the page

**❌ Recording fails**
- Check available storage space
- Ensure stable internet connection
- Try different recording quality settings
- Clear browser cache

**❌ Files not downloading**
- Check Safari download settings
- Ensure popup blocker is disabled
- Try a different browser tab

### 🔧 Debug Mode
Open Safari Developer Tools (if available) to see console logs:
- Camera resolution information
- Recording status updates
- Error messages

## 📱 iPhone-Specific Notes

### 🔒 Permissions
- **First launch**: Safari will request camera/microphone access
- **Settings**: Manage permissions in Safari > Settings > Camera
- **Privacy**: All processing happens locally on device

### 💾 File Handling
- **Downloads**: Files save to Safari Downloads folder
- **File App**: Access via Files app > Downloads
- **Sharing**: Use iOS share sheet to send files

### 🔋 Performance
- **Battery**: Camera usage may drain battery quickly
- **Heat**: Extended recording may cause device warming
- **Memory**: Large files may require device restart

## 🚀 Deployment Options

### Production Deployment
1. **GitHub Pages**: Free, easy setup
2. **Netlify**: Drag-and-drop deployment
3. **Vercel**: Git-based deployment
4. **Firebase Hosting**: Google's hosting platform

### Enterprise Deployment
- **Internal hosting**: Deploy on company servers
- **App Store**: Convert to native app using Cordova/PhoneGap
- **Progressive Web App**: Add manifest.json for PWA features

## 🤝 Contributing

Contributions welcome! Areas for improvement:

- **Additional camera controls** (ISO, shutter speed)
- **More recording formats** (ProRes, H.265)
- **Advanced editing features**
- **Cloud storage integration**
- **Social sharing features**

## 📄 License

MIT License - Feel free to use and modify for your projects.

## 📞 Support

- **Issues**: Open GitHub issues for bugs
- **Feature Requests**: Submit enhancement ideas
- **Documentation**: Improve this README

## 🎉 Acknowledgments

- Inspired by professional cinema cameras
- Built for iPhone Safari optimization
- Designed for content creators and filmmakers

---

**📱 Ready to shoot in Open Gate? Launch the app and start capturing the full sensor!**
