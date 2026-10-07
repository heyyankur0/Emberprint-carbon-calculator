# EmberPrint - Carbon Footprint Calculator

A web app that estimates an individual's yearly carbon footprint (in tonnes of CO₂e) from lifestyle and daily activities. Results update live as you move the sliders.

## Features
- Four categories: transport, home energy, food, lifestyle
- Live total with an animated gauge and a category breakdown chart
- Comparison against the average Indian and world footprint
- Personalised tips based on your biggest source of emissions
- Light and dark themes, responsive on mobile

## How it works
Footprint = activity × emission factor. Each answer is converted to kg CO₂e, then everything is added up per year.

Approximate factors used: grid electricity 0.82 kg/kWh, petrol car 0.17 kg/km, diesel 0.16, CNG 0.10, 2-wheeler 0.05, electric 0.06, public transport 0.06 kg/km, short flight 250 kg, long flight 1,100 kg, LPG 42.6 kg per cylinder.

## Tech
HTML, CSS and vanilla JavaScript in a single file. No installation needed.

## Run it
Download `index.html` and open it in any browser.

## Note
These are educational estimates, not an official audit.
