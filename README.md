# DarkSkyAPITest

API Tests were conducted using Dark Sky API to extract weather data using multiple parameters. Both API request types - 'Forecast Request' and 'Time Machine Request' are used in the test cases

Please execute the below API requests in your browser or using POSTMAN tool (GET calls). Responses are committed to the Repository for your reference.

Test Case-1: Extract weather data for the future date (04-Sept-2018) - Time Machine Request:
Request: https://api.darksky.net/forecast/117bcd7ca3a8e87bb63dff50b177f170/37.8267,-122.4233,1536051600

Test Case-2: Extract weather data for any given location by changing Latitude and Longitude in the API (London as an example):
Request: https://api.darksky.net/forecast/117bcd7ca3a8e87bb63dff50b177f170/51.5074,-0.1278

Test Case-3: Extract weather data for the future date (05-Sept-2018) in 'Arabic' language excluding 'flags and currently' data
Request: https://api.darksky.net/forecast/117bcd7ca3a8e87bb63dff50b177f170/37.8267,-122.4233,1536138000?lang=ar&exclude=currently,flags

Test Case-4: Extract weather data for the today's date (02-Sept-2018) in 'German' language excluding 'minutely' data
Request: https://api.darksky.net/forecast/117bcd7ca3a8e87bb63dff50b177f170/37.8267,-122.4233,1535878800?lang=de&exclude=minutely

Test Case-5: Extract weather data for the today's date (02-Sept-2018) in both 'uk2' and 'si' units and see the difference w.r.t windSpeed,visibility metrics
Request: https://api.darksky.net/forecast/117bcd7ca3a8e87bb63dff50b177f170/37.8267,-122.4233,1535878800?units=si
Request: https://api.darksky.net/forecast/117bcd7ca3a8e87bb63dff50b177f170/37.8267,-122.4233,1535878800?units=uk2

