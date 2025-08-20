# Next.js + shadcn + Tweakcn Theme Creator

Automates creation of Next.js 15 apps with TypeScript, Tailwind v4, all 47 shadcn components, and 24 beautiful themes.

## Usage Options

### Option 1: Claude Code Command (Recommended)

1. **Copy both files to your Claude commands directory:**
   ```bash
   cp nextjs-shadcn.md ~/.claude/commands/
   cp create-nextjs-shadcn.sh ~/.claude/commands/
   chmod +x ~/.claude/commands/create-nextjs-shadcn.sh
   ```

2. **Use the command:**
   ```bash
   /nextjs-shadcn
   ```

   The AI will guide you through interactive setup asking for:
   - Project name
   - Location 
   - Theme choice (24 options available)

### Option 2: Standalone Script

Run the script directly:

```bash
./create-nextjs-shadcn.sh [project-name] [path] [theme]
```

**Examples:**
```bash
# Basic usage
./create-nextjs-shadcn.sh my-app

# With custom path
./create-nextjs-shadcn.sh my-app ./projects

# With theme
./create-nextjs-shadcn.sh my-app ./projects violet-bloom
```

## What Gets Created

- ✅ Next.js 15 with TypeScript
- ✅ Tailwind CSS v4
- ✅ All 47 shadcn UI components
- ✅ App Router + Turbopack
- ✅ Optional tweakcn theme
- ✅ Ready for `npm run dev`

## Available Themes

Choose from 24 themes organized by style:
- **Clean & Minimal**: modern-minimal, clean-slate, amber-minimal
- **Bold & Striking**: neo-brutalism, bold-tech, retro-arcade  
- **Purple & Cosmic**: violet-bloom, cosmic-night, quantum-rose, amethyst-haze
- **Warm & Earthy**: mocha-mousse, kodama-grove, solar-dusk, vintage-paper
- **Playful & Vibrant**: t3-chat, pastel-dreams, midnight-bloom, soft-pop
- **Cool & Calm**: ocean-breeze, northern-lights
- **Unique Styles**: doom-64, elegant-luxury, sunset-horizon, starry-night

## Requirements

- Node.js (for Next.js)
- Git (for cloning)
- Internet connection (for package installation)

🚀 NextJS + Shadcn + Tweakcn Theme Setup
=========================================

This will create a Next.js 15 app with:
✅ TypeScript + Tailwind v4
✅ All 47 shadcn components
✅ Optional beautiful theme
✅ Turbopack + App Router

Please provide the following:

1. **Project Name**: What should we call your app?
   Example: my-awesome-app

2. **Location**: Where should we create it? 
   (press Enter for current directory: !`pwd`)
   
3. **Theme**: Choose a theme or press Enter for default shadcn

Available Themes:
-----------------
🎨 Clean & Minimal
   • modern-minimal - Professional blue tones, sleek design
   • clean-slate - Fresh neutral palette, versatile
   • amber-minimal - Warm sophisticated amber accents

🔥 Bold & Striking  
   • neo-brutalism - Bold red/yellow/blue, hard shadows, zero radius
   • bold-tech - Strong confident tech aesthetic
   • retro-arcade - Solarized colors, 8-bit nostalgia

💜 Purple & Cosmic
   • violet-bloom - Deep purple, modern and vibrant
   • cosmic-night - Dark purple space theme
   • quantum-rose - Pink-purple gradient, futuristic
   • amethyst-haze - Soft purple with dreamy undertones

☕ Warm & Earthy
   • mocha-mousse - Coffee browns, cozy café vibes
   • kodama-grove - Forest greens, natural and grounded
   • solar-dusk - Sunset oranges, desert twilight
   • vintage-paper - Aged paper browns, literary classic

🎈 Playful & Vibrant
   • t3-chat - Pink social chat theme
   • pastel-dreams - Soft pastel purples, dreamy
   • midnight-bloom - Deep purple nights, floral
   • soft-pop - Gentle pop colors, soft edges

🌊 Cool & Calm
   • ocean-breeze - Fresh aqua blues, seaside
   • northern-lights - Green/blue aurora, arctic

🎮 Unique Styles
   • doom-64 - Dark red retro gaming, FPS nostalgia
   • elegant-luxury - Premium refined feel
   • sunset-horizon - Orange to purple gradient
   • starry-night - Deep space with star accents

   
Built for Claude Code but works standalone.
