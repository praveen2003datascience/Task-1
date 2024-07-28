# Traffic Accident Data Analysis
# Project Overview
This project aims to analyze traffic accident data to identify patterns related to road conditions, weather, and time of day. We use various data visualization techniques to explore the data and identify accident hotspots and contributing factors.

# Dataset
The dataset contains information about traffic accidents with the following columns:

`ID:` Unique identifier for each accident

`Source:` Data source

`Severity:` Severity of the accident (1-4)

`Start_Time:` Start time of the accident

`End_Time:` End time of the accident

`Start_Lat:` Starting latitude of the accident

`Start_Lng:` Starting longitude of the accident

`End_Lat:` Ending latitude of the accident

`End_Lng:` Ending longitude of the accident

`Distance(mi):` Distance of the accident

`Description: `Description of the accident

`Street:` Street where the accident occurred

`City:` City where the accident occurred

`County:` County where the accident occurred

`State:` State where the accident occurred

`Zipcode:` Zip code where the accident occurred

`Country:` Country where the accident occurred

`Timezone:` Timezone of the accident

`Airport_Code:` Nearest airport code

`Weather_Timestamp:` Timestamp of the weather data

`Temperature(F):` Temperature at the time of the accident

`Wind_Chill(F):` Wind chill at the time of the accident

`Humidity(%):` Humidity at the time of the accident

`Pressure(in):` Atmospheric pressure at the time of the accident

`Visibility(mi):` Visibility at the time of the accident

`Wind_Direction:` Wind direction at the time of the accident

`Wind_Speed(mph):` Wind speed at the time of the accident

`Precipitation(in):` Precipitation at the time of the accident

`Weather_Condition:` Weather condition at the time of the accident

Amenity, Bump, Crossing, Give_Way, Junction, No_Exit, Railway, Roundabout, Station, Stop, Traffic_Calming, Traffic_Signal, Turning_Loop: Boolean values indicating various road conditions
Sunrise_Sunset: Whether it was day or night
Civil_Twilight, Nautical_Twilight, Astronomical_Twilight: Twilight conditions

# Installation
Clone the repository:
```bash
         git clone https://github.com/yourusername/traffic-accident-analysis.git
         cd traffic-accident-analysis
````
# Install the required Python packages:
```bash
         pip install pandas matplotlib seaborn folium
```
# Dataset:
I use the US_Accidents_March23.csv for the Traffic Accident Data Analysis.
```bash
          data = pd.read_csv(r"C:\Users\Praveen T\Downloads\US_Accidents_March23.csv\US_Accidents_March23.csv")
```
# Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your changes.
