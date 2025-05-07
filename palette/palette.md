# Melange Palette

## Introduction

Melange is a warm color scheme for Neovim and beyond. It was designed with one core idea in mind: **Control flow should use warm colors and data should use cold colors.**

This document outlines the color palette used in Melange for both its dark and light variants, based on the provided color definitions.

The palette for UI and syntax highlighting within Neovim is often structured into logical groups (referred to as `a`, `b`, `c`, `d` in the theme's internal scripts). The 16 base terminal colors are also explicitly defined.

## Principles

* **Warm Control Flow:** Keywords, functions, and control structures are generally assigned warmer colors.
* **Cold Data:** Variables, strings, numbers, and data structures are typically assigned cooler colors.
* **Clarity and Comfort:** The colors are chosen to be easy on the eyes while providing clear differentiation between syntax elements.

## Palette Definition (for Neovim UI and Syntax)

The following colors are mapped to the `a, b, c, d` structure that `melange-nvim`'s Lua highlighting scripts use.

---

### Dark Variant Palette (Mapped)

**Group `a` (Base UI / Grays)**

| Key   | Description                     | Hex Value | Swatch                                                                     |
|-------|---------------------------------|-----------|----------------------------------------------------------------------------|
| `fg`  | Default Foreground              | `#ECE1D7` | ![#ECE1D7](https://www.thecolorapi.com/id?format=svg&named=false&hex=ECE1D7) |
| `bg`  | Default Background              | `#292522` | ![#292522](https://www.thecolorapi.com/id?format=svg&named=false&hex=292522) |
| `com` | Comments / Muted Foreground     | `#867462` | ![#867462](https://www.thecolorapi.com/id?format=svg&named=false&hex=867462) |
| `ui`  | UI Elements / Borders           | `#403A36` | ![#403A36](https://www.thecolorapi.com/id?format=svg&named=false&hex=403A36) |
| `sel` | Selection Background / UI Accent| `#34302C` | ![#34302C](https://www.thecolorapi.com/id?format=svg&named=false&hex=34302C) |
| `float`| Floating Window Background     | `#34302C` | ![#34302C](https://www.thecolorapi.com/id?format=svg&named=false&hex=34302C) |

**Group `b` (Bright Foreground Colors)**

| Color Name      | Hex Value | Swatch                                                                     |
|-----------------|-----------|----------------------------------------------------------------------------|
| Red (`b.red`)   | `#D47766` | ![#D47766](https://www.thecolorapi.com/id?format=svg&named=false&hex=D47766) |
| Green (`b.green`)| `#85B695` | ![#85B695](https://www.thecolorapi.com/id?format=svg&named=false&hex=85B695) |
| Yellow (`b.yellow`)|`#EBC06D` | ![#EBC06D](https://www.thecolorapi.com/id?format=svg&named=false&hex=EBC06D) |
| Blue (`b.blue`) | `#A3A9CE` | ![#A3A9CE](https://www.thecolorapi.com/id?format=svg&named=false&hex=A3A9CE) |
| Magenta (`b.magenta`)|`#CF9BC2` | ![#CF9BC2](https://www.thecolorapi.com/id?format=svg&named=false&hex=CF9BC2) |
| Cyan (`b.cyan`) | `#89B3B6` | ![#89B3B6](https://www.thecolorapi.com/id?format=svg&named=false&hex=89B3B6) |

**Group `c` (Regular Foreground Colors)**

| Color Name      | Hex Value | Swatch                                                                     |
|-----------------|-----------|----------------------------------------------------------------------------|
| Red (`c.red`)   | `#BD8183` | ![#BD8183](https://www.thecolorapi.com/id?format=svg&named=false&hex=BD8183) |
| Green (`c.green`)| `#78997A` | ![#78997A](https://www.thecolorapi.com/id?format=svg&named=false&hex=78997A) |
| Yellow (`c.yellow`)|`#E49B5D` | ![#E49B5D](https://www.thecolorapi.com/id?format=svg&named=false&hex=E49B5D) |
| Blue (`c.blue`) | `#7F91B2` | ![#7F91B2](https://www.thecolorapi.com/id?format=svg&named=false&hex=7F91B2) |
| Magenta (`c.magenta`)|`#B380B0` | ![#B380B0](https://www.thecolorapi.com/id?format=svg&named=false&hex=B380B0) |
| Cyan (`c.cyan`) | `#7B9695` | ![#7B9695](https://www.thecolorapi.com/id?format=svg&named=false&hex=7B9695) |

**Group `d` (Background Accent Colors)**

| Color Name      | Hex Value | Swatch                                                                     |
|-----------------|-----------|----------------------------------------------------------------------------|
| Red (`d.red`)   | `#7D2A2F` | ![#7D2A2F](https://www.thecolorapi.com/id?format=svg&named=false&hex=7D2A2F) |
| Green (`d.green`)| `#233524` | ![#233524](https://www.thecolorapi.com/id?format=svg&named=false&hex=233524) |
| Yellow (`d.yellow`)|`#8B7449` | ![#8B7449](https://www.thecolorapi.com/id?format=svg&named=false&hex=8B7449) |
| Blue (`d.blue`) | `#273142` | ![#273142](https://www.thecolorapi.com/id?format=svg&named=false&hex=273142) |
| Magenta (`d.magenta`)|`#422741` | ![#422741](https://www.thecolorapi.com/id?format=svg&named=false&hex=422741) |
| Cyan (`d.cyan`) | `#253333` | ![#253333](https://www.thecolorapi.com/id?format=svg&named=false&hex=253333) |

---

### Light Variant Palette (Mapped)

**Group `a` (Base UI / Grays)**

| Key   | Description                     | Hex Value | Swatch                                                                     |
|-------|---------------------------------|-----------|----------------------------------------------------------------------------|
| `fg`  | Default Foreground              | `#54433A` | ![#54433A](https://www.thecolorapi.com/id?format=svg&named=false&hex=54433A) |
| `bg`  | Default Background              | `#F1F1F1` | ![#F1F1F1](https://www.thecolorapi.com/id?format=svg&named=false&hex=F1F1F1) |
| `com` | Comments / Muted Foreground     | `#7D6658` | ![#7D6658](https://www.thecolorapi.com/id?format=svg&named=false&hex=7D6658) |
| `ui`  | UI Elements / Borders           | `#A98A78` | ![#A98A78](https://www.thecolorapi.com/id?format=svg&named=false&hex=A98A78) |
| `sel` | Selection Background / UI Accent| `#D9D3CE` | ![#D9D3CE](https://www.thecolorapi.com/id?format=svg&named=false&hex=D9D3CE) |
| `float`| Floating Window Background     | `#E9E1DB` | ![#E9E1DB](https://www.thecolorapi.com/id?format=svg&named=false&hex=E9E1DB) |

**Group `b` (Bright Foreground Colors)**

| Color Name      | Hex Value | Swatch                                                                     |
|-----------------|-----------|----------------------------------------------------------------------------|
| Red (`b.red`)   | `#BF0021` | ![#BF0021](https://www.thecolorapi.com/id?format=svg&named=false&hex=BF0021) |
| Green (`b.green`)| `#3A684A` | ![#3A684A](https://www.thecolorapi.com/id?format=svg&named=false&hex=3A684A) |
| Yellow (`b.yellow`)|`#A06D00` | ![#A06D00](https://www.thecolorapi.com/id?format=svg&named=false&hex=A06D00) |
| Blue (`b.blue`) | `#465AA4` | ![#465AA4](https://www.thecolorapi.com/id?format=svg&named=false&hex=465AA4) |
| Magenta (`b.magenta`)|`#904180` | ![#904180](https://www.thecolorapi.com/id?format=svg&named=false&hex=904180) |
| Cyan (`b.cyan`) | `#3D6568` | ![#3D6568](https://www.thecolorapi.com/id?format=svg&named=false&hex=3D6568) |

**Group `c` (Regular Foreground Colors)**

| Color Name      | Hex Value | Swatch                                                                     |
|-----------------|-----------|----------------------------------------------------------------------------|
| Red (`c.red`)   | `#C77B8B` | ![#C77B8B](https://www.thecolorapi.com/id?format=svg&named=false&hex=C77B8B) |
| Green (`c.green`)| `#6E9B72` | ![#6E9B72](https://www.thecolorapi.com/id?format=svg&named=false&hex=6E9B72) |
| Yellow (`c.yellow`)|`#BC5C00` | ![#BC5C00](https://www.thecolorapi.com/id?format=svg&named=false&hex=BC5C00) |
| Blue (`c.blue`) | `#7892BD` | ![#7892BD](https://www.thecolorapi.com/id?format=svg&named=false&hex=7892BD) |
| Magenta (`c.magenta`)|`#BE79BB` | ![#BE79BB](https://www.thecolorapi.com/id?format=svg&named=false&hex=BE79BB) |
| Cyan (`c.cyan`) | `#739797` | ![#739797](https://www.thecolorapi.com/id?format=svg&named=false&hex=739797) |

**Group `d` (Background Accent Colors)**

| Color Name      | Hex Value | Swatch                                                                     |
|-----------------|-----------|----------------------------------------------------------------------------|
| Red (`d.red`)   | `#F1DEDF` | ![#F1DEDF](https://www.thecolorapi.com/id?format=svg&named=false&hex=F1DEDF) |
| Green (`d.green`)| `#D0E9D1` | ![#D0E9D1](https://www.thecolorapi.com/id?format=svg&named=false&hex=D0E9D1) |
| Yellow (`d.yellow`)|`#CCA478` | ![#CCA478](https://www.thecolorapi.com/id?format=svg&named=false&hex=CCA478) |
| Blue (`d.blue`) | `#E0E2E8` | ![#E0E2E8](https://www.thecolorapi.com/id?format=svg&named=false&hex=E0E2E8) |
| Magenta (`d.magenta`)|`#E8E0E8` | ![#E8E0E8](https://www.thecolorapi.com/id?format=svg&named=false&hex=E8E0E8) |
| Cyan (`d.cyan`) | `#CDE8E7` | ![#CDE8E7](https://www.thecolorapi.com/id?format=svg&named=false&hex=CDE8E7) |

---

## Terminal Colors (16 ANSI Colors)

These are the 16 standard terminal colors as defined in the provided Melange palettes.

### Dark Variant Terminal Colors

| Name            | Hex       | Image Swatch                                                               |
|-----------------|-----------|----------------------------------------------------------------------------|
| Black           | `#34302C` | ![#34302C](https://www.thecolorapi.com/id?format=svg&named=false&hex=34302C) |
| Red             | `#BD8183` | ![#BD8183](https://www.thecolorapi.com/id?format=svg&named=false&hex=BD8183) |
| Green           | `#78997A` | ![#78997A](https://www.thecolorapi.com/id?format=svg&named=false&hex=78997A) |
| Yellow          | `#E49B5D` | ![#E49B5D](https://www.thecolorapi.com/id?format=svg&named=false&hex=E49B5D) |
| Blue            | `#7F91B2` | ![#7F91B2](https://www.thecolorapi.com/id?format=svg&named=false&hex=7F91B2) |
| Magenta         | `#B380B0` | ![#B380B0](https://www.thecolorapi.com/id?format=svg&named=false&hex=B380B0) |
| Cyan            | `#7B9695` | ![#7B9695](https://www.thecolorapi.com/id?format=svg&named=false&hex=7B9695) |
| White           | `#C1A78E` | ![#C1A78E](https://www.thecolorapi.com/id?format=svg&named=false&hex=C1A78E) |
| Bright Black    | `#867462` | ![#867462](https://www.thecolorapi.com/id?format=svg&named=false&hex=867462) |
| Bright Red      | `#D47766` | ![#D47766](https://www.thecolorapi.com/id?format=svg&named=false&hex=D47766) |
| Bright Green    | `#85B695` | ![#85B695](https://www.thecolorapi.com/id?format=svg&named=false&hex=85B695) |
| Bright Yellow   | `#EBC06D` | ![#EBC06D](https://www.thecolorapi.com/id?format=svg&named=false&hex=EBC06D) |
| Bright Blue     | `#A3A9CE` | ![#A3A9CE](https://www.thecolorapi.com/id?format=svg&named=false&hex=A3A9CE) |
| Bright Magenta  | `#CF9BC2` | ![#CF9BC2](https://www.thecolorapi.com/id?format=svg&named=false&hex=CF9BC2) |
| Bright Cyan     | `#89B3B6` | ![#89B3B6](https://www.thecolorapi.com/id?format=svg&named=false&hex=89B3B6) |
| Bright White    | `#ECE1D7` | ![#ECE1D7](https://www.thecolorapi.com/id?format=svg&named=false&hex=ECE1D7) |

### Light Variant Terminal Colors

| Name            | Hex       | Image Swatch                                                               |
|-----------------|-----------|----------------------------------------------------------------------------|
| Black           | `#E9E1DB` | ![#E9E1DB](https://www.thecolorapi.com/id?format=svg&named=false&hex=E9E1DB) |
| Red             | `#C77B8B` | ![#C77B8B](https://www.thecolorapi.com/id?format=svg&named=false&hex=C77B8B) |
| Green           | `#6E9B72` | ![#6E9B72](https://www.thecolorapi.com/id?format=svg&named=false&hex=6E9B72) |
| Yellow          | `#BC5C00` | ![#BC5C00](https://www.thecolorapi.com/id?format=svg&named=false&hex=BC5C00) |
| Blue            | `#7892BD` | ![#7892BD](https://www.thecolorapi.com/id?format=svg&named=false&hex=7892BD) |
| Magenta         | `#BE79BB` | ![#BE79BB](https://www.thecolorapi.com/id?format=svg&named=false&hex=BE79BB) |
| Cyan            | `#739797` | ![#739797](https://www.thecolorapi.com/id?format=svg&named=false&hex=739797) |
| White           | `#7D6658` | ![#7D6658](https://www.thecolorapi.com/id?format=svg&named=false&hex=7D6658) |
| Bright Black    | `#A98A78` | ![#A98A78](https://www.thecolorapi.com/id?format=svg&named=false&hex=A98A78) |
| Bright Red      | `#BF0021` | ![#BF0021](https://www.thecolorapi.com/id?format=svg&named=false&hex=BF0021) |
| Bright Green    | `#3A684A` | ![#3A684A](https://www.thecolorapi.com/id?format=svg&named=false&hex=3A684A) |
| Bright Yellow   | `#A06D00` | ![#A06D00](https://www.thecolorapi.com/id?format=svg&named=false&hex=A06D00) |
| Bright Blue     | `#465AA4` | ![#465AA4](https://www.thecolorapi.com/id?format=svg&named=false&hex=465AA4) |
| Bright Magenta  | `#904180` | ![#904180](https://www.thecolorapi.com/id?format=svg&named=false&hex=904180) |
| Bright Cyan     | `#3D6568` | ![#3D6568](https://www.thecolorapi.com/id?format=svg&named=false&hex=3D6568) |
| Bright White    | `#54433A` | ![#54433A](https://www.thecolorapi.com/id?format=svg&named=false&hex=54433A) |

---

*This `palette.md` structure is inspired by the Everforest colorscheme's palette documentation and populated with the provided Melange color values.*
