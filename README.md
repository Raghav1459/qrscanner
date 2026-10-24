# Juniper House digital menu

A static, mobile-friendly restaurant menu with separate Veg, Non Veg, and Dessert sections, dish search, serving sizes, prices, and nutrition values. The **Get the menu QR** dialog creates a downloadable QR image for the public URL where you host this menu.

## Run locally

Open `index.html` in a browser, or serve this folder with any static web server. Google Fonts, Unsplash photos, and the QR generator are loaded from external CDNs, so those features need an internet connection.

## Publish and make a QR code

1. Publish this folder to a static web host such as GitHub Pages, Netlify, or your restaurant's website.
2. Open the published menu and select **Get the menu QR**.
3. Enter its public `https://` URL, generate the code, then download and print the PNG for tables or signage.

The QR encodes the public address you enter; a local file address or `localhost` will not open for guests on their phones.

## Customize

- Update dishes, prices, serving weights, and nutrition data in the `dishes` array in `app.js`.
- Assign each dish to `Veg`, `Non Veg`, or `Dessert` in that array to place it in the right menu section.
- Nutrition figures in the starter menu are illustrative estimates. Replace them with values verified for your recipes and serving sizes before publishing.
- Set the displayed currency and restaurant branding in `app.js`, `index.html`, and `styles.css`.
