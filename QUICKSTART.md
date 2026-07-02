# Proxy-Aj - Quick Start

## Installation (30 detik)

```bash
bash <(wget -qO- https://raw.githubusercontent.com/Thomzh/Proxy-Aj/main/install.sh)
```

## Jalankan Proxy

```bash
./proxy
```

## Edit Konfigurasi

```bash
# Edit config utama
nano file

# Edit Android vars
nano vars
```

## Common Commands

```bash
./proxy              # Jalankan proxy
cat file            # Lihat config
nano file           # Edit config
```

## Konfigurasi Cepat

### Ubah Server
```
ProxyServer|195.62.48.50
ProxyServerPort|1234
```

### Ubah Discord
```
discord|discord.gg/ajproxy
DiscordID|1210909836288729099
```

### Tambah Warp Link
```
CsnLink|/mylink|Custom Link||https://example.com|1|urlbody||
```

### Tambah Moderator
```
AddModsList|USER_ID|`#@Username
```

## File Utama

| File | Fungsi |
|------|--------|
| `proxy` | Binary utama |
| `file` | Konfigurasi utama |
| `vars` | Konfigurasi Android |
| `install.sh` | Script instalasi |

## Troubleshooting

| Masalah | Solusi |
|--------|--------|
| Permission denied | `chmod +x proxy` |
| Proxy tidak jalan | Edit `file` |
| Port error | Ubah `ProxyServerPort` |
| wget not found | `apt install wget -y` |

## Next Steps

1. ✅ Install Proxy-Aj
2. 📝 Edit `file` dan `vars`
3. 🚀 Jalankan `./proxy`
4. 🎮 Connect ke Growtopia
5. 🔧 Customize sesuai kebutuhan

## Support

- Discord: discord.gg/ajproxy
- GitHub: https://github.com/Thomzh/Proxy-Aj

---

**Happy Gaming! 🎮**
