# Data Fields
- `time`
• The time field is in Unix time and can be converted to local time with a simple script or using online tools.
- `latitude, longitude`
• The latitude and longitude readings from the devices are determined via GPS and given in degrees for projected corrdinates.
- `pm1, pm25, pm10`
• The particulate matter (pm) readings from the optical particle counter after calibration.
• The units for each are instantaneous mass concentrations in μg/m3.
- `no2`
• The nitrogen dioxide (no2) readings from the gas sensors after conversion and calibration.
• The unit is instantaneous concentrations in parts per billion (ppb).
- `bin0-bin23`
• Twenty-four bins from the OPC containing particle number counts for different sizes, ranging from 0.35 to 40 μm. The bin boundary sizes are as follows from bin0 to bin23:
- `temperature`
• Ambient temperature reading in degrees Celsius.
- `humidity`
• Ambient relative humidity reading in percentage

Table.  datasets
|City|Sensing target pollutants|Sensing fleet|Duration|
|----|-------------------------|-------------|--------|
|New York City, US|Particulate matter, particle size distribution, NO2|Five municipal vehicles|Jan. 2020 - Feb. 2020; Sep. 2021 - Dec. 2021|