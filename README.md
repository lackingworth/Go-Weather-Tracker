# Go-Weather-Tracker

Go + OpenWeather API Weather Tracker
Located on port 8080

## Installing

* You must have [Go v1.21](https://go.dev/doc/install) (or higher) installed on your system
* You must have [OpenWeatherMap](https://home.openweathermap.org/api_keys) API key

## Executing program

* Clone this repository to the location of your choosing
* Provide necessary information (API key) to *.apiConfig* file
* Open your terminal
* Navigate to the saved location using ```cd folderName``` command, where *folderName* is the name of your path folder
* When in right location run:
```
go build
go run main.go
```
## Usage (Requests)

* To get weather information, send *GET* request to *DOMAIN/weather/city_name*, i.e:
 ```
localhost:8080/weather/London
```

## Help

For customizability of the response, update the Structs provided accordingly (also, check [subscription plan for OWM API](https://openweathermap.org/api) for better understanding of available features)

For more types of weather information or general issues about weather API, please refer to:
* https://openweathermap.org/ - OpenWeatherMap portal

Feel free to report any issues or suggest improvements
