# Electron Vue Template

A template that comes with an Electron application bundled with VueJS 3.

## Why?

This project got inspired by [electron-vue](https://github.com/SimulatedGREG/electron-vue). Sadly, the project is not being maintained anymore.

electron-vue-template uses updated Electron/Vue versions and build tools! 👍 The idea of this template is to keep it really simple Electron application without an unnecessary amount of dependency overhead.

## About

This template uses [ViteJS](https://vitejs.dev) for the development server providing HMR (Hot Reload) while developing your Electron app.\
Building the Electron application is done by [Electron Builder](https://www.electron.build/), making your application cross-platform and easily distributable.

This template doesn't come with any unnecessary dependencies and is unopinionated, so you can start developing your Electron / Vue applications however you want.

## Get Started

To start developing your Electron application execute the following commands:

```bash
git clone https://github.com/Deluze/electron-vue-template
cd electron-vue-template
npm install
npm run dev
```

That's all!

## Commands

This template only comes with 2 necessary commands:

```bash
npm run dev # start Electron application and ViteJS devserver for development
npm run build # builds the renderer with ViteJS and compiles it with Electron Builder
```

## Project Structure

```bash
- root
  - config/
    - vite.js # ViteJS configuration
    - electron-builder.js # Electron Builder configuration
  - scripts/ # all the scripts used to build or serve your application, change as you like.
  - src/
    - main/ # Main thread (Electron application source)
    - renderer/ # Renderer thread (VueJS application source)
```
