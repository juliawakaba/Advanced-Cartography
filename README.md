Advanced Cartography: The Price of Peace 🌍
SDG 2: Zero Hunger vs. Political Stability in Africa (2023)
Project Overview

This cartographic project explores the relationship between food security and national governance. By visualizing the Prevalence of Undernourishment (POU) alongside the Political Instability Index (PI), this dashboard highlights how civil peace is often a prerequisite for achieving Sustainable Development Goal 2: Zero Hunger.

The project focuses on the African continent using 2023 datasets, providing a spatial narrative on the "price" that instability extracts from human nutrition.
Tech Stack & Methodology

    Frontend: HTML5, CSS3 

    Mapping Engine: Leaflet.js

    Data Format: GeoJSON

    Hosting: Vercel

    Branding: Adheres to official UN SDG 2 branding guidelines, utilizing the primary hex color #DDA63A.

Cartographic Design Choices

    I chose to represent POU as a choropleth layer (color-filled regions) and Political Instability as proportional symbols (purple bubbles). This allows the viewer to see two distinct datasets simultaneously without visual clutter.

    Thematic Styling: * POU: Uses a warm-to-dark brown gradient to represent the severity of undernourishment.

        PI: Uses varying bubble sizes to show the intensity of political instability; larger bubbles signify higher instability (-2.73 to -0.91 range).

    Professional Dashboard UI: The map features a floating header with a blurred background (glassmorphism) and the official SDG 2 icon to provide immediate context.

Data Sources

    POU Data: Prevalence of Undernourishment statistics derived from the FAO (2023).

    PI Data: Political Stability and Absence of Violence/Terrorism indices derived from World Bank/Governance Indicators.

How to Run Locally

Since this project uses fetch() to load GeoJSON data, it requires a local server environment (or hosting via Vercel/GitHub Pages):

    Clone the repository:
    Bash

    git clone this project

    Open the folder in VS Code.

    Use the Live Server extension to launch index.html.

    Alternatively, use Python to start a server: python -m http.server 8000.

Created as part of the Advanced Cartography curriculum.

Would you like me to add a "Key Findings" section to this README based on specific countries in your data that show the strongest link between instability and hunger?