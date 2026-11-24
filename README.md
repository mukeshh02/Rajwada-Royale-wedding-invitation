# Rajwada Royale ✦ Premium Interactive Wedding Invitation

> **Template Name:** Rajwada Royale  
> **Brand:** A.C.P Invites  
> **Contact:** 7000371321  
> **Website Section:** [akashcamera.com/invites](https://akashcamera.com/invites)

---

## 🌟 Template Overview
**Rajwada Royale** is an imperial, mobile-responsive North Indian & Rajasthani Palace digital wedding invitation featuring rich interactive animations, royal gate unfolding, traditional wedding shehnai background music, and authentic heritage aesthetics.

### ✨ Key Features:
1. **Royal Double-Door Unfolding Animation**:
   - Deep royal maroon double doors carved with gold floral motifs and imperial elephants.
   - Central royal card with Lord Ganesha's sacred emblem and Sanskrit invocation (*श्री गणेशाय नमः*).
   - Smooth 3D gate-swing opening animation on tap.
2. **Background Shehnai & Instrumental Music**:
   - Autoplay upon opening with persistent floating audio toggle (mute / unmute controls).
3. **Hero Palace Mandap & Golden Calligraphy**:
   - Illuminated royal palace garden mandap with fountain reflections, golden domes, and couple names in royal calligraphy.
4. **Parchment Scrolls with Golden Rollers**:
   - Unrolling parchment scrolls detailing bride and groom family lineages.
5. **Interactive "Reveal the Date" Slot Machine**:
   - Gazebo arch illustration with animated rolling date wheels locking smoothly onto the wedding date.
6. **3D Hanging Photo Gallery with Pendulum Physics**:
   - Photo frames suspended by cords and brass rings that sway gently with inertia on scroll.
7. **Arched Ceremony Cards**:
   - Illustrated royal cards for Ring Ceremony, Mehendi, Haldi, Sangeet, Vivaah, and Reception with direct Google Maps navigation links.
8. **Custom Footer Branding**:
   - Dedicated bottom bar featuring **A.C.P Invites (7000371321)** with direct tap-to-call dialer.
9. **Zero Third-Party Dependency**:
   - All fonts (Cormorant Garamond, Fraunces, Sora, Tiro Devanagari Sanskrit), media, audio, and vendor scripts are self-hosted.

---

## 🚀 How to Run Locally

### Option 1: One-Click (Windows)
Double-click on [`run_localhost.bat`](run_localhost.bat).

### Option 2: Python (Terminal)
```bash
python server.py 8000
```
Open your browser at: **http://127.0.0.1:8000/**

---

## 📁 Folder Structure
- `index.html` — Root redirect entry point
- `server.py` — Python HTTP server with media streaming support
- `run_localhost.bat` — Windows quick launch script
- `templates/royale/` — Main template assets, scripts, styles, and media
  - `index.html` — Core invitation layout
  - `styles.css` — Royal design system and animations
  - `media/` — Palace video, audio track, SVG icons, and photos
- `templates/_platform/` — Self-hosted fonts, audio controllers, and GSAP/Lenis animation libraries
