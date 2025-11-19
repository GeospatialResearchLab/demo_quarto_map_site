# Heritage Cherry Trees Demo Site  
### A Quarto Example Embedding a qgis2web Map Hosted on GitHub

This repository contains a simple **Quarto website** created to demonstrate how an interactive map—exported from **QGIS** using the **qgis2web** plugin and hosted in a separate GitHub repository—can be embedded into a standalone project site.

The purpose of this demo is to show a fully FOSS, license-free workflow for community mapping projects and student portfolios. It illustrates how a project can pair:

- a narrative or “About” page, and  
- an embedded interactive map  

…using only free tools and GitHub Pages for hosting.

## What This Demo Shows

This Quarto site embeds an externally hosted interactive Leaflet map of **Heritage Street Trees** in Washington, DC that are cherry species (*Prunus*). The map itself was created in **QGIS** and exported using the **qgis2web** plugin, then published in its own GitHub repository via GitHub Pages.

This project demonstrates that:

- The **map stands alone** and can be hosted in any GitHub repository  
- A Quarto site can **embed that map via iframe**, just like any other website  
- No ArcGIS Online accounts, institutional logins, or proprietary software are required  
- Any organization, community group, or student can use this workflow

## Workflow Overview

1. **Map creation in QGIS**  
   - A subset of street trees was filtered to include only *Prunus* species meeting the District’s **Heritage Tree** criteria (≥ 100 inches circumference at DBH).  
   - Points were styled using graduated marker size based on DBH.

2. **Map export with qgis2web**  
   - The project was exported as a **Leaflet** web map.  
   - The exported map was placed in a separate GitHub repo and published using GitHub Pages.

3. **Quarto site creation**  
   - A minimal Quarto website was created with an “About” page and a “Map” page.  
   - The qgis2web map is embedded using a simple HTML `<iframe>`.

4. **Publishing on GitHub Pages**  
   - This site is published directly from the Quarto output folder.

## Why This Matters

This approach offers a lightweight, accessible alternative to ArcGIS Online for:

- **Community mapping workshops**  
- **Public-facing mapping projects**  
- **Student mapping portfolios**  
- **Collaborative research outputs**  
- **Any group without institutional GIS licenses**

It also provides a pathway for future instruction: students can build a Quarto site as a mapping portfolio, embed maps hosted in small GitHub projects, and document their process using reproducible workflow practices.

## Live Demo

- **Quarto site:**  
  *(Insert your GitHub Pages site URL once deployed)*

- **Interactive map (qgis2web export):**  
  *(Insert link to the separate map repo’s GitHub Pages URL)*
