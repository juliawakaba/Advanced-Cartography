# Advanced Cartography: The Price of Peace
### SDG 2: Zero Hunger vs. Political Stability in Africa (2023)

---

## Project Overview
This cartographic project explores the intricate relationship between **food security** and **national governance**. By visualizing the **Prevalence of Undernourishment (POU)** alongside the **Political Instability Index (PI)**, this dashboard highlights how civil peace is often a prerequisite for achieving **Sustainable Development Goal 2: Zero Hunger**.

The project focuses on the African continent using 2023 datasets, providing a spatial narrative on the "price" that instability extracts from human nutrition.



## Tech Stack & Methodology
* **Frontend:** HTML5, CSS3 (Modern Glassmorphism UI)
* **Mapping Engine:** [Leaflet.js](https://leafletjs.com/)
* **Data Format:** GeoJSON
* **Hosting:** [Vercel](https://vercel.com)
* **Branding:** Adheres to official UN SDG 2 branding guidelines, utilizing the primary hex color **#DDA63A**.



## Cartographic Design Choices

### Choropleth Representation
I chose to represent **POU** as a choropleth layer (color-filled regions) and **Political Instability** as proportional symbols (purple bubbles). This allows the viewer to see two distinct datasets simultaneously without visual clutter.

### Thematic Styling
* **POU Gradient:** Uses a warm-to-dark brown gradient to represent the severity of undernourishment.
* **PI Symbols:** Uses varying bubble sizes to denote the intensity of political instability; larger bubbles signify higher instability ($-2.73$ to $-0.91$ range).
* **UI/UX:** The map features a floating header with a blurred background and the official SDG 2 icon to provide immediate context.



## Data Sources & Credits
Special thanks to the following organizations for providing the open-access data used in this spatial analysis:

| Dataset | Provider | Source Link |
| :--- | :--- | :--- |
| **Political Stability Index** | The World Bank | [data.worldbank.org](https://data.worldbank.org/indicator/PV.PER.RNK) |
| **SDG 2.1.1 PoU Data** | sdgs dataportal| [sdg dataportal](https://unstats.un.org/sdgs/dataportal/database) |
| **Basemap Tiles** | OpenStreetMap | [openstreetmap.org](https://www.openstreetmap.org/) |


## How to Run Locally
Since this project uses `fetch()` to load GeoJSON data, it requires a local server environment:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/juliawakaba/Advanced-Cartography
   ```

2. **Open the folder in your preferred IDE (e.g., VS Code)**

3. **Launch via Server:**
     - Use the Live Server extension in VS Code.
     - OR use Python to start a server: 
     ```python -m http.server 8000```

---

Created as part of the Advanced Cartography curriculum Winter Semester 2025 taught by Professor Merve Keskin.