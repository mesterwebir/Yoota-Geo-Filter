## 🌐 Languages

- [English](README.md) (Current)
- [فارسی (Persian)](README_FA.md)
# 🛡️ Yoota - Geo Filter

**Geographic Website Blocker for Windows**

Automatically blocks specified websites when connecting from Iran using VPN detection and hosts file modification.

## 🌟 Features

- **Automatic Geo-Detection**: Detects your IP location and country
- **Smart Website Blocking**: Blocks websites only when connected from Iran
- **Real-time Monitoring**: Continuously monitors your connection
- **System Tray Integration**: Runs minimized in system tray
- **Auto-startup**: Automatically starts with Windows
- **DNS Cache Flush**: Ensures immediate blocking effect
- **Modern UI**: Clean and user-friendly interface
- **License System**: Secure license-based activation
- **Admin Notifications**: Receive important announcements

## 🎯 Use Cases

- **VPN Users**: Automatically blocks websites when VPN disconnects
- **Content Filtering**: Selective website blocking based on location
- **Compliance**: Helps maintain local internet regulations
- **Parental Control**: Geographic-based content filtering

## 📋 System Requirements

- **OS**: Windows 10/11 (64-bit)
- **RAM**: 50MB minimum
- **Admin Rights**: Required for hosts file modification
- **Internet**: Required for IP/location detection and license validation

## 🚀 Installation

1. Download the latest version from [Releases](../../releases)
2. Right-click on `Yoota.exe` → "Run as administrator"
3. Enter your license key when prompted
4. Configure websites to block in the main interface

## 🔧 Usage

### Initial Setup
1. **Launch as Admin**: Always run with administrator privileges
2. **License Activation**: Enter your valid license key
3. **Add Websites**: Add domains you want to block (one per line)
4. **Start Monitoring**: Click "▶️ START" to begin monitoring

### Main Interface
- **IP Display**: Shows current IP and detected country
- **Status Indicator**: Monitoring status (Running/Stopped)
- **Website List**: Domains to block when in Iran
- **Activity Log**: Real-time operation logs

### System Tray
- **Show/Hide**: Double-click tray icon
- **Quick Controls**: Right-click for menu options
- **Background Operation**: Runs silently in background

## ⚙️ Configuration

### Website Blocking
```
example.com
www.example.com
subdomain.example.com
```

### Advanced Settings
- **Service Toggle**: Enable/disable blocking service
- **Auto-save**: Automatically saves website list
- **Startup Integration**: Runs automatically with Windows

## 🔒 Security & Privacy

- **Local Operation**: All blocking happens locally via hosts file
- **No Data Collection**: Only IP location is checked
- **Encrypted Communication**: Secure license validation
- **Admin Required**: Ensures legitimate system access

## 🛠️ Technical Details

### How It Works
1. **IP Detection**: Uses ipify.org API for current IP
2. **Location Check**: Determines country using ipapi.co
3. **Hosts File**: Modifies Windows hosts file for blocking
4. **DNS Flush**: Clears DNS cache for immediate effect

### Blocking Mechanism
- Redirects blocked domains to `127.0.0.1`
- Supports www and non-www variants
- Flushes DNS cache twice for reliability
- Works with all browsers and applications

## 🆘 Troubleshooting

### Common Issues

**"Admin Required" Error**
- Solution: Right-click exe → "Run as administrator"

**Websites Not Blocking**
- Check if monitoring is started (▶️ START button)
- Verify admin privileges
- Restart browser after blocking

**License Issues**
- Ensure internet connection for validation
- Contact support: [@yoota_v2ray](https://t.me/yoota_v2ray)

**Multiple Instances**
- Only one instance can run at a time
- Check system tray for existing instance

### Performance
- **Memory Usage**: ~10-15MB RAM
- **CPU Usage**: Minimal (only during IP checks)
- **Network**: Minimal (IP checks every 30 seconds)

## 📞 Support

- **Telegram**: [@yoota_v2ray](https://t.me/yoota_v2ray)
- **Website**: [mesterweb.ir](https://mesterweb.ir)
- **Email**: mesterweb.ir@gmail.com

## 📄 License

This software requires a valid license for operation. Contact us for licensing information.

## 🔄 Updates

- **Auto-check**: License validation includes update notifications
- **Manual Check**: Visit GitHub releases for latest version
- **Changelog**: Available in each release

## ⚠️ Disclaimer

This software is for educational and compliance purposes. Users are responsible for ensuring compliance with local laws and regulations. The software modifies system files (hosts) and requires administrator privileges.

## 🏷️ Version

**Current Version**: 1.0.0  
**Release Date**: 2025  
**Build**: Production Ready

---

**Made with ❤️ by [mesterweb.ir](https://mesterweb.ir)**
