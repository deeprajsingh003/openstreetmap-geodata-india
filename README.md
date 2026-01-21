# GEOData Visualization using Python & SQLite

This project demonstrates how to retrieve, process, store, and visualize geolocation data using Python, SQLite, and OpenStreetMap APIs.

# 📌 Project Origin
This project is based on a guided academic assignment from the Using Databases with Python course (Python for Everybody Specialization) by the University of Michigan (Dr. Charles Severance).

The original starter code was provided as part of the course.  
I independently executed, customized, and extended the project to strengthen my hands-on understanding.

#🔧 What I Modified
- Replaced default sample locations with **India Bengaluru landmarks and public places**
- Re-ran the complete data pipeline independently
- Debugged execution issues and API delays
- Added documentation and screenshots for clarity

# 🛠 Technologies Used
- Python
- SQLite
- OpenStreetMap (Geocoding API)
- HTML & JavaScript
- JSON
- Command Line (Windows PowerShell)

# 🔄 Project Workflow
1. Locations are defined in `where.data`
2. `geoload.py` fetches latitude & longitude using a geocoding API
3. Data is stored in an SQLite database
4. `geodump.py` generates a JavaScript file (`where.js`)
5. `where.html` visualizes the data on an interactive map

# 📸 Screenshots
Screenshots of terminal execution and map visualization are included in the `project screenshots/` folder and even here
<img width="880" height="701" alt="running geoload py in terminal" src="https://github.com/user-attachments/assets/49b8fa5b-38e5-469f-a021-ecf2fd47d6bd" />
<img width="1357" height="713" alt="running geodump py in terminal" src="https://github.com/user-attachments/assets/480dd5ad-b833-4c6d-af76-8197f54b5f5f" />
<img width="1365" height="638" alt="mentioned india bengaluru locations data in map" src="https://github.com/user-attachments/assets/09413b66-149c-4f63-8db9-eab30787cef3" />


# 📚 What I Learned
- Working with external APIs and rate limits
- Storing structured data using SQLite
- Transforming data between Python and JavaScript
- Visualizing real-world data on maps
- Debugging multi-step data pipelines

# 🚀 Future Improvements
- Add clustering for dense locations
- Improve map styling
- Integrate Google Maps API as an alternative

# 🧾 Disclaimer
This project is **educational** and based on a guided course assignment.  
All customizations, execution, and documentation were done independently for learning purposes.
