# OrionX OS — Custom Android 14 ROM for Galaxy M31

**OrionX OS** is a custom AOSP-based ROM designed exclusively for **Samsung Galaxy M31 (m31)**. Inspired by the best of **HyperOS, ColorOS, OriginOS, iOS 18, and Android 14**, OrionX combines aesthetic elegance with performance, deep customization, and futuristic interaction.

## Features

### Visual & UI
- iOS 18-style minimalist UI
- Custom **Dynamic Island** (like macOS)
- Animated cosmic wallpapers with orbit effects (purple-blue space theme)
- Home screen with **free-form icons & widgets** (tilt, resize, rotate)
- Dock support, iOS-like Control Center, Notification shade
- Animated **Oci AI Assistant** (cute floating character)
- In-built **Pernya AI Assistant** with personality & expression

### AI Features
- Oci Assistant with:
  - Emotion detection via camera
  - Voice recognition and interaction
  - Security prompts if unrecognized faces detected
  - Sensor-based responses (e.g. yells when overspeeding)
- AI facial registration on first boot
- Full protection mode with lockout if unauthorized access detected

### Performance & Custom Kernel
- Powered by **SuperX Kernel** (based on GrassKernel)
  - 3 performance modes: Safe / Normal / Extreme
- Dedicated app for kernel tuning
- Built-in performance and gaming enhancements

### Media & Entertainment
- Built-in **anime streaming app** (no ads, free access)
- Real-time camera translation
- Watch together: Video+VC+chat+stickers
- Visual filters, background changer in calls & video chats

### Customization
- Floating widgets (Wigade system)
- Home screen themes: space / iOS-style / minimal
- Wallpaper engine with animated stars, galaxies

### Security
- USB access locked if user unknown
- Lock prompts with custom questions (e.g., "What’s my boss’s name?")
- Face scan mandatory for registration
- All Oci features disappear if Oci disabled

## Device Info

- **Device:** Samsung Galaxy M31
- **Codename:** `m31`
- **Android Version:** 14 (AOSP Base)
- **Kernel:** SuperX Kernel (custom, included)
- **Status:** Alpha / Beta / Stable _(customize later)_

## How to Build

1. Fork the repository
2. Clone with `--depth=1`
3. Run via [GitHub Actions workflow](.github/workflows/orionx_build.yml)
4. Output: flashable `.zip` with GApps included

## Credits

- Base: AOSP, LineageOS, Project Elixir
- Kernel: [GrassKernel](https://github.com/username/grasskernel)
- Design: OrionX Team
- Icon sets & Animation: inspired by Apple & OriginOS
- Special thanks to the community

---

> **Note:** OrionX OS is made for learning, creativity, and personal use. Not affiliated with Samsung, Google, or Apple.
