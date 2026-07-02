# Proxy-Aj - Growtopia Proxy for Termux/Android

![Version](https://img.shields.io/badge/version-19.3-blue)
![Platform](https://img.shields.io/badge/platform-Termux%20%7C%20Android-green)
![License](https://img.shields.io/badge/license-MIT-orange)

**Proxy-Aj** adalah proxy server Growtopia yang powerful untuk Termux dan Android. Didasarkan dari kode AJTermux dengan fitur lengkap termasuk authentication KeyAuth, Discord integration, casino links, moderator system, dan banyak lagi.

## ✨ Fitur Utama

✅ **Instalasi Mudah**
- One-line installer untuk Termux
- Dependency auto-install
- Setup dalam hitungan detik

✅ **Growtopia Proxy**
- Full proxy server support
- Multi-port configuration
- Server data templates
- Meta server integration

✅ **Authentication & Security**
- KeyAuth integration
- API authentication
- Version checking
- Update management

✅ **Discord Integration**
- Discord webhook support
- Server links
- Login messages
- Update notifications

✅ **Casino & Warp Links**
- Multiple casino links
- Custom warp system
- Discord webhook webhooks
- URL body support

✅ **User Management**
- Role system (owner, LEKSA, kondee, Dabah, leksa)
- Moderator management
- Admin controls
- User permissions

✅ **Advanced Features**
- Private server support
- Custom banners (RTTEX)
- FPS offset patterns
- Login system integration
- Item backup system
- Anti-cheat support

## 🚀 Installation

### Quick Install (Termux)

```bash
bash <(wget -qO- https://raw.githubusercontent.com/Thomzh/Proxy-Aj/main/install.sh)
```

### Manual Install

```bash
git clone https://github.com/Thomzh/Proxy-Aj.git
cd Proxy-Aj
chmod +x install.sh
./install.sh
```

## 📖 Usage

### Jalankan Proxy

```bash
./proxy
```

### Edit Konfigurasi

```bash
# Edit config utama
nano file

# Edit Android variables
nano vars
```

## ⚙️ Konfigurasi

### Server Settings

```
ProxyServer|195.62.48.50
ProxyServerPort|1234
GrowtopiaIP|213.179.209.175
GrowtopiaPort|17043|17043|17043|17043|17043
```

### Discord Integration

```
discord|discord.gg/ajproxy
DiscordID|1210909836288729099
```

### Custom Warp Links

```
CsnLink|/mylink|Custom Link||https://example.com|1|urlbody||
```

### Moderator Management

```
AddModsList|67302|`#@Miu
AddModsList|36299549|`#@Moniuet
```

### User Roles

```
KovatTyypit|owner|LEKSA|kondee|Dabah|leksa
```

## 📁 File Structure

```
Proxy-Aj/
├── install.sh           # Installation script
├── proxy                # Main binary
├── file                 # Main configuration
├── vars                 # Android variables
├── README.md           # Documentation
├── QUICKSTART.md       # Quick start guide
└── LICENSE             # MIT License
```

## 🎮 Growtopia Configuration

### Server Data

```
server_data_Start
server|%s
port|17091
loginurl|login.growtopiagame.com
type|1
meta|%s
RTENDMARKERBS1001
server_data_End
```

### Login Messages

```
LoginMessage1|Welcome!
LoginMessage2|Enjoy!
LoginMessage3|Logging In...
```

### Update Messages

```
UpdateMessage|New version available!
ProxyVersion|19.3
ProxyVersion_ANDROID|18.6
```

## 🔧 Troubleshooting

### Instalasi gagal

```bash
# Update packages
apt update && apt upgrade -y

# Install dependencies
apt install wget -y

# Run installer lagi
bash install.sh
```

### Proxy tidak jalan

```bash
# Check permissions
chmod +x proxy

# Check file config
cat file
```

### Port sudah digunakan

Edit `file` dan ubah:
```
ProxyServerPort|8888
```

## 📝 Customization

### Tambah Private Server

```
AddGTPSInfo|Server Name|127.0.0.1
```

### Tambah Custom Banner

```
Rttex|banner_name.rttex|https://link.to/banner.rttex
```

### Tambah Moderator

```
AddModsList|USER_ID|`#@Username
```

## 🔗 Links

- **GitHub**: https://github.com/Thomzh/Proxy-Aj
- **Discord**: discord.gg/ajproxy
- **Issues**: https://github.com/Thomzh/Proxy-Aj/issues
- **Original**: https://github.com/JoakimTheCoder/AJTermux

## 📊 Version History

**v19.3** (Current)
- Based on AJTermux
- Full Growtopia proxy support
- KeyAuth integration
- Termux optimization
- Enhanced configuration system

## 📄 License

MIT License - Lihat [LICENSE](LICENSE) untuk details

## ⚠️ Disclaimer

Tool ini disediakan untuk educational dan authorized use saja. Pengguna bertanggung jawab memastikan penggunaannya sesuai dengan semua hukum yang berlaku dan terms of service.

## 🤝 Contributing

Contributions welcome! Silakan:

1. Fork repository
2. Buat feature branch
3. Commit changes
4. Push ke branch
5. Buka Pull Request

## 📧 Support

- **Discord**: discord.gg/ajproxy
- **GitHub Issues**: Buka issue untuk bugs atau feature requests

---

**Made with ❤️ by Thomzh**

*Based on AJTermux by JoakimTheCoder*

*Last Updated: 2026-07-02*
