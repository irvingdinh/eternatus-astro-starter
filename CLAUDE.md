# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Commands

### Development

- `pnpm dev` - Start the development server at http://localhost:4321
- `pnpm build` - Build the production site to `./dist/`
- `pnpm preview` - Preview the production build locally

### Package Management

- `pnpm install` - Install project dependencies

## Architecture

This is a minimal Astro starter project configured with Tailwind CSS v4 using the Vite plugin approach.

### Key Technologies

- **Astro** - Static site generator framework
- **Tailwind CSS v4** - Configured via @tailwindcss/vite plugin in astro.config.mjs
- **TypeScript** - Strict configuration enabled

### Project Structure

- `src/pages/` - Astro pages that define routes (file-based routing)
- `src/styles/` - Global CSS files including Tailwind imports
- `public/` - Static assets served directly
- `astro.config.mjs` - Astro configuration with Vite plugin setup

### Build System

- Uses pnpm as the package manager with workspace configuration
- Vite as the underlying build tool
- TypeScript with strict mode enabled
