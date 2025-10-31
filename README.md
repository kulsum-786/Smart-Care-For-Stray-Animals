# Smart-Care-For-Stray-Animals
A smart stray animal care system that analyzes city zone data to assess risk, maps NGOs and hospitals, and provides helplines for rescue, vaccination, and animal welfare using Python and Folium.

🐾 Smart Care for Stray Animals
📖 Project Overview

This project provides a data-driven system to identify and mitigate stray animal risks in Bengaluru.
It analyzes demographic, accident, and animal control data to classify zones into High, Medium, or Low Risk, generates interactive Folium maps, and helps users find local NGOs and veterinary hospitals for animal rescue, sterilization, or medical support.

It aims to bridge data analytics and social welfare, supporting both citizens and authorities in improving stray animal safety.

🧠 Key Features

📊 Zone-wise Risk Analysis based on animal–human ratios, accidents, and neutering rates

🗺️ Interactive Folium Map displaying risk zones and scores

📈 Visualizations (Pie Chart, Bar Chart, Heatmap, Radar & Trendline) for detailed insights

📍 NGO & Hospital Lookup by ward/place for animal rescue or complaints

📞 Built-in Helpline Directory for quick assistance


🧰 Technologies Used
Category	             Libraries / Tools
Programming Language	:Python 3.8+
Data Handling         :pandas, numpy
Visualization	        :matplotlib, seaborn
Mapping	folium
Utilities             :sys, warnings, IPython

⚙️ Installation Instructions
1️⃣ Create or open your project folder:-
cd "C:\Users\kulsum ansari\OneDrive\Documents\datathon"
mkdir stray_animal_care
cd stray_animal_care
2️⃣ Install Required Packages:-
pip install pandas numpy matplotlib seaborn folium
3️⃣ Place Required CSV Files in the Folder:-
cleaned_zone_dataset.csv  
place_to_zone_mapping.csv  
hospitaldata.csv  
zonewise_ngos.csv  
4️⃣ Save the Python File
Save your main script as:-
smart_care_for_stray_animals.py
▶️ How to Run
Run in terminal or command prompt:
python smart_care_for_stray_animals.py


You’ll be prompted to:

Enter a ward/place name (e.g., Banashankari)

View risk classification and visual insights

Get NGO and Hospital contact details for that area

📊 Outputs Generated
Output	              Description
🗺️ Interactive Map   :Displays risk zones with color-coded severity
📈 Charts & Plots   :Zone metrics comparison with averages
🔥 Heatmap	         :Correlation among zone features
🌐 Radar Chart	     :Zone’s performance on multiple factors
🏥 Contact Info	     :NGOs & Veterinary Hospitals by Zone
☎️ Helpline Section	 :Emergency and complaint contact details

🏙️ Risk Classification Logic
Risk Level	Criteria
High Risk (🔴)	High animal–human ratio, low neutering, more accidents
Medium Risk (🟠)	Mixed mitigating and risk factors
Low Risk (🟢)	High neutering rate, strong public infrastructure
📞 Helplines & Complaint Portals

📞 Helpline Numbers: 080-49203888 / 8904085030

☎️ BBMP Helpline: Dial 1533

📧 Email: onehelpdesk@karnataka.gov.in

🌐 Portals:Bangalore One Portal
Email Complaint

stray_animal_care/
│
├── cleaned_zone_dataset.csv
├── place_to_zone_mapping.csv
├── hospitaldata.csv
├── zonewise_ngos.csv
│
├── smart_care_for_stray_animals.py
│
└── outputs/
    ├── zone_risk_map.html
    ├── zone_visualizations/
    └── logs/

Possible Future Enhancements

Integrate real-time rescue request tracking

Use machine learning to forecast risk increases

Deploy on Streamlit for web access

Add live data from BBMP or NGO APIs









