# QOZ_Mapbox_iframe
# Texarkana Opportunity Zone Map

This interactive web map displays real estate listings located within Qualified Opportunity Zones (QOZs) in **Texarkana, Texas**. Built with [Mapbox GL JS](https://docs.mapbox.com/mapbox-gl-js/), the map visually plots properties using custom blue markers. Clicking a marker reveals key listing details in a popup, including price, square footage, and a direct link to the full property listing.

## 📍 Features

- **Interactive Map** centered on Texarkana, TX.
- **Custom Blue Markers** (`#227af7`) for each property.
- **Popup Windows** showing:
  - Address
  - Property type
  - Size / units
  - Price
  - Listing URL
- Easily expandable by adding more property entries to the `listings` array.

## 🗂 File Structure

- `index.html` – Main HTML file containing the map setup, styles, and listing data.
- Uses CDN-hosted Mapbox GL JS (v3.13.0)

## 🛠️ How to Use

1. Clone or download the `index.html` file.
2. Open it in any modern browser.
3. Ensure your Mapbox access token is valid (line 21).
4. Add or update listings inside the `listings` array in the script section.

## 🔧 Dependencies

- [Mapbox GL JS](https://docs.mapbox.com/mapbox-gl-js/): v3.13.0
- Custom Mapbox style: `mapbox://styles/bymarkallan/cmd39ol2s01m101s4asoi38rw`

## 🏘️ Current Listings

The following sample properties are currently displayed:
- **100 Main St** – Hotel McCartney (Office)
- **311 W Broad St** – Mixed Use
- **601 W 7th St** – Retail
- **1103 Spruce St** – Commercial Land

## 🔄 How to Add More Properties

Simply extend the `listings` array with new objects using the following structure:

```js
{
  address: "Property Address",
  type: "Property Type",
  size: "Size or Units",
  price: "Price",
  url: "Full Listing URL",
  coordinates: [longitude, latitude]
}

## 📌 Screenshot
![Texarkana_QOZ_Map](https://drive.google.com/file/d/1sPwGjWDtROY0FrH0cEKIblsFV1CGsBkW/view?usp=drivesdk)

📝 License

This project is open source and free to use. Attribution appreciated if reused for public or educational projects.



Made with ❤️ in Texarkana.