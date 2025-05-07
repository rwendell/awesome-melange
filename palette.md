# Melange Palette

## Introduction

Melange is a warm color scheme for Neovim and beyond. It was designed with one core idea in mind: **Control flow should use warm colors and data should use cold colors.**

This document outlines the color palette used in Melange for both its dark and light variants, and how these colors are applied to various highlight groups. The color definitions are primarily sourced from `lua/melange/palettes/dark.lua` and `lua/melange/palettes/light.lua`.

The palette is generally structured into four groups:
* `a`: Base UI colors and grays.
* `b`: Bright foreground colors.
* `c`: Regular foreground colors.
* `d`: Background accent colors (often for diffs, special states).

## Principles

* **Warm Control Flow:** Keywords, functions, and control structures are generally assigned warmer colors.
* **Cold Data:** Variables, strings, numbers, and data structures are typically assigned cooler colors.
* **Clarity and Comfort:** The colors are chosen to be easy on the eyes while providing clear differentiation between syntax elements.

## Palette Definition

You will need to retrieve the specific hex codes from the following files in the `melange-nvim` repository:
* `lua/melange/palettes/dark.lua`
* `lua/melange/palettes/light.lua`

For each color below:
1. Replace the text placeholder (e.g., `#<a.fg_dark>`) with the actual hex value (e.g., `#C5C8C6`).
2. Replace the URL placeholder (e.g., `__A_FG_DARK_HEX__`) with the hex value *without* the leading `#` (e.g., `C5C8C6`).

---

### Dark Variant Palette

*(Sourced from `lua/melange/palettes/dark.lua`)*

* **Group `a` (Base UI / Grays):**
    * `a.fg` (Default Foreground): `#<a.fg_dark>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__A_FG_DARK_HEX__)
    * `a.bg` (Default Background): `#<a.bg_dark>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__A_BG_DARK_HEX__)
    * `a.com` (Comments / Muted Foreground): `#<a.com_dark>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__A_COM_DARK_HEX__)
    * `a.ui` (UI Elements / Borders): `#<a.ui_dark>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__A_UI_DARK_HEX__)
    * `a.sel` (Selection Background / UI Accent): `#<a.sel_dark>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__A_SEL_DARK_HEX__)
    * `a.float` (Floating Window Background): `#<a.float_dark>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__A_FLOAT_DARK_HEX__)
* **Group `b` (Bright Foreground Colors):**
    * `b.red`: `#<b.red_dark>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__B_RED_DARK_HEX__)
    * `b.green`: `#<b.green_dark>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__B_GREEN_DARK_HEX__)
    * `b.yellow`: `#<b.yellow_dark>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__B_YELLOW_DARK_HEX__)
    * `b.blue`: `#<b.blue_dark>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__B_BLUE_DARK_HEX__)
    * `b.magenta`: `#<b.magenta_dark>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__B_MAGENTA_DARK_HEX__)
    * `b.cyan`: `#<b.cyan_dark>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__B_CYAN_DARK_HEX__)
* **Group `c` (Regular Foreground Colors):**
    * `c.red`: `#<c.red_dark>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__C_RED_DARK_HEX__)
    * `c.green`: `#<c.green_dark>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__C_GREEN_DARK_HEX__)
    * `c.yellow`: `#<c.yellow_dark>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__C_YELLOW_DARK_HEX__)
    * `c.blue`: `#<c.blue_dark>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__C_BLUE_DARK_HEX__)
    * `c.magenta`: `#<c.magenta_dark>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__C_MAGENTA_DARK_HEX__)
    * `c.cyan`: `#<c.cyan_dark>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__C_CYAN_DARK_HEX__)
* **Group `d` (Background Accent Colors):**
    * `d.red`: `#<d.red_dark>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__D_RED_DARK_HEX__)
    * `d.green`: `#<d.green_dark>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__D_GREEN_DARK_HEX__)
    * `d.yellow`: `#<d.yellow_dark>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__D_YELLOW_DARK_HEX__)
    * `d.blue`: `#<d.blue_dark>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__D_BLUE_DARK_HEX__)
    * `d.magenta`: `#<d.magenta_dark>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__D_MAGENTA_DARK_HEX__)
    * `d.cyan`: `#<d.cyan_dark>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__D_CYAN_DARK_HEX__)

---

### Light Variant Palette

*(Sourced from `lua/melange/palettes/light.lua`)*

* **Group `a` (Base UI / Grays):**
    * `a.fg` (Default Foreground): `#<a.fg_light>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__A_FG_LIGHT_HEX__)
    * `a.bg` (Default Background): `#<a.bg_light>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__A_BG_LIGHT_HEX__)
    * `a.com` (Comments / Muted Foreground): `#<a.com_light>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__A_COM_LIGHT_HEX__)
    * `a.ui` (UI Elements / Borders): `#<a.ui_light>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__A_UI_LIGHT_HEX__)
    * `a.sel` (Selection Background / UI Accent): `#<a.sel_light>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__A_SEL_LIGHT_HEX__)
    * `a.float` (Floating Window Background): `#<a.float_light>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__A_FLOAT_LIGHT_HEX__)
* **Group `b` (Bright Foreground Colors):**
    * `b.red`: `#<b.red_light>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__B_RED_LIGHT_HEX__)
    * `b.green`: `#<b.green_light>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__B_GREEN_LIGHT_HEX__)
    * `b.yellow`: `#<b.yellow_light>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__B_YELLOW_LIGHT_HEX__)
    * `b.blue`: `#<b.blue_light>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__B_BLUE_LIGHT_HEX__)
    * `b.magenta`: `#<b.magenta_light>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__B_MAGENTA_LIGHT_HEX__)
    * `b.cyan`: `#<b.cyan_light>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__B_CYAN_LIGHT_HEX__)
