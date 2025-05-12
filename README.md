# land-use-land-cover-mapping-south-Lebanon-2024
Supervised classification of Landsat 8 imagery for South Lebanon Governorate using ArcGIS Pro. Includes maps, shapefiles, KML, area analysis, and methodology.
 🗺️ Land Cover & Land Use Mapping – South Lebanon (2024)
 📍 Project Overview
 This project was part of my GIS work in 2024 where I focused on creating a **land cover and land use (LULC)** classification for the **South Lebanon Governorate
 I used **ArcGIS Pro** and **Landsat 8 imagery** to perform a **supervised classification**. The goal was to categorize the area into different land types like urban areas, crops, bare soil, and so on
 I worked on everything from preparing the satellite image, classifying the land types, cleaning up the results, calculating the areas, and exporting the maps. The final outputs include a shapefile, map visuals, Excel tables, and even a KML file for Google Earth.
  🎯 Objective
  - Understand how land is being used across South Lebanon
- Provide a baseline for environmental monitoring or land change tracking
- Create something that could potentially support planning, recovery, or academic research in the region
- ## 🛠 Tools & Data Used
- **Satellite**: Landsat 8 (2024)
- **Software**: ArcGIS Pro
- **Techniques**: Image clipping, supervised classification, raster-to-vector conversion
- **Output formats**: Shapefiles, Excel, PDF, and KML
- ---

## 🛠 Tools & Data Used
- **Satellite**: Landsat 8 (2024)
- **Software**: ArcGIS Pro
- **Techniques**: Image clipping, supervised classification, raster-to-vector conversion
- **Output formats**: Shapefiles, Excel, PDF, and KML

---

## 🧪 Methodology

Here’s a quick breakdown of the workflow:

1. **Image Preparation**
   - I started by clipping the Landsat 8 composite image to the South Lebanon area.
   - The image bands (1 to 7) were merged into one file and checked for quality.

2. **Classification**
   - I manually created training samples for each land class based on visible features in the imagery.
   - Then I ran a supervised classification using those samples.
   - Once I got the raster result, I cleaned it up and clipped it to the area of interest.

3. **Post-Processing**
   - I converted the classified raster to vector polygons (to calculate area more easily).
   - I used ArcGIS field calculator to get the area of each class in km².
   - I exported everything into Excel and created a final PDF map layout.

📄 I also wrote a short methodology summary here:  
`Docs/Land cover land use Methodology.docx`

---

## 🌍 Land Use / Cover Classes
- Urban Areas  
- Agricultural Units  
- Field Crops  
- Permanent Crops  
- Artificial Vegetation  
- Wooded Land  
- Bare Soil  
- Water Bodies

Each one is labeled and colored in the final map and attribute table.

---

## 📐 Area Results

Detailed area results by class are provided in:
- `Docs/LUC South_Lebanon 2024 Excel.xlsx` (Excel)
- `Maps/LUC_South_Lebanon_2024.pdf` (Visual Map with Legend)

## 🧭 Outputs
- `Data/` folder with shapefile and classification outputs
- `Docs/` folder with Excel sheet and written methodology
- `Maps/` folder with final LULC map (PDF)
- **KML file for Google Earth viewing** (`GoogleEarth/` folder)

---

## 📂 Folder Structure

🔒 Note on Data Use
This project uses open satellite data (Landsat 8) and was prepared for educational and portfolio purposes. All classifications and maps were independently generated and do not represent an official publication.
👤 About Me
Rami el khatib
Bachelors  in Surveying Engineering and Masters in data science -LAU
📧 ramikhatib615@gmail.com| 🌐 www.linkedin.com/in/rami-al-khatib-75ba2028b5
