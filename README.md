<<<<<<< HEAD
# IT Chic Travels v2.0 - Premium Redesign

![IT Chic Travels](https://img.shields.io/badge/Status-Ready%20for%20Implementation-success)
![Version](https://img.shields.io/badge/Version-2.0-blue)
![Design](https://img.shields.io/badge/Design-Luxury%20Storyteller-purple)

## 🌍 Overview

A complete v2.0 redesign of IT Chic Travels website, transforming it from a traditional static layout into a **premium, immersive 2026-standard digital experience** with cinematic video backgrounds, glassmorphism aesthetics, and advanced animations.

## ✨ Key Features

### 🎬 Cinematic Experience
- Full-bleed video backgrounds with rotating global destinations
- Smooth 10-second transitions between video clips
- Glassmorphic overlays for depth and readability

### 🎨 Glassmorphism Design
- Transparent-to-solid blurred navigation header
- Frosted glass effect on all content cards
- Multi-layer depth with backdrop filters

### 📐 Bento-Box Grid Layouts
- Asymmetric, visually interesting layouts
- Interactive service and trip cards
- Floating 3D icons with hover animations

### 🎭 Advanced Animations
- **Kinetic Typography**: Cursor-reactive "travel THE WORLD" text
- **Liquid Motion Buttons**: Expanding gradient hover effects (blue → coral)
- **Scroll-Triggered Fade-Ins**: Staggered GSAP animations
- **Parallax Effects**: Depth-based scrolling

### 🎯 Premium UX
- Sticky navigation that shrinks on scroll
- "Start Your Journey" CTA always visible
- Cursor trail effect (desktop)
- Mobile-optimized responsive design

## 🚀 Quick Start

### Prerequisites
- Modern web browser (Chrome 90+, Firefox 88+, Safari 14+)
- Local web server (for video playback)

### Installation

1. **Clone or download this redesign folder**
   ```bash
   cd "IT CHICH TRAVELS/v2_redesign"
   ```

2. **Start a local server**
   ```bash
   # Using Python 3
   python3 -m http.server 8000
   
   # Using Node.js
   npx http-server -p 8000
   
   # Using PHP
   php -S localhost:8000
   ```

3. **Open in browser**
   ```
   http://localhost:8000
   ```

## 📁 Project Structure

```
v2_redesign/
├── index.html              # Main HTML file
├── css/
│   └── style.css          # Complete design system
├── js/
│   └── main.js            # All interactive features
├── assets/
│   ├── videos/            # Hero background videos
│   ├── images/            # Service & trip images
│   └── icons/             # SVG icons and logo
├── DESIGN_DOCUMENTATION.md # Comprehensive design guide
└── README.md              # This file
```

## 🎨 Required Assets

### ⚠️ Important: Asset Placeholder Notice

The current implementation uses **placeholder asset paths**. You need to add the following assets to make the website fully functional:

### Videos (MP4, 1920x1080, H.264)
Place in `assets/videos/`:
- `hero-destinations.mp4` - Mixed global highlights
- `hero-santorini.mp4` - Greek islands footage
- `hero-bali.mp4` - Tropical paradise scenes
- `hero-morocco.mp4` - Desert and marketplace

**Recommended Sources**:
- [Pexels Videos](https://www.pexels.com/videos/) - Free HD travel footage
- [Pixabay Videos](https://pixabay.com/videos/) - Free stock videos
- [Coverr](https://coverr.co/) - Beautiful free videos

**Search Terms**: "santorini sunset", "bali beach", "morocco market", "travel destination"

### Images (WebP/JPEG, 1920x1080+)
Place in `assets/images/`:

**Services**:
- `service-custom-itinerary.jpg` - Travel planning concept
- `service-concierge.jpg` - Luxury hotel concierge
- `service-exclusive.jpg` - VIP yacht/exclusive access

**Trips**:
- `trip-santorini.jpg` - Santorini white buildings
- `trip-bali.jpg` - Bali wellness/nature
- `trip-morocco.jpg` - Moroccan marketplace
- `trip-japan.jpg` - Cherry blossoms in Kyoto

**Testimonials**:
- `avatar-1.jpg` (400x400) - Client photo
- `avatar-2.jpg` (400x400) - Client photo
- `avatar-3.jpg` (400x400) - Client photo

**Recommended Sources**:
- [Unsplash](https://unsplash.com/) - High-quality free photos
- [Pexels](https://www.pexels.com/) - Free stock photography

### Logo
Place in `assets/images/`:
- `logo.svg` - IT Chic Travels logo (transparent background)

**Note**: You can extract the current logo from https://itchictravels.com/ or create a new SVG version.

## 🎯 Asset Quick Download Guide

### Step 1: Download Videos
```bash
# Example using Pexels (requires account)
# 1. Go to https://www.pexels.com/videos/
# 2. Search for: "santorini sunset aerial"
# 3. Download 1920x1080 MP4
# 4. Rename to hero-santorini.mp4
# 5. Move to assets/videos/

# Repeat for other destinations
```

### Step 2: Download Images
```bash
# Example using Unsplash
# 1. Go to https://unsplash.com/
# 2. Search for: "santorini white buildings blue dome"
# 3. Download Large (1920x1080+)
# 4. Rename to trip-santorini.jpg
# 5. Move to assets/images/

# Repeat for all required images
```

### Step 3: Optimize Assets
```bash
# Compress images (optional but recommended)
# Using ImageOptim (Mac) or TinyPNG (web)

# Convert to WebP for better performance
# Using online tool: https://cloudconvert.com/jpg-to-webp
```

# Slutify — ScenePacks (prototype)

This repository contains a small static prototype implementing the ScenePacks layout and interactions used in the Slutify marketing prototype:

- Banner/header with clickable CTAs
- Clickable category chips
- ScenePack tabs and a cover grid
- Download buttons under each pack cover
- A waitlist request modal

## Preview locally

Open `irlmedia-site/index.html` directly, or run a simple server:

```bash
cd irlmedia-site
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Replace assets

Add your own banner images and cover art to `irlmedia-site/assets/` and update the filenames in `index.html`.

## Push to GitHub

If you want to publish this branch to your GitHub remote:

```bash
cd irlmedia-site
git status
git add .
git commit -m "Update ScenePacks prototype layout"
git push
```

This repository may already have a branch pushed as `irlmedia-prototype-final`.

## Next steps

- Replace placeholder images with real scenepack art
- Add real download URLs for each pack
- Add a live form backend for the waitlist

---

**Notes:**

- Branding in the site has been updated to "Slutify" across core prototype pages.
- If you want other project READMEs consolidated or preserved (for example the IT Chic Travels redesign), tell me and I will merge them into a separate folder.

**Version:** 1.0

**Created:** July 2026

