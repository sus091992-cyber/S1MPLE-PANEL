# ⚡S1MPLE PANEL V1

**Modern Modified Edition of BPB Panel with Clean IP Scanner**

## 📋 Overview

⚡S1MPLE PANEL V1 is a beautifully redesigned and modernized version of the original [BPB Panel](https://github.com/bia-pain-bache/BPB-Worker-Panel) with an enhanced UI and additional features.

This is **NOT a complete repack** - it maintains 100% of the original functionality while adding:
- 🎨 Modern Red + White Color Scheme with smooth hover effects
- 🧹 Built-in Clean IP Scanner (runs on Cloudflare Workers)
- ✨ Enhanced UI/UX Design

## 🎯 Key Differences from Original

| Feature | Original BPB | S1MPLE V1 |
|---------|-------------|-----------|
| **Color Scheme** | Blue | Red + White ✨ |
| **UI Design** | Standard | Modern & Enhanced |
| **Clean IP Scanner** | External Link | Built-in Feature |
| **Functionality** | ✅ All | ✅ All (Same) |
| **Cloudflare Ready** | ✅ Yes | ✅ Yes |

## ⚙️ Features

All original BPB Panel features + enhancements:

- ✅ **VLESS & Trojan Protocols**
- ✅ **Warp Configuration Support**
- ✅ **Fragment Support**
- ✅ **Private DoH Server**
- ✅ **Chain Proxy Support**
- ✅ **Routing Rules (Bypass/Block)**
- ✅ **Multi-Client Support** (Xray, Sing-box, Clash, etc.)
- ✅ **Password Protection**
- ✅ **Full Customization**
- 🆕 **Clean IP Finder** - Integrated Scanner

## 🧹 Clean IP Scanner Feature

The built-in Clean IP Scanner helps you find clean Cloudflare IPs directly from the panel:

- Scans on **Cloudflare Workers** (no local processing)
- Identifies clean public IPs
- Returns IP details (Country, ISP, etc.)
- Seamlessly integrated into the panel interface

## 🚀 Deployment on Cloudflare

### ✅ Cloudflare Worker Compatible
- ✅ Can be deployed as Worker
- ✅ Can be deployed as Worker with custom domain
- ✅ Fully compatible with all Cloudflare features

### ✅ Cloudflare Pages Compatible
- ✅ Can be deployed as Pages
- ✅ Support for custom domains

**Status:** 🟢 **PRODUCTION READY** - Fully compatible with Cloudflare Workers & Pages

## 📦 Installation

### Quick Start (Using BPB Wizard)

1. Download from [BPB Wizard](https://github.com/bia-pain-bache/BPB-Wizard)
2. Replace the original files with S1MPLE PANEL files
3. Deploy to Cloudflare Workers or Pages

### Manual Installation

1. Clone this repository
2. Set up your Cloudflare account
3. Deploy worker.js to Cloudflare Workers
4. Configure environment variables (UUID, Password, etc.)
5. Access your panel at `your-domain.com/panel`

## 🔧 Configuration

All configurations work the same as the original BPB Panel:

**Required Environment Variables:**
- `UUID` - VLESS UUID
- `TR_PASS` - Trojan Password

**Optional:**
- `PROXY_IP` - Proxy IP or domain
- `PREFIX` - NAT64 Prefixes
- `SUB_PATH` - Subscription URI path
- `FALLBACK` - Fallback domain
- `DOH_URL` - Custom DoH server

## 🎨 UI Improvements

### Modern Design
- **Red + White Color Scheme** - Eye-catching yet professional
- **Smooth Hover Effects** - Better user interactions
- **Enhanced Typography** - More readable and modern
- **Responsive Layout** - Works on all devices

### Dark Mode Support
- Full dark mode included
- Auto-detect system preference

## 📚 Original Documentation

For detailed configuration and usage, refer to the original BPB Panel documentation:
- [BPB Panel Official Repository](https://github.com/bia-pain-bache/BPB-Worker-Panel)
- [BPB Documentation](https://bia-pain-bache.github.io/BPB-Worker-Panel/)
- [Installation Guide](https://bia-pain-bache.github.io/BPB-Worker-Panel/installation/wizard/)

## 🤝 Credits

- **Original BPB Panel:** [bia-pain-bache](https://github.com/bia-pain-bache/BPB-Worker-Panel)
- **Modified Version (S1MPLE PANEL V1):** This Repository

## ⚠️ Important Notes

- This is a **UI modification** of BPB Panel, not a fork
- All core functionality remains unchanged from the original
- The Clean IP Scanner is an additional feature
- For advanced support, refer to [original BPB documentation](https://github.com/bia-pain-bache/BPB-Worker-Panel)

## 📄 License

This project maintains the same license as the original BPB Panel: **GPL-3.0**

---

## 🚀 What's New in V1

- 🎨 Complete UI redesign with red/white theme
- 🧹 Integrated Clean IP Scanner
- ✨ Smooth animations and modern effects
- 📱 Enhanced mobile responsiveness
- 🎯 Better visual hierarchy

---

**Version:** 1.0.0  
**Last Updated:** 2026-06-15  
**Status:** ✅ Production Ready

For issues or feature requests related to the modified UI/features, open an issue here.  
For BPB Panel core issues, refer to the [original repository](https://github.com/bia-pain-bache/BPB-Worker-Panel).
