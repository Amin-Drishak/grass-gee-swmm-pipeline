# GRASS GIS + Google Earth Engine → SWMM Pipeline

**Author:** Muhammad Amin Khan  
**Purpose:** Minimal working example showing how to integrate **GRASS GIS**, **Google Earth Engine**, and **SWMM** for stormwater modeling.

---

## Workflow

This project demonstrates a simplified hydrological modeling workflow:

1. Fetches and preprocesses remote sensing & land cover data using Google Earth Engine.
2. Uses GRASS GIS for spatial analysis and watershed delineation.
3. Prepares and runs a simplified SWMM model to estimate peak flows.
4. Outputs hydrographs and summary statistics.

> ⚠️ Note: This example currently uses **mock rainfall and land cover data**.  
> Real data can be integrated from Google Earth Engine and GRASS GIS for accurate simulations.

---

## Tools & Libraries

- Python 3.x  
- GRASS GIS  
- Google Earth Engine API  
- EPA SWMM  
- Pandas, NumPy, Matplotlib  

---

## How to Run

1. Clone the repository:
   ```bash
   git clone <your-repo-link>
   cd grass-gee-swmm-pipeline-main
2. Create and activate a Python virtual environment:
   ```bash
   python -m venv .venv
   .\.venv\Scripts\activate  # Windows
   source .venv/bin/activate # Linux/macOS

---

### **2. Install dependencies**
```markdown
3. Install dependencies:
   ```bash
   pip install -r requirements.txt

---

### **3. Run the simulation**
```markdown
4. Run the simulation:
   ```bash
   python main.py

---

### **4. Check the output hydrograph**
```markdown
5. Check the output hydrograph:
   - The hydrograph image will be saved as `hydrograph.png` in the project folder.
> ⚠️ Note: This example currently uses **mock rainfall and land cover data**.  
> Real data can be integrated from Google Earth Engine and GRASS GIS for accurate simulations.

## Author
Muhammad Amin Khan  
Email: ameenkhan8823813@gmail.com  
WhatsApp: +8618852000702  
WeChat: Aminkhan786
