# Hotel Rates Filter API - Read Me

This project is built using Visual Stuido 2022 and .NET 6. Please clone the repository (https://github.com/momerjaved/Hote-Rates-Filter-API.git) to your local machine and use Visual Studio to open the solution file HotelRatesFilterAPI.sln. Press CTRL+F5 to execute project which will display the default Swagger API landing page. You will find a single GET method named HotelRatesFilter accepting two parameters: hotelId : integer and arrivalDate : string.  Provide values in both fields for e.g. as below

hotelId : 7294
arrivalDate  "2016-03-15T00:00:00.000+01:00"

Press Execute and scroll down , server call should return with Code 200 and JSON data in Response Body section with filtered HotelId and corresponding Hotel rates as required by the task. 

The hotelrates.json file can be found under Data folder and you can try a different combination of hotelId and arrivalDate.  For e.g.  the combination 

hotelId : 7295
arrivalDate  "2023-05-01T00:00:00.000+01:00"

should fetch 2 Hotel rates.

 Unit Tests project :  **HotelRatesUnitTest**. Open the Test Explorer and press 'Run All Tests in View' button. All tests should pass successfully.
