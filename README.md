# Music Library Manager

A modern, cross-platform music library management application built with Electron and Svelte. Organize, play, and analyze your music collection with advanced waveform visualization and comprehensive metadata management.

![Music Library Manager](https://img.shields.io/badge/Version-0.11.3-blue)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20macOS%20%7C%20Linux-green)
![License](https://img.shields.io/badge/License-ISC-yellow)

## ✨ Features

### 🎵 **Music Management**

- **Smart Library Organization**: Add and organize your music files with comprehensive metadata support
- **Advanced Search**: Powerful search functionality with tag-based filtering
- **Drag & Drop Support**: Easily add songs by dragging files into the application
- **Metadata Editing**: Edit song information including title, artist, album, genre, and custom tags

### 🌊 **Waveform Visualization**

- **Real-time Waveforms**: Generate actual audio waveforms using FFmpeg integration
- **Visual Playback**: See your music as you play it with synchronized waveform displays
- **Performance Options**: Toggle between real waveforms and simulated ones for better performance
- **Caching System**: Intelligent waveform caching to improve load times

### 🎛️ **Audio Playback**

- **High-Quality Playback**: Support for various audio formats (MP3, FLAC, WAV, OGG, AAC)
- **Global Volume Control**: Unified volume management across all tracks
- **Audio Statistics**: View detailed audio information including bitrate, sample rate, and codec details

### 🏷️ **Tag System**

- **Custom Tags**: Create and assign custom tags to organize your music
- **Smart Filtering**: Filter your library by multiple tags simultaneously
- **Tag Management**: Easy tag creation, editing, and deletion

### 💾 **Database Management**

- **SQLite Backend**: Reliable local database storage
- **Database Migration**: Move your database to custom locations
- **Backup System**: Automatic and manual backup functionality
- **Data Import/Export**: Load existing databases or create new ones

### 🎨 **Modern Interface**

- **Dark/Light Themes**: Toggle between beautiful dark and light modes
- **Responsive Design**: Clean, modern interface with smooth animations
- **Real-time Updates**: Instant UI updates and responsive controls
- **Customizable Settings**: Comprehensive settings for audio, display, and performance

### 🔄 **Auto-Updates**

- **Background Updates**: Automatic update checking and downloading
- **Release Notes**: View changelog for new versions
- **Configurable**: Control update behavior through settings

## 📥 Download & Installation

### System Requirements

- **Windows**: Windows 10 or later (64-bit)
- **macOS**: macOS 10.14 (Mojave) or later
- **Linux**: Most modern distributions (64-bit)
- **Storage**: 100MB+ free space
- **RAM**: 4GB+ recommended

### Download Latest Release

**[📥 Download Music Library Manager v0.11.3](https://github.com/DMDComposer/Library-Manager-Releases/releases/latest)**

#### Platform-Specific Downloads:

**🖥️ Windows**

- **`Music Library Manager-0.11.3-win-x64.exe`** - Windows Installer
- Double-click to install, follows standard Windows installation process

**🍎 macOS**

- **`Music Library Manager-0.11.3-mac-x64.dmg`** - Intel Macs
- **`Music Library Manager-0.11.3-mac-arm64.dmg`** - Apple Silicon (M1/M2)
- Open the DMG and drag the app to your Applications folder

**🐧 Linux**

- **`Music Library Manager-0.11.3-linux-x64.AppImage`** - Portable AppImage
- Make executable: `chmod +x Music-Library-Manager-*.AppImage`
- Run directly: `./Music-Library-Manager-*.AppImage`

### Installation Notes

- **First Launch**: The app will create its database and settings on first run
- **Updates**: The app can auto-update itself when new versions are available
- **Permissions**: May request file system access for music library management

## 🎯 Quick Start Guide

### Getting Your Music Library Started

1. **Launch the Application**

   - Windows: Start Menu > Music Library Manager
   - macOS: Applications > Music Library Manager
   - Linux: Run the AppImage file

2. **Add Your First Songs**

   - **Drag & Drop**: Simply drag music files from your file explorer into the app
   - **Add Button**: Click "Add Song" to manually create entries
   - **Bulk Import**: Drag entire folders to import multiple files at once

3. **Organize with Tags**

   - Right-click any song to add custom tags
   - Use tags like "Favorites", "Workout", "Chill", etc.
   - Filter your library by clicking on tags

4. **Customize Your Experience**
   - Go to **Settings** to configure waveforms, themes, and audio options
   - Toggle **Dark Mode** for a sleek nighttime interface
   - Adjust **Waveform Settings** based on your system performance

### Using Key Features

#### **Waveform Visualization**

- **Enable**: Settings > Audio & Waveforms > Show Waveforms ✅
- **Real Waveforms**: For actual audio analysis (requires more processing)
- **Simulated Waveforms**: For better performance on slower systems

#### **Search & Filter**

- **Search Bar**: Find songs by title, artist, album, or any metadata
- **Tag Filtering**: Click tags to filter your library instantly
- **Clear Filters**: Use the "Clear" button to reset all filters

#### **Audio Management**

- **Playback**: Click any song to start playing
- **Volume Control**: Use the global volume slider in settings
- **Audio Info**: View detailed codec and quality information

#### **Database & Backups**

- **Auto-Backup**: Enabled by default, creates regular backups
- **Manual Backup**: Settings > Database > Create Backup
- **Move Database**: Relocate to external storage if needed

## ⚡ Performance Tips

### For Best Performance:

- **Disable Real Waveforms** on older or slower computers
- **Enable Waveform Caching** to speed up repeated loads
- **Use SSD Storage** for your database location when possible
- **Close Other Audio Applications** to avoid conflicts

### Troubleshooting:

- **Audio Not Playing**: Check that your audio files aren't corrupted
- **Slow Waveforms**: Switch to simulated waveforms in settings
- **Database Issues**: Try creating a backup and restarting the app
- **Update Problems**: Check your internet connection and try manual update

## 🔧 Advanced Features

### FFmpeg Integration (Optional)

For enhanced waveform generation, install FFmpeg on your system:

- **Windows**: Download from [ffmpeg.org](https://ffmpeg.org/download.html)
- **macOS**: Install via Homebrew: `brew install ffmpeg`
- **Linux**: Install via package manager: `sudo apt install ffmpeg`

### Database Management

- **Multiple Libraries**: Create different databases for different music collections
- **Custom Locations**: Move your database to cloud storage, external drives, etc.
- **Import/Export**: Share libraries between devices or backup to cloud

### Keyboard Shortcuts

- **Ctrl/Cmd + F**: Focus search bar
- **Space**: Play/Pause current song
- **Ctrl/Cmd + ,**: Open Settings
- **Escape**: Close modals/sidebars

## 🆘 Support & Community

### Get Help

- **📖 User Guide**: Check the built-in help in Settings > About
- **🐛 Report Issues**: [GitHub Issues](https://github.com/DMDComposer/Library-Manager-Releases/issues)
- **💡 Feature Requests**: [GitHub Discussions](https://github.com/DMDComposer/Library-Manager-Releases/discussions)
- **📧 Direct Support**: Contact through GitHub or project issues

### Stay Updated

- **⭐ Star the Project** on GitHub for updates
- **🔔 Watch Releases** to get notified of new versions
- **📱 Follow Development** for behind-the-scenes updates

## 🎵 What Users Are Saying

> _"Finally, a music manager that actually works the way I think. The waveforms are gorgeous and the tagging system is exactly what I needed."_ - Audio Professional

> _"Switched from iTunes and never looked back. This app is fast, beautiful, and doesn't try to sell me anything."_ - Home User

> _"The database backup feature saved my entire music collection when my drive failed. Highly recommend!"_ - Music Collector

## 🚀 Upcoming Features

### Coming Soon:

- 🎵 **Playlist Management**: Create and manage custom playlists
- 🎧 **Advanced Audio Analysis**: Detailed frequency analysis and audio insights
- 🔌 **Plugin System**: Extend functionality with community plugins
- ☁️ **Cloud Sync**: Synchronize libraries across multiple devices

### Long-term Roadmap:

- 🌐 **Streaming Integration**: Connect with popular music services
- 🤖 **Smart Organization**: AI-powered music categorization
- 📊 **Analytics Dashboard**: Listening habits and music insights
- 👥 **Multi-user Support**: Shared libraries for families/teams

## 📜 License & Credits

**License**: ISC License - Free for personal and commercial use

**Built With**: Electron, Svelte, TypeScript, and modern web technologies

**Acknowledgments**: Special thanks to the open-source community and all contributors who make this project possible.

---

**🎶 Ready to transform your music experience?**

**[Download Music Library Manager Now](https://github.com/DMDComposer/Library-Manager-Releases/releases/latest)**

If you love this app, please ⭐ **star the project** on GitHub and share it with fellow music enthusiasts!

## Version History

See [Releases](https://github.com/DMDComposer/Library-Manager-Releases/releases) for detailed changelog.
