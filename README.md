# ParkMatch: Frontend

A web application that helps users plan personalized national park trips with restaurant recommendations and itinerary building.

## What it does
- Takes user preferences through a questionnaire (dates, activities, climate, crowds)
- Shows personalized national park recommendations with real weather data from API
- Helps build complete itineraries with accommodation and dining options
- Finds restaurants near parks using Google Maps Places API
- Exports final trip plans (text file)

## File Structure

### Main Pages
- `index.html` => landing page and trip status
- `questionnaire.html` => user preference questionnaire  
- `park-selection.html` => displays recommended parks for selection
- `itinerary.html` => build and edit trip itinerary
- `restaurant-selector.html` - find and select restaurants near parks
- `final-itinerary.html` => view final trip with export/delete options

### Data
- `data/fake-parks-data.json` => fallback park data/data for testing
- `data/activities_adjusted.json` => available activity options
- `data/topics_adjusted.json` => available topic/interest options

### Other
- `images/` => background images and banners
- `icons/` => SVG icons for UI elements (from [feathericons.com](https://feathericons.com/))
- `logos/` => ParkMatch brand logos (horizontal, symbol, stacked)

## Stack
- HTML/CSS/JavaScript
- Google Maps JavaScript API
- Browser localStorage for data persistence (no users and lasting/personalized storage)
- Responsive design for mobile/desktop

## Setup
1. Clone the repo
2. Serve files with any static server
3. Backend API URL is configured in `questionnaire.html`