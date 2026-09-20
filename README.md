GridPoint

GridPoint is a Python-based web application that uses mathematical optimization to help determine suitable warehouse locations based on demand and other location data.

Technologies Used

Backend
Python
Flask — web application server
SciPy — mathematical optimization, specifically scipy.optimize.milp
Frontend
HTML
CSS
JavaScript — embedded directly within the Python script
Leaflet — interactive maps
Chart.js — data visualization

Python Modules Used

Standard Python Modules
math
pathlib
os
csv
io
json
random
time
urllib
Third-Party Packages
flask
scipy

How to Run
1. Open the project folder

Open Command Prompt or Terminal and navigate to the folder containing the Python file.

For example:

cd "D:\New folder (9)\gridpoint"

2. Install the required dependencies

Run:

pip install flask scipy

3. Run the application

Run:

python "gridpoint_updated (5).py"

4. Open the application

After the Flask server starts, the terminal should display a local address, usually similar to:

http://127.0.0.1:5000

Open that address in your web browser.

Notes

Make sure Python is installed and available from the command line.
An internet connection may be required for map tiles and other externally loaded frontend resources.
Keep the terminal running while using the application. Closing it or pressing Ctrl + C will stop the Flask server.
