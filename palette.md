# Melange Palette

## Introduction

Melange is a warm color scheme for Neovim and beyond. It was designed with one core idea in mind: **Control flow should use warm colors and data should use cold colors.**

This document outlines the color palette used in Melange for both its dark and light variants.

## Principles

* **Warm Control Flow:** Keywords, functions, and control structures are generally assigned warmer colors (e.g., yellows, oranges, reds).
* **Cold Data:** Variables, strings, numbers, and data structures are typically assigned cooler colors (e.g., blues, greens, cyans).
* **Clarity and Comfort:** The colors are chosen to be easy on the eyes while providing clear differentiation between syntax elements.

## Palette

Melange offers distinct palettes for its dark and light themes.

---

### Dark Variant

The dark variant is the default and uses a darker background with contrasting foreground and accent colors.

#### Base Colors

* **Backgrounds:**
    * `bg` (Primary Background): `#<hex_code_bg>` (e.g., editor background)
    * `bg_alt` (Alternative Background): `#<hex_code_bg_alt>` (e.g., statusline, popups)
    * `bg_visual` (Visual Selection Background): `#<hex_code_bg_visual>`
    * `bg_sidebar` (Sidebar/BufferList Background): `#<hex_code_bg_sidebar>`
* **Foregrounds:**
    * `fg` (Primary Foreground): `#<hex_code_fg>` (e.g., default text)
    * `fg_alt` (Alternative Foreground): `#<hex_code_fg_alt>` (e.g., less important text, comments)
    * `fg_strong` (Stronger Foreground): `#<hex_code_fg_strong>`

#### Accent Colors (Grays, Primaries, etc.)

* **Grays:**
    * `grey0`: `#<hex_code_grey0>`
    * `grey1`: `#<hex_code_grey1>`
    * `grey2`: `#<hex_code_grey2>`
    * ... (add as many as defined)
* **Warm Colors (Control Flow & Emphasis):**
    * `red`: `#<hex_code_red>`
    * `orange`: `#<hex_code_orange>`
    * `yellow`: `#<hex_code_yellow>`
    * `warm_accent1` (e.g., for specific keywords): `#<hex_code_warm_accent1>`
* **Cold Colors (Data & General Syntax):**
    * `green`: `#<hex_code_green>`
    * `cyan`: `#<hex_code_cyan>`
    * `blue`: `#<hex_code_blue>`
    * `purple` (or `magenta`): `#<hex_code_purple>`
    * `cold_accent1` (e.g., for strings or numbers): `#<hex_code_cold_accent1>`

---

### Light Variant

The light variant uses a lighter background, providing an alternative for users who prefer light themes.

#### Base Colors

* **Backgrounds:**
    * `bg` (Primary Background): `#<hex_code_light_bg>`
    * `bg_alt` (Alternative Background): `#<hex_code_light_bg_alt>`
    * `bg_visual` (Visual Selection Background): `#<hex_code_light_bg_visual>`
    * `bg_sidebar` (Sidebar/BufferList Background): `#<hex_code_light_bg_sidebar>`
* **Foregrounds:**
    * `fg` (Primary Foreground): `#<hex_code_light_fg>`
    * `fg_alt` (Alternative Foreground): `#<hex_code_light_fg_alt>`
    * `fg_strong` (Stronger Foreground): `#<hex_code_light_fg_strong>`

#### Accent Colors (Grays, Primaries, etc.)

* **Grays:**
    * `grey0`: `#<hex_code_light_grey0>`
    * `grey1`: `#<hex_code_light_grey1>`
    * `grey2`: `#<hex_code_light_grey2>`
    * ... (add as many as defined)
* **Warm Colors (Control Flow & Emphasis):**
    * `red`: `#<hex_code_light_red>`
    * `orange`: `#<hex_code_light_orange>`
    * `yellow`: `#<hex_code_light_yellow>`
    * `warm_accent1`: `#<hex_code_light_warm_accent1>`
* **Cold Colors (Data & General Syntax):**
    * `green`: `#<hex_code_light_green>`
    * `cyan`: `#<hex_code_light_cyan>`
    * `blue`: `#<hex_code_light_blue>`
    * `purple` (or `magenta`): `#<hex_code_light_purple>`
    * `cold_accent1`: `#<hex_code_light_cold_accent1>`

---

## Syntax Highlighting Groups (Conceptual Mapping)

This section provides a general idea of how the palette colors are typically applied to common Neovim highlight groups. The actual implementation can be found in `lua/melange/highlights.lua` (or a similarly named file).

**Note:** The specific color names (e.g., `yellow`, `blue`) refer to the colors defined in the palettes above for the respective dark or light variant.

* **Comments:** `fg_alt` or a specific `grey`
* **Constants (Strings, Numbers, Booleans):** `green`, `cyan`, or `cold_accent1`
* **Identifiers (Variables):** `fg` or a subtle `cold_accent`
* **Functions (Definitions & Calls):** `yellow` or `orange`
* **Keywords (if, else, for, return, etc.):** `red`, `orange`, or `warm_accent1`
* **Types:** `yellow` or `cyan`
* **Operators:** `fg` or a subtle `warm_accent`
* **Statements (Keywords):** `red` or `purple`
* **Special Characters (e.g., Punctuation):** `fg` or a subtle `grey`
* **Errors:** A bright `red`
* **Warnings:** `orange` or `yellow`
* **Information:** `blue` or `cyan`
* **LSP Diagnostics (underline, virtual text):**
    * Error: `red`
    * Warning: `orange`
    * Info: `blue`
    * Hint: `cyan` or `grey`

## Terminal Colors

Melange also provides color schemes for various terminal emulators. These aim to match the Neovim theme for a cohesive experience. Refer to the `term/` directory in the Melange repository for specific configurations for terminals like Alacritty, Kitty, WezTerm, etc. The terminal colors will generally map to the core accent colors defined in the palettes.

Example mapping (actual colors will vary by dark/light theme):

* `black`: `bg_alt`
* `red`: `red`
* `green`: `green`
* `yellow`: `yellow`
* `blue`: `blue`
* `magenta`: `purple`
* `cyan`: `cyan`
* `white`: `fg`
* `bright_black`: `grey1` (or a darker grey)
* `bright_red`: A brighter shade of `red`
* `bright_green`: A brighter shade of `green`
* `bright_yellow`: A brighter shade of `yellow`
* `bright_blue`: A brighter shade of `blue`
* `bright_magenta`: A brighter shade of `purple`
* `bright_cyan`: A brighter shade of `cyan`
* `bright_white`: `fg_strong`

---

*This `palette.md` is inspired by the structure of the Everforest colorscheme's palette documentation.*
