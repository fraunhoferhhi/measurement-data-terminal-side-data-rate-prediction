# Measurement data for the paper "Terminal-Side Data Rate Prediction for High-Mobility Users"

[1] Schäufele, D., Kasparick, M., Schwardmann, J., Morgenroth, J. and Stańczak, S., 2021. Terminal-Side Data Rate Prediction for High-Mobility Users. Submitted to VTC2021-Spring.

## Usage

Data is saved as pandas dataframe and can be loaded using

```
df = pd.read_hdf('DriveTest_uplink.hdf', 'data')
```

## Data columns

| Column | Unit | Notes |
| --- | --- | --- |
| Altitude | m | from GPS |
| Heading | ° | from GPS |
| Latitude | ° | from GPS |
| Longitude | ° | from GPS |
| Speed | km/h | from GPS |
| Time of Day | h | |
| * Current Data Rate | Kbit/s | Transmitted data rate over last 2s |
| * Elapsed Time | ms | Time duration of current data transmission |
| * Transmitted Bytes | B | Transmitted Bytes of current data transmission |
| * Bandwidth | MHz | from UE |
| * BLER | % | from UE |
| * cellID |  | from UE |
| * cellIdentity |  | from UE |
| * CQI |   | from UE |
| * EARFCN |  | from UE |
| * eNodeB ID |  | from UE |
| * Frequency | MHz | from UE |
| * MCS Level |  | from UE |
| * MIMO Layers | 1 | from UE |
| * Num Antenna eNodeB | 1 | from UE |
| * Num Carriers | 1 | from UE |
| * Num RB | 1 | from UE |
| * Pathloss | dB | from UE |
| * PCI |  | from UE |
| * PDSCH Throughput | Kbit/s | from UE |
| * PUSCH Throughput | Kbit/s | from UE |
| * Retransmission Rate | % | from UE |
| * RI | 1 | from UE |
| * RSRP | dBm | from UE |
| * RSRQ | dB | from UE |
| * RSSI | dBm | from UE |
| * SINR | dB | from UE |
| * Spectral Efficiency | bit/s/Hz | from UE |
| * TAC |  | from UE |
| * Timing Advance |  | from UE |
| * Tx Power | dBm | from UE |
| * TSMW 4G-Drift | ns/s | from TSMW |
| * TSMW F-Factor | dB | from TSMW |
| * TSMW Power | dBm | from TSMW |
| * TSMW RSRP | dBm | from TSMW |
| * TSMW RSRQ | dB | from TSMW |
| * TSMW SINR | dB | from TSMW |
| * TSMW Sigma-4G-Drift | ns/s | from TSMW |
| * TSMW TimeOfArrival | ms | from TSMW |
| Weather Apparent Temperature | °C | from Dark Sky API |
| Weather Cloud Cover | 1 | from Dark Sky API |
| Weather Dew Point | °C | from Dark Sky API |
| Weather Humidity | 1 | from Dark Sky API |
| Weather Precipation Intensity | mm/h | from Dark Sky API |
| Weather Precipation Probability | 1 | from Dark Sky API |
| Weather Pressure | mbar | from Dark Sky API |
| Weather Temperature | °C | from Dark Sky API |
| Weather UV Index |  | from Dark Sky API |
| Weather Visibility | km | from Dark Sky API |
| Weather Wind Speed | km/h | from Dark Sky API |
| Traffic Distance | m | distance to road for which jam factor is given |
| Traffic Jam Factor |  | from here.com API |
| Traffic Street Name |  | name of the road for which jam factor is given |
| Category |  | manual classification of environment |
