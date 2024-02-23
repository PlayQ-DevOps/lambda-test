All timestamps provided by sensors are UTC timestamps based on the local clock inside the sensor.

Example POST body sent from an air quality sensor:
```
{
    "timestamp": "2022-05-18T11:40:22.519222",
    "payload": {
        "aqi": 46
    }
}
```

Example POST body sent from a weather sensor:
```
{
    "timestamp": "2023-11-18T01:40:23.518922",
    "payload": {
        "temperature": 14,
        "humidity": 68,
        "wind_speed": 9
        "wind_direction": "NE"
    }
}
```

Example POST body sent from a traffic sensor:
```
{
    "timestamp": "2023-11-18T01:40:23.518922",
    "payload": {
        "cars_per_hour": 57
        "avg_speed": 67
    }
}
```
