# LX Search P1.5

Medicine search over 151 items. Each item shows its form, pack size, source and price.

## What it does

- Searches medicines and sources as you type. Esc clears the search.
- Groups items by route of use: All, Oral, Injectable, Inhaled and Topical or Liquid.
- Filters by pack size and by source.
- Shows the selected item as a large card with its price, and shows how many items match.

## What it does not do

- It is read-only. It has no editing, import or export, and it does not calculate prices.
- The 151 items are built into `index.html`. It does not fetch or update them.
- It keeps nothing in the browser.

## Network and install

Loads Font Awesome 6.4.2 from cdnjs and Google Fonts. It makes no other requests. Not installable; no service worker.

## Built with

One HTML file, with no build step and no framework. Font Awesome 6.4.2 supplies the icons.

## Run locally

Open `index.html` in a browser, or serve the folder with any static file server.
