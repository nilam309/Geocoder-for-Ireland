Geocoder for Ireland

Geocoder provides the GPS coordinates for the given location.
Programming Language: Python
Coding Environment: Google Colab

Addresses in Ireland are generally formatted as such:
    Resident Name,
    Road or Local Area Name,
    Townland,
    Town/City,
    County

For the given task, I have considered only County, Town/City, Townland and respectively referred datasets areas listed below:
County: https://data.gov.ie/dataset/counties-osi-national-placenames-gazetteer2
Town: https://data.gov.ie/dataset/electoral-districts-osi-national-placenames-gazetteer3
Townland: https://data.gov.ie/dataset/townlands-osi-national-placenames-gazetteer3

The sequence to search co-ordinates for the location will be as follow:
1.	Townland
2.	Town/City
3.	County

