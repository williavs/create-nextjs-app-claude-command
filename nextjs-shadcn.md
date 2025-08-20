---
allowed-tools: Bash
argument-hint: (interactive setup)
description: Create a NextJS app with full shadcn UI setup and optional tweakcn theme
---

# Create NextJS + Shadcn Project with Tweakcn Themes

## Context
- Arguments provided: $ARGUMENTS
- Current directory: !`pwd`

## Your Task

Guide the user through an interactive setup process to create a new NextJS project with shadcn and optional theme.

### Step 1: Interactive Setup

First, show the user what we're about to create and ask for their preferences:

```
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
```

Wait for the user to provide their choices.

### Step 2: Parse User Input
Once the user provides their input, parse it to extract:
- Project name (required)
- Location (optional, use current directory if not specified)
- Theme (optional, use default if not specified)

### Step 3: Execute Setup
Run the setup script with the provided arguments:
```bash
~/.claude/scripts/create-nextjs-shadcn.sh [project-name] [path] [theme]
```

### Step 4: Confirm Success
After successful completion, let the user know:
- ✅ Project created: [name] at [location]
- ✅ All 47 shadcn components installed
- ✅ Theme applied: [theme name] (if specified)
- 📦 Next steps: `cd [project]` and `npm run dev`

## Available Themes (from tweakcn.com)

### Clean & Minimal
- **modern-minimal** - Clean blue tones, Inter font. Professional and sleek with subtle radius
- **clean-slate** - Fresh, pristine design with neutral palette for versatile applications  
- **amber-minimal** - Warm amber accents with minimalist approach, sophisticated warmth

### Bold & Striking
- **neo-brutalism** - Bold red/yellow/blue, hard shadows, zero radius. Unapologetically stark
- **bold-tech** - Strong tech aesthetic with confident color choices
- **retro-arcade** - Solarized palette inspired by classic arcade games. Nostalgic 8-bit vibes

### Purple & Cosmic
- **violet-bloom** - Deep purple theme with Plus Jakarta Sans. Modern and vibrant
- **cosmic-night** - Dark purple cosmic theme. Spacey and mysterious with gradient vibes
- **quantum-rose** - Pink-purple gradient aesthetic. Futuristic and feminine
- **amethyst-haze** - Soft purple haze with dreamy undertones

### Warm & Earthy
- **mocha-mousse** - Brown coffee tones, DM Sans font. Cozy café aesthetic
- **kodama-grove** - Forest green and earth tones, Merriweather font. Natural and grounded
- **solar-dusk** - Warm sunset oranges with Oxanium font. Desert twilight feel
- **vintage-paper** - Aged paper browns with serif fonts. Literary and classic

### Playful & Vibrant
- **t3-chat** - Pink chat-inspired theme. Social and friendly
- **pastel-dreams** - Soft pastel purples with large radius. Dreamy and gentle
- **midnight-bloom** - Deep purple nights with floral undertones
- **soft-pop** - Gentle pop colors with soft edges

### Cool & Calm
- **ocean-breeze** - Aqua blues for a fresh seaside feel
- **northern-lights** - Green and blue aurora-inspired colors. Arctic and ethereal

### Unique Styles
- **doom-64** - Dark red retro gaming theme. Classic FPS nostalgia
- **elegant-luxury** - Premium feel with refined color choices
- **sunset-horizon** - Gradient sunset colors from orange to purple
- **starry-night** - Deep space theme with star-like accents

## Features
- Next.js 14 with TypeScript, Tailwind CSS v3, App Router
- ALL shadcn UI components pre-installed
- 24 beautiful themes from tweakcn.com
- lucide-react and next-themes included
- Ready for immediate development