# Figma Plugin - Svelte TypeScript

## Introduction

This repository contains the source code for a Figma plugin developed using Svelte and TypeScript. The plugin enhances the Figma experience with its features. Feel free to explore the codebase and contribute to its development.

## Getting Started

To get started with the development or testing of this Figma plugin, follow the steps below:

1. **Clone this repository:**
   
   ```bash
   https://github.com/Azkii/figma-plugin-svelte-ts
   ```

2. **Install dependencies:**
   
   ```bash
   npm install
   ```
   
3. **Run the development server:**
   
   ```bash
   npm run watch
   ```

4. **Open Figma and load the plugin:**
  - Open Figma.
  - Go to the Plugins menu.
  - Select 'Development' and choose 'Create a plugin...'
  - Choose 'Link existing plugin' and select the manifest.json file in the public directory of this repository.

## Available Scripts
- `watch`: Concurrently runs the Vite development server, and TypeScript and Terser for automatic code compilation and minification.
- `web`: Starts the Vite development server.
- `ui-build`: Builds the UI using Vite in watch mode.
- `controller-build`: Builds the TypeScript controller and minifies it using Terser.
- `analyze-bundle`: Generates a bundle visualization using Vite Bundle Visualizer.

`Feel free to customize and extend the scripts based on your development needs.`


