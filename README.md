# Malvid

[![Travis Build Status](https://travis-ci.org/Malvid/Malvid.svg?branch=master)](https://travis-ci.org/Malvid/Malvid) [![Coverage Status](https://coveralls.io/repos/github/comwrap/Malvid/badge.svg?branch=master)](https://coveralls.io/github/comwrap/Malvid?branch=master)  [![Dependencies](https://david-dm.org/comwrap/Malvid.svg)](https://david-dm.org/comwrap/Malvid#info=dependencies) [![Greenkeeper badge](https://badges.greenkeeper.io/Malvid/Malvid.svg)](https://greenkeeper.io/)

UI to help you build and document web components.

![Malvid UI in a browser](http://s.electerious.com/images/malvid/readme.png)

## Contents

- 🏃 [Get started](#get-started)
- 📄 [Introduction](#introduction)
- 🔗 [Links](#links)
- ⚙️ [Documentation](#documentation)

## Get started

### Guide

Malvid can be integrated into your project in two ways: Using the CLI *or* using the API of Malvid. Check out our guide for more information. [Get started with Malvid &#187;](docs/Get%20started.md)

### Demo

The website of [Malvid](https://malvid.io) is open-source and built entirely with Malvid. You can take a look at the components and how they are made in the [repository of the website](https://github.com/Malvid/website).

## Introduction

### What is Malvid?

Malvid helps you to build, document and visualise components by turning a directory into an interactive UI.

### How does it work?

1. You execute Malvid using the CLI *or* using the API
2. Malvid scans the folder you've specified and generates a static HTML output
3. You open the output in your browser to start browsing through your components

### Why Malvid?

- It visualises components in a way that improves how your team works with components
- It doesn't force you to use a defined directory structure, templating language or build tool
- It integrates perfectly with [Rosid](https://rosid.electerious.com)
- It's built on popular modules like [React](https://reactjs.org)
- It's lightweight and only includes what it really needs

### What are components?

Components are independent and reusable pieces of a project. A component could be a tiny chunk of HTML, a whole page or something in between. Malvid does not enforce any specific templating engine or naming conventions for those components.

## Links

Boilerplates:

- 📐 [Skeleton Components](https://github.com/electerious/Skeleton-Components): UI for components written in Nunjucks, JS (with Babel, UglifyJS) and SASS (with cssnano, Autoprefixer)

Guides:

- 📄 [Get started](docs/Get%20started.md)
- 📄 [Integrations](docs/Integrations.md)
- 📄 [Styleguide](docs/Styleguide.md)
- 📄 [Sharing components between front-end and back-end](https://medium.com/@electerious/sharing-components-between-front-end-and-back-end-1e9a624bceae)

Videos:

- 🎬🇩🇪 [Scalable Front-Ends with Web Components and Malvid](https://www.youtube.com/watch?v=4o-WHDXjNgo&index=8&list=LL5lfEWoNEhOh1SDcVlr37iQ&t=0s)

Similar tools:

- 🛠 [Fractal](https://fractal.build)
- 🛠 [Pattern Lab](http://patternlab.io)

Sites powered by Malvid:

- 🌍 [Malvid](https://malvid.io)
- 🌏 [Commerz Real AG](https://www.commerzreal.com)

## Documentation

### Requirements

Malvid depends on...

- [Node.js](https://nodejs.org/en/) (v8.9.0 or newer)
- [npm](https://www.npmjs.com)

Make sure to install and update all dependencies before you setup Malvid.

### Interface

The interface of Malvid puts the focus on your components. This chapter gives you an overview about it's possibilities. [Interface &#187;](docs/Interface.md)

### Hotkeys

Navigate through your components using the hotkeys provided by Malvid. [Hotkeys &#187;](docs/Hotkeys.md)

### API

Malvid can be integrated into your project using its API *or* CLI. The API gives you more flexibility and allows you to use Malvid in your existing asset pipeline or toolset. [API &#187;](docs/API.md)

### CLI

The CLI of Malvid is located in the `bin` folder and allows you to run Malvid without adding JS files to your project. This approach is simpler than using the API, but provides less flexibility. [CLI &#187;](docs/CLI.md)

### Components

Malvid scans folders and detects all components in the given structure. This chapter explains how to store and manage components and how to add additional information to the UI using a configuration file. [Components &#187;](docs/Components.md)

### Integrations

The API of Malvid allows you to use your existing asset pipeline or toolset together with Malvid. This includes Rosid, Gulp, NPM scripts and other systems. [Integrations &#187;](docs/Integrations.md)

### Options

If you want more control over Malvid, pass an object of options to it. [Options &#187;](docs/Options.md)

### FAQ

Answers to frequently asked questions. [FAQ &#187;](docs/FAQ.md)
