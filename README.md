# Sublime Text 2 HTML Autocomplete

Sublime Text HTML Autocomplete is an incremental quality of life improvement for writing out HTML in Sublime Text 2. This updated file features a number of expansions for common libraries, adds some missing tags, adds/removes attributes, and adds/removes cursor tabs.

Please backup your original `html_completions.py` before replacing.

_No tests have been performed for compatibility with Sublime Text 3._

## Installation

Installation is as simple as replacing the corresponding `html_completions.py` file in the packages directory.

* Windows: `C:\Users\{user-name}\AppData\Roaming\Sublime Text 2\Packages\HTML`
* OS X: `/Users/{user-name}/Library/Application Support/Sublime Text 2/Packages/HTML`
* Linux: `Good luck, God speed.`

## Features
### New Tags:
* `<doctype>` expands to a full HTML document including: doctype, html, head, body, jQuery CDN, and style/javascript placeholders.
* `<bootstrap>` expands to include: jQuery 2.1.4 CDN, Bootstrap stylesheet CDN, Bootstrap javascript CDN.
* `<jquery>` expands to include jQuery 2.1.4 CDN.

### Updated Tags:
* `<html>` now self-closes.
* `<div>` now includes a `class` attribute.
* `<img>` now includes an `alt` attribute.
* `<script>` no longer selects `text/javascript` on auto-complete. Instead, places cursor inside `src` attribute.
* `<style>` no longer selects `text/css` on auto-complete. Instead places cursor inside `style` body.