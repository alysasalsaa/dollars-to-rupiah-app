# dollars-to-rupiah-app

A real-time USD to IDR converter with denomination breakdown, built with HTML, CSS, and JavaScript.

## About

Enter a dollar amount and instantly see the equivalent in Indonesian Rupiah using a live exchange rate. The app also breaks down the total into the fewest possible denomination notes and coins (Rp100 to Rp100.000).

## Features

- [x] User can enter a dollar value (including cents, e.g. $2.75)
- [x] User can see the total IDR from the converted dollar value
- [x] Real-time exchange rate fetched from exchangerate-api.com
- [x] Rate auto-refreshes every 5 minutes
- [x] Fallback rate (Rp16.000) used if API is unavailable
- [x] Denomination breakdown using fewest pieces possible (bonus)
- [x] Supports all IDR denominations: Rp100.000, Rp50.000, Rp20.000, Rp10.000, Rp5.000, Rp2.000, Rp1.000, Rp500, Rp200, Rp100
- [x] Warning shown for invalid or negative input

## Tech Stack

- HTML
- CSS
- JavaScript (vanilla)

## How to run

Open `index.html` in your browser — no build tools needed. Requires an internet connection for live exchange rates.
