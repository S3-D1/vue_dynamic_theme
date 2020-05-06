# vue_dynamic_theme
This project is just a demonstrator for a dynamic theme rendering mechanism.

## Table of Contents

- [UseCase](#usecase)
- [Project setup](#project-setup)
- [How to use](#how-to-use)
- [Tasks](#tasks)

## UseCase
- Design a layout only with placeholders for all colors
- Use default colors for all placeholders
- Provide a REST API for the theme
- Reload the page when a new scheme is provided

## Project setup
- https://vuejs.org/
- https://vuetifyjs.com/
- https://github.com/axios/axios
- https://vuex.vuejs.org/guide/

## How to use
Initial setup:
```
npm install
```

Run in development mode
```
npm run serve
```

Build for production
```
npm run build
```

Lint and fix files
```
npm run lint
```

## Tasks
[x] init vue app with vuetify
[] provide vuetify theme with all colors and custom properties
[] add a couple of design elements for representating the theme
[] add axios and theme endpoint
[] provide vuex store for the theme
[] implement the theme reload