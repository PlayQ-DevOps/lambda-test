Example POST body sent from an air quality sensor:
```
{
    "local_timestamp": "2022-05-18T11:40:22.519222-07:00",
    "payload": {
        "aqi": 46
    }
}
```

Example POST body sent from a weather sensor:
```
{
    "local_timestamp": "2023-11-18T01:40:23.518922-05:00",
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
    "local_timestamp": "2023-11-18T01:40:23.518922-05:00",
    "payload": {
        "cars_per_hour": 57
        "avg_speed": 67
    }
}
```
