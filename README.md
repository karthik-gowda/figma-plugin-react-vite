# Figma Plugin Template

This is a modern Figma plugin template built with React, TypeScript, and Tailwind CSS. It uses Vite for fast development and building, and includes UI components from shadcn/ui and Radix UI for beautifully designed, accessible components.

## Features

- ⚡️ **Vite** - Lightning fast build tool
- ⚛️ **React 18** - Modern UI development
- 🔷 **TypeScript** - Type safety and better developer experience
- 🎨 **Tailwind CSS** - Utility-first CSS framework
- 💅 **shadcn/ui** - Beautiful, accessible component system
- 📦 **Radix UI** - Accessible UI primitives
- 🔌 **Hot Reload** - Fast development with watch mode

## Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- Figma Desktop App

## Getting Started

1. Clone this repository
2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

4. To build the plugin:
   ```bash
   npm run build
   ```

## UI Components

This template uses [shadcn/ui](https://ui.shadcn.com/), a collection of beautifully designed and accessible components built with Radix UI and Tailwind CSS. Components are maintained in the `src/components/ui` directory and can be customized to match your design needs.

Available components:
- Accordion
- Button
- Card

To add more components, you can use the shadcn-ui CLI:
```bash
npx shadcn-ui@latest add [component-name]
```

## Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production (builds both UI and plugin code)
- `npm run build-ui` - Build only the UI
- `npm run build-code` - Build only the plugin code
- `npm run watch` - Watch mode for development

## Project Structure

- `src/` - Source code
  - `components/ui/` - shadcn/ui components
  - `lib/` - Utility functions
  - `App.tsx` - Main React application
  - `code.ts` - Figma plugin code
  - `main.tsx` - Entry point for the UI
  - `index.css` - Global styles
- `components.json` - shadcn/ui configuration

## Tech Stack

- [React](https://reactjs.org/)
- [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/)
- [shadcn/ui](https://ui.shadcn.com/)
- [Radix UI](https://www.radix-ui.com/)
- [Vite](https://vitejs.dev/)

## Development

The plugin uses a dual-build system:
- The UI code runs in an iframe within Figma
- The plugin code runs in Figma's plugin sandbox

When developing, you can use the watch mode to automatically rebuild both:
```bash
npm run watch
```

## Contributing

Feel free to submit issues and pull requests to improve the template.

## License

MIT License