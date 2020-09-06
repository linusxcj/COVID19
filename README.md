# COVID-19 Tracker

This repository contains a REST API package that consolidates and provides real-time data on the availability of hospital beds, oxygen, and medicines across multiple sources for COVID-19. The data is updated every 30 minutes and is segmented by state, city, and pincode.

## API Endpoints

### Hospital Beds

- Endpoint: /hospital-beds
- Method: GET
- Parameters:
- state (required): State name
- city (required): City name
- pincode (required): Pincode
- Example: http://localhost:5000/hospital-beds?state=STATE&city=CITY&pincode=PINCODE

### Oxygen

- Endpoint: /oxygen
- Method: GET
- Parameters:
- state (required): State name
- city (required): City name
- pincode (required): Pincode
- Example: http://localhost:5000/oxygen?state=STATE&city=CITY&pincode=PINCODE


### Medicine

- Endpoint: /medicine
- Method: GET
- Parameters:
- state (required): State name
- city (required): City name
- pincode (required): Pincode
- Example: http://localhost:5000/medicine?state=STATE&city=CITY&pincode=PINCODE

