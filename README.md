FORMAT: 1A
HOST: http://api.meshcandy.com/

# Mesh Candy Endpoints

## Get-Sensor-Battery-Value [/getBatteryValue?accountId=107&commonName=Cables&startDate=2018-07-07]

- `GET` ` ` `Key in accountId & optional input parameters` `    ` `/getBatteryValue`

### getBatteryValue [GET]

+ Response 200 (application/json)

    + Body
    
            {
                Id: 594,
                Value: 83,
                units: "Percentage",
                FK_DeviceEntry: 5900075,
                TimeStamp: "2018-08-09T01:30:20.191Z"
            }
            

## Get-Sensor-Humidity-Value [/getHumidityValue?accountId=107&commonName=Cables&startDate=2018-07-07]

- `GET` ` ` `Key in accountId & optional input parameters` `    ` `/getHumidityValue`

### getHumidityValue [GET]

+ Response 200 (application/json)

    + Body
    
            {
                Id: 594,
                Value: 37.8,
                units: "Percentage",
                FK_DeviceEntry: 5687319,
                TimeStamp: "2018-07-07T00:22:54.080Z"
            }


## Get-Sensor-Pressure-Value [/getPressureValue?accountId=107&commonName=Cables&startDate=2018-07-07]

- `GET` ` ` `Key in accountId & optional input parameters` `    ` `/getPressureValue`

### getPressureValue [GET]

+ Response 200 (application/json)

    + Body
    
            {
                Id: 594,
                Value: 1005,
                units: "MBar",
                FK_DeviceEntry: 5687319,
                TimeStamp: "2018-07-07T00:22:54.080Z"
            }

   


## Get-Sensor-Temperature-Value [/getTemperatureValue?accountId=107&commonName=Cables&startDate=2018-07-07]

- `GET` ` ` `Key in accountId & optional input parameters` `    ` `/getTemperatureValue`

### getTemperatureValue [GET]

+ Response 200 (application/json)

    + Body
    
            {
                "Id": 594,
                "Value": 2611,
                "units": "Celsius",
                "FK_DeviceEntry": 5900090,
                "TimeStamp": "2018-08-09T01:30:39.847Z"
            }
            

## Get-Location-Result [/getLocationResult?accountId=107&commonName=Cables&startDate=2018-07-07]

- `GET` ` ` `Key in accountId/ControlId & optional input parameters` `    ` `/getLocationResult`

### getLocationResult [GET]

+ Response 200 (application/json)

    + Body
    
            {
                Id: 594,
                SerialNumber: "D05490137",
                MongoId: "HyMoqK8W0e",
                CommonName: "Cables",
                MajorMinor: null,
                XCoord: null,
                YCoord: null,
                FK_AccountId: 107,
                FK_Make: null,
                FK_Model: null,
                MapURL: null,
                GUID: null,
                UUID: null,
                timeStamp: "2017-10-12T00:00:00.000Z"
            }
            

  