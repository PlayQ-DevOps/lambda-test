Example response to a GET request for a air quality sensor:
```
{
    "timestamp": "2022-05-18T11:40:22.519222",
    "type": "air_quality",
    "name": "chicago.w_goethe_st",
    "location": {
        "lat": 41.90587258379623,
        "long": -87.63444084296869
    },
    "payload": {
        "aqi": 46
    }
}
```

Example response to a GET request for a weather sensor:
```
{
    "timestamp": "2023-11-18T01:40:23.518922",
    "type": "weather",
    "name": "houston.lyons_ave",
    "location": {
        "lat": 29.77666625781551,
        "long": -95.31539968940213
    },
    "payload": {
        "temperature": 14,
        "humidity": 68,
        "wind_speed": 9
        "wind_direction": "NE"
    }
}
```

Example response to a GET request for a traffic sensor:
```
{
    "timestamp": "2023-11-18T01:40:23.518922",
    "type": "traffic",
    "name": "austin.hampton_rd",
    "location": {
        "lat": 30.292399617881824,
        "long": -97.72776190288003
    },
    "payload": {
        "cars_per_hour": 57
        "avg_speed": 67
    }
}
```
