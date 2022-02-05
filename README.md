# IoT based Weather Station
The equipment required for this project are:

1.	NodeMCU
2.	DHT11 Sensor
3.	Breadboard
4.	Jumper Wires

# V1 sketch:
v1 sketch only support getting data from DHT11 sensor and sending it to THIGSPEAK server.

## V1 data format:
| Timestamp | Humadity | Temperature |
| --------- | -------- | ----------- |
| abc       | 35%      | 29          |
| etc       | etc      | etc         |


# V2 sketch:
v2 sketch support getting data from DHT11 sensor and making an api call to weather api for getting current weather condition. Then this data is sent to thingspeak server.
## V2 data format:
| Timestamp | Humadity | Temperature | Weather |
| --------- | -------- | ----------- | ------- |
| abc       | 35%      | 29          | Cloudy  |
| etc       | etc      | etc         | etc     |

___

## Jupyter Notebook:
Provides an predictive analysis of islamabad's weather data by checking correlation between different factors affecting weather and using different ML models.
### Note:
islamabad.csv is required to run jupyter notebook.

## Feed.csv
feed.csv represent a real output of v2 sketch.

## IoT Weather Station.pbix
A descriptive analysis of data obtained using sketch v2  

![Descriptive Analysis](https://github.com/MuhammadSaadJamil/IOT-Weather-Station/blob/master/Power%20Bi%20output.png?raw=true)

---
### Link to thingspeak [Channel Here](https://thingspeak.com/channels/1623014)