* **Group `c` (Regular Foreground Colors):**
    * `c.red`: `#<c.red_light>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__C_RED_LIGHT_HEX__)
    * `c.green`: `#<c.green_light>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__C_GREEN_LIGHT_HEX__)
    * `c.yellow`: `#<c.yellow_light>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__C_YELLOW_LIGHT_HEX__)
    * `c.blue`: `#<c.blue_light>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__C_BLUE_LIGHT_HEX__)
    * `c.magenta`: `#<c.magenta_light>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__C_MAGENTA_LIGHT_HEX__)
    * `c.cyan`: `#<c.cyan_light>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__C_CYAN_LIGHT_HEX__)
* **Group `d` (Background Accent Colors):**
    * `d.red`: `#<d.red_light>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__D_RED_LIGHT_HEX__)
    * `d.green`: `#<d.green_light>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__D_GREEN_LIGHT_HEX__)
    * `d.yellow`: `#<d.yellow_light>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__D_YELLOW_LIGHT_HEX__)
    * `d.blue`: `#<d.blue_light>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__D_BLUE_LIGHT_HEX__)
    * `d.magenta`: `#<d.magenta_light>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__D_MAGENTA_LIGHT_HEX__)
    * `d.cyan`: `#<d.cyan_light>` ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__D_CYAN_LIGHT_HEX__)

---

## Terminal Colors

Melange sets the following 16 terminal colors. These correspond to the `vim.g.terminal_color_X` variables.

*(Color variables refer to the values from the active (dark/light) palette. Replace placeholders as instructed above.)*

| Terminal Color ID | Melange Palette Key | Hex Placeholder (Dark) | Image (Dark)                                                                     | Hex Placeholder (Light) | Image (Light)                                                                      |
|-------------------|---------------------|------------------------|----------------------------------------------------------------------------------|-------------------------|------------------------------------------------------------------------------------|
| `terminal_color_0`  | `a.float`           | `#<a.float_dark>`      | ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__A_FLOAT_DARK_HEX__)      | `#<a.float_light>`      | ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__A_FLOAT_LIGHT_HEX__)      |
| `terminal_color_1`  | `c.red`             | `#<c.red_dark>`        | ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__C_RED_DARK_HEX__)        | `#<c.red_light>`        | ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__C_RED_LIGHT_HEX__)        |
| `terminal_color_2`  | `c.green`           | `#<c.green_dark>`      | ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__C_GREEN_DARK_HEX__)      | `#<c.green_light>`      | ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__C_GREEN_LIGHT_HEX__)      |
| `terminal_color_3`  | `c.yellow`          | `#<c.yellow_dark>`     | ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__C_YELLOW_DARK_HEX__)     | `#<c.yellow_light>`     | ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__C_YELLOW_LIGHT_HEX__)     |
| `terminal_color_4`  | `c.blue`            | `#<c.blue_dark>`       | ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__C_BLUE_DARK_HEX__)       | `#<c.blue_light>`       | ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__C_BLUE_LIGHT_HEX__)       |
| `terminal_color_5`  | `c.magenta`         | `#<c.magenta_dark>`    | ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__C_MAGENTA_DARK_HEX__)    | `#<c.magenta_light>`    | ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__C_MAGENTA_LIGHT_HEX__)    |
| `terminal_color_6`  | `c.cyan`            | `#<c.cyan_dark>`       | ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__C_CYAN_DARK_HEX__)       | `#<c.cyan_light>`       | ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__C_CYAN_LIGHT_HEX__)       |
| `terminal_color_7`  | `a.com`             | `#<a.com_dark>`        | ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__A_COM_DARK_HEX__)        | `#<a.com_light>`        | ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__A_COM_LIGHT_HEX__)        |
| `terminal_color_8`  | `a.ui`              | `#<a.ui_dark>`         | ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__A_UI_DARK_HEX__)         | `#<a.ui_light>`         | ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__A_UI_LIGHT_HEX__)         |
| `terminal_color_9`  | `b.red`             | `#<b.red_dark>`        | ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__B_RED_DARK_HEX__)        | `#<b.red_light>`        | ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__B_RED_LIGHT_HEX__)        |
| `terminal_color_10` | `b.green`           | `#<b.green_dark>`      | ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__B_GREEN_DARK_HEX__)      | `#<b.green_light>`      | ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__B_GREEN_LIGHT_HEX__)      |
| `terminal_color_11` | `b.yellow`          | `#<b.yellow_dark>`     | ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__B_YELLOW_DARK_HEX__)     | `#<b.yellow_light>`     | ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__B_YELLOW_LIGHT_HEX__)     |
| `terminal_color_12` | `b.blue`            | `#<b.blue_dark>`       | ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__B_BLUE_DARK_HEX__)       | `#<b.blue_light>`       | ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__B_BLUE_LIGHT_HEX__)       |
| `terminal_color_13` | `b.magenta`         | `#<b.magenta_dark>`    | ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__B_MAGENTA_DARK_HEX__)    | `#<b.magenta_light>`    | ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__B_MAGENTA_LIGHT_HEX__)    |
| `terminal_color_14` | `b.cyan`            | `#<b.cyan_dark>`       | ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__B_CYAN_DARK_HEX__)       | `#<b.cyan_light>`       | ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__B_CYAN_LIGHT_HEX__)       |
| `terminal_color_15` | `a.fg`              | `#<a.fg_dark>`         | ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__A_FG_DARK_HEX__)         | `#<a.fg_light>`         | ![Swatch](https://www.thecolorapi.com/id?format=svg&named=false&hex=__A_FG_LIGHT_HEX__)         |


*This `palette.md` is inspired by the structure of the Everforest colorscheme's palette documentation and generated with the help of the Melange highlight definitions.*
