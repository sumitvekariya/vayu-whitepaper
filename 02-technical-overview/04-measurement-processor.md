# Measurement Processor

The measurement processor receives the location set (longitude, latitude) and noise intensity measured in dB(A).

### **An Example Of The Payload:**

```json
[{ "location": [longitude, latitude], "dbaValue": 40 },
{ "location": [longitude, latitude], "dbaValue": 60 },
{ "location": [longitude, latitude], "dbaValue": 80 },
{ "location": [longitude, latitude], "dbaValue": 90 },
{ "location": [longitude, latitude], "dbaValue": 120 } ]
```

Silencio does not upload audio streams to the server; rather, the application calculates the sound level directly. Therefore, the anomaly detection engine must validate the incoming data points. This approach helps protect data quality and integrity.
