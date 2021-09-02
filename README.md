# EpicSwap UIkit

[![Version](https://img.shields.io/npm/v/flydex-uikit)](https://www.npmjs.com/package/flydex-uikit) [![Size](https://img.shields.io/bundlephobia/min/flydex-uikit)](https://www.npmjs.com/package/flydex-uikit)

EpicSwap UIkit is a set of React components and hooks used to build pages on EpicSwap's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add flydex-uikit`

## Setup

### Theme

Before using Pancake UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from 'flydex-uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from 'flydex-uikit'
...
<ResetCSS />
```

### Types

This project is built with Typescript and export all the relevant types.

