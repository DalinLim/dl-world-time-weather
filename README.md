

## Features
- Search locations worldwide using Open-Meteo Geocoding.
- Current conditions and five-day forecast from Open-Meteo.
- Live local clock updates every second using the location's IANA timezone.
- Responsive desktop and mobile layout.
- No API key, backend, PHP or build step required.


## APIs and attribution
- Geocoding: https://geocoding-api.open-meteo.com/
- Weather forecast: https://open-meteo.com/
- The app uses Open-Meteo's public API. No API key is required for non-commercial use. Review the provider's current terms and attribution requirements before using it commercially.
- Weather data is provided by Open-Meteo and licensed under CC BY 4.0.

## Notes
The local clock is calculated in the browser using the timezone returned by the geocoding/weather API and updates every second. Weather observations/forecasts refresh when the user searches again; they are not a live sensor stream.
