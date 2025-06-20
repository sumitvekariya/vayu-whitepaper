# Silencio Explorer

Visualization of the Different Datasets Collected

## Street Noise Level Explorer

### Data Pipeline for H3 Hexagons Aggregation

Silencio uses a data pipeline to continuously stream information from our hot database. This pipeline systematically processes hexagons at multiple resolutions ranging from 3–13, depending on geographic location. It then recalculates and updates the average noise levels, storing them in the hexagons database. The noise levels are categorized into four distinct classifications:

*   **Green (low) - dB(A)**
*   **Yellow (moderate) - dB(A)**
*   **Orange (intermediate) - dB(A)**
*   **Red (high) - dB(A)**

## Venue Check-In Explorer

Silencio lets users check in at venues and measure noise levels in real-time using their mobile devices. The app verifies the user’s location to ensure the noise readings are accurately associated with the corresponding venue. These measurements are then aggregated and displayed on a map for easy visualization.

When users conduct a check-in, the app measures the venue’s noise level in decibels dB(A). Users can view the number of check-ins and the average noise level at each venue, all of which are displayed on the map for easy reference.

*   **< 59 dB(A)- Quiet**
*   **>60-69 dB(A) - Loud**
*   **> 70 dB(A) - Very Loud**

### Filtering and Sorting

Users can search on the map by the following criteria:

*   Nearby Venues: Find venues close to your location.
*   Noise Levels: Filter venues by quiet, loud, or very loud.
*   Venue Types: Choose from categories such as restaurants, cafes, or parks.
*   Venue Name: Search for the name of the venue through the search function.

As the app develops, users will also be able to filter by date (historic, year, month, day, hour) or time of day (morning, noon, evening, night).

## **Noise Complaints**

Users can easily file noise complaints on the map or at specific venues, providing helpful feedback alongside their noise level recordings.

Complaints can be logged at any location or venue. The number of complaints is counted and displayed on the map, with clusters highlighting areas with more noise issues depending on the zoom level.

### **Filtering and Sorting**

*   **Complaint Source:** Complaints can originate from traffic, neighbors, music, construction, animals, nightlife, trains, industrial, events, sirens, ships, airplanes, and other sources.
*   **Time Frame:** Complaints can be filtered to show the past 24 hours (live complaints) or trends over the past year and three months.

