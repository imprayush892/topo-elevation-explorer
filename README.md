# TOPO — 3D Terrain Explorer & Exporter

![TOPO Version](https://img.shields.io/badge/version-4.0-blue)
![License](https://img.shields.io/badge/license-MIT-green)
![Build](https://img.shields.io/badge/build-passing-brightgreen)

**TOPO** is a high-performance, client-side web application for visualizing global topographic data and exporting it into CAD and 3D-modeling environments. 

Built for urban designers, architects, and digital fabricators, TOPO bridges the gap between expensive GIS data and early-stage spatial conceptualization. It extracts Mapzen Terrarium DEM data and generates 3D meshes and vector contours directly in your browser.

## ✨ Features

* **Interactive 3D Environment:** Fluidly explore global terrain using MapLibre GL JS.
* **Client-Side 3D Export:** Draw a polygonal boundary and instantly download the terrain as an `.STL` (binary, 3D-printable) or `.OBJ` mesh.
* **Vector Contour Generation:** Export strict AC1009 R12 `.DXF` files with customizable contour intervals (drops seamlessly into Rhino, Grasshopper, or AutoCAD).
* **Zero Backend:** All marching-squares algorithms, mesh triangulation, and file encoding happen in the browser via vanilla JavaScript.
* **Multiple Map Styles:** Toggle between Dark, Satellite, Topographic, and Street base maps.
* **Live Data Overlays:** Enable elevation heatmaps and neon contour vectors in real-time.

## 🚀 Quick Start

Because TOPO has zero backend dependencies, running it is incredibly simple.

### Option 1: Live Demo
[Insert Link to Live Demo Here]

### Option 2: Run Locally
1. Clone the repository:
   ```bash
   git clone https://github.com/imprayush892/topo-elevation-explorer.git
