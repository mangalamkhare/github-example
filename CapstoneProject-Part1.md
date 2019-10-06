Introduction:

My Friend is working in Canada and has her home in the city of Toronto. She loves her neighbourhood because of all the great amenities and venues that exist such as Schools, hospitals, pharmacies, parks and so on. She has recently received a job offer from another company which she considers her dream company which is in another city. It has great career prospects for her. However this requires her to move from the current city if she decides to accept the offer. She wants to explore the neighbourhoods that are closer to the new job and has similar amenities which she has now. 

Business Problem:

•	My friend stays in the city of Toronto and has amenities like Good Schools, hospitals, food joints, hospitals, parks, pharmacies and grocery stores.
•	Her new job is in the city of Scarborough and wants the same amenities as she has now like
•	Schools, grocery stores, hospitals, pharmacies, parks food joints nearby. 
•	She decides to contact one of his friend who works on data science projects and take help of him to explore the two cities and get recommendations to have her home in the new city.

Data Needs:

•	Get Pincode and neighbourhood information for Toronto and Scarborough from the Wikipedia site “https://en.wikipedia.org/wiki/List_of_postal_codes_of_Canada:_M”

    This will help us to get information on potal code and neighbourhood details which can then be enriched with the latitude and longitude information

•	Enrich the neighbourhood information with Latitude and longitude information through geocoder data set. http://cocl.us/Geospatial_data

    This will help us to enrich the neighbourhood details with latitude and longitude information and then can be passed to four square API to get the details.

•	Use Foursquare data on venue categories, top tips, location data, ratings Fousquare API
    
    This data set will be the heart of the entire analysis. By using this API we will get all the venues in each neighbourhood.
    
    Once we get data we can cluster and analyse each neighbourhood and share the analysis to help her get the desired information

