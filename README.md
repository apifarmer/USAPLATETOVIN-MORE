# USAPLATETOVIN-API
USAPLATETOVINAPI
https://rapidapi.com/uponatime24/api/usa-plate-to-vin-more/details

developers evaluate your API at https://rapidapi.com/uponatime24/api/usa-plate-to-vin-more/details
README
Endpoints GET 'https://usa-plate-to-vin-more.p.rapidapi.com/platetovin/'
/platetovin/plate-state
Method: GET

Description: This endpoint fetches vehicle information based on the provided license plate and state.

Path Parameters:

plate-state: A string combining the license plate number and the state code separated by a hyphen. For example, 8VIR650-CA.
Query Parameters:

format (optional): Set to csv to receive the response in CSV format. Defaults to JSON if not specified.
Example Request:

GET 'https://usa-plate-to-vin-more.p.rapidapi.com/platetovin/8VIR650-CA'
GET 'https://usa-plate-to-vin-more.p.rapidapi.com/platetovin/8VIR650-CA?format=csv'
Description:

The endpoint takes a license plate number and state code in the format plate-state.
It scrapes vehicle data in real-time from a specified website.
By default, the response is returned in JSON format.
You can specify the query parameter format=csv to get the response in CSV format.
Response Example
JSON Response:

{
  "VIN": "1HGCM82633A123456",
  "Make": "Honda",
  "Model": "Accord",
  "Year": "2003",
  "Trim": "EX V6",
  "Style/Body": "Sedan 4D",
  "Engine": "3.0L V6",
  "Manufactured in": "Japan",
  "Age": 21,
  "Transmission": "Automatic"
}
CSV Response:

VIN,Make,Model,Year,Trim,Style/Body,Engine,Manufactured in,Age,Transmission
1HGCM82633A123456,Honda,Accord,2003,EX V6,Sedan 4D,3.0L V6,Japan,21,Automatic
