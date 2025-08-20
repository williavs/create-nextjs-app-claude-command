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

Built for Claude Code but works standalone.