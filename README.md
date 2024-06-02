
Ghoomi Ghoomi - Explore Indian States
Overview
Ghoomi Ghoomi is a web project designed to assist travelers in exploring the diverse and vibrant states of India. The website features an interactive map of each of the 28 states in India, highlighting 5-10 famous places in each state. Users can read detailed information about these places and delve deeper into the attractions they wish to explore. This project aims to promote Indian tourism and provide first-time travelers to India with a comprehensive guide to the country's rich cultural heritage and natural beauty.

Features
Interactive State Maps: Each state has its own map with marked locations of famous tourist spots.
Detailed Place Information: Each marked location comes with a detailed description and additional information.
User-Friendly Interface: Easy navigation and visually appealing design to enhance the user experience.
Tourist Information: Useful tips and information for travelers, including best times to visit, local cuisine, and cultural insights.
Technologies Used
Frontend: HTML, CSS, JavaScript
APIs: Google Maps API (for interactive maps)
Hosting: Currently not live on a server, but can be deployed on web hosting services like GitHub Pages, Netlify, etc.
Installation
Prerequisites
Web browser for testing
Steps
Clone the Repository:
bash
Copy code
git clone https://github.com/yourusername/ghoomi-ghoomi.git
Navigate to the Project Directory:
bash
Copy code
cd ghoomi-ghoomi
Open the Website:
Open the index.html file in your web browser to view the website.
Usage
Home Page: The main page displays a map of India with clickable states.
State Page: Clicking on a state redirects to a detailed map of the state with marked tourist spots.
Place Details: Clicking on a marked spot shows detailed information about the place, including history, attractions, and travel tips.
Navigation: Use the navigation bar to explore different sections of the website, such as travel tips, cultural insights, and contact information.
File Structure
bash
Copy code
ghoomi-ghoomi/
│
├── index.html               # Main entry point of the website
├── styles.css               # Stylesheet for the website
├── script.js                # JavaScript for interactive functionality
├── /assets
│   ├── /images              # Folder for storing images used in the website
│
├── /states
│   ├── state1.html          # HTML file for state 1
│   ├── state2.html          # HTML file for state 2
│   ├── ...                  # More state files
│
└── /data
    ├── places.json          # JSON file with place details
Detailed Information
index.html
This file contains the main structure of the home page, including the clickable map of India. It links to the CSS for styling and the JavaScript for functionality.

styles.css
This file contains all the styles used across the website to ensure a consistent and visually appealing design.

script.js
This file contains the JavaScript code responsible for handling user interactions, such as clicking on states to load the corresponding state pages and integrating the Google Maps API for displaying maps and markers.

/states
This directory contains individual HTML files for each of the 28 states. Each file includes an embedded Google Map with markers for famous places, and sections describing these places.

/data/places.json
This JSON file contains detailed information about the famous places in each state, such as name, description, and coordinates. This data is used to populate the maps and information sections dynamically.

Contributing
Fork the repository.
Create a new branch for your feature or bugfix:
bash
Copy code
git checkout -b feature-name
Make your changes and commit them:
bash
Copy code
git commit -m "Description of feature"
Push to the branch:
bash
Copy code
git push origin feature-name
Create a pull request.
License
This project is licensed under the MIT License. See the LICENSE file for more details.

Acknowledgements
Google Maps API for providing the map and marker functionality.
Open-source libraries and tools used in this project.
Contact
For any inquiries or feedback, please contact [your-email@example.com].

Thank you for using Ghoomi Ghoomi! We hope it enhances your travel experience across the beautiful states of India.





