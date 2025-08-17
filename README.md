# 🚍 Bus Route Optimizer for College Students

This project provides an interactive tool to calculate distances, fares, and visualize optimized bus routes between **cities** and **colleges** using the [OpenRouteService API](https://openrouteservice.org/).  
It displays the **map with route, markers, distance, and estimated fare** directly inside Jupyter Notebook or Google Colab.

---

## Features
-  Select a **City** and a **College** from dropdowns.  
-  Calculates **road distance** using OpenRouteService.  
-  Estimates **bus fare** (₹1.2 per km, minimum ₹10).  
-  Shows an **interactive map** with route, start & end markers.  
-  Adds intermediate **orange markers** with place names   

---


##  Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Manu03072004/Bus_Route_Optimizer.git
   cd Bus_Route_Optimizer
    ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
  
   Or install manually (if not using requirements.txt):
   pip install pandas folium openrouteservice ipywidgets
   ```
---

##  Dataset

The project uses a CSV file `updated_cities_and_colleges.csv` that contains the following columns:

- **City** – Name of the city  
- **College** – Name of the college  
- **Latitude** – Latitude coordinate  
- **Longitude** – Longitude coordinate  

This dataset is used to fetch coordinates for cities and colleges to calculate routes and fares.

---

## Usage

1. Open the notebook:
   ```bash
   jupyter notebook Bus_Route_Optimizer.ipynb
    ```
or run it directly in Google Colab.

2. Enter your OpenRouteService API Key inside the notebook.

3.Select a City and College from the dropdowns.

4.The notebook will display:

 Optimized route on an interactive map

 Distance traveled

 Estimated fare

---

## Example Output

Distance & Fare Display

 Hyderabad to IIT Hyderabad
Distance: 42.56 km
Fare: ₹51.07


---

## Author

- **Pusarla Manaswini**  
📧 Email: pusarlamanaswini@gmail.com  
🔗 GitHub: https://github.com/Manu03072004
---


