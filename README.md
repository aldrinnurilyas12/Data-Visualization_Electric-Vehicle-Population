
![electric_dashboard](https://github.com/aldrinnurilyas12/Data-Visualization_Electric-Vehicle-Population/assets/105443417/40d1120a-c1f8-4a6f-8528-f0b3c25bc63f)


#AboutDataSet
VIN (1-10)	=> (Change column name to code_vehicle)
The 1st 10 characters of each vehicle's Vehicle Identification Number (VIN) /code_vehicle.

County	
This is the geographic region of a state that a vehicle's owner is listed to reside within. Vehicles registered in Washington state may be located in other states.

City	
The city in which the registered owner resides.

State	
This is the geographic region of the country associated with the record. These addresses may be located in other states.

Postal Code	
The 5 digit zip code in which the registered owner resides.

Model Year	
The model year of the vehicle, determined by decoding the Vehicle Identification Number (VIN)/ code_vehicle.

Make	
The manufacturer of the vehicle, determined by decoding the Vehicle Identification Number (VIN) / code_vehicle.

Model	
The model of the vehicle, determined by decoding the Vehicle Identification Number (VIN) /code_vehicle.

Electric Vehicle Type	
This distinguishes the vehicle as all electric or a plug-in hybrid.

Clean Alternative Fuel Vehicle (CAFV) Eligibility	
This categorizes vehicle as Clean Alternative Fuel Vehicles (CAFVs) based on the fuel requirement and electric-only range requirement in House Bill 2042 as passed in the 2019 legislative session.

Electric Range	
Describes how far a vehicle can travel purely on its electric charge.

Base MSRP	=> (I'm drop this column)
This is the lowest Manufacturer's Suggested Retail Price (MSRP) for any trim level of the model in question.

Legislative District	
The specific section of Washington State that the vehicle's owner resides in, as represented in the state legislature.

DOL Vehicle ID	
Unique number assigned to each vehicle by Department of Licensing for identification purposes.

Vehicle Location	
The center of the ZIP Code for the registered vehicle.

Electric Utility	
This is the electric power retail service territories serving the address of the registered vehicle. All ownership types for areas in Washington are included: federal, investor owned, municipal, political subdivision, and cooperative. If the address for the registered vehicle falls into an area with overlapping electric power retail service territories then a single pipe | delimits utilities of same TYPE and a double pipe || delimits utilities of different types. We combined vehicle address and Homeland Infrastructure Foundation Level Database (HIFLD) (https://gii.dhs.gov/HIFLD) Retail_Service_Territories feature layer using a geographic information system to assign values for this field. Blanks occur for vehicles with addresses outside of Washington or for addresses falling into areas in Washington not containing a mapped electric power retail service territory in the source data.

2020 Census Tract	
The census tract identifier is a combination of the state, county, and census tract codes as assigned by the United States Census Bureau in the 2020 census, also known as Geographic Identifier (GEOID). More information can be found here: https://www.census.gov/programs-surveys/geography/about/glossary.html#par_textimage_13 https://www.census.gov/programs-surveys/geography/guidance/geo-identifiers.html

#DOWNLOAD THE DATASET 
Link : https://catalog.data.gov/dataset/electric-vehicle-population-data
