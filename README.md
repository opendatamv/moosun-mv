# Moosun MV Repository

Collection of Weather data collected from Maldives meteorology stations.

Data is collected from September 9 2019 to July 7 2020. We are planning to automate this process to automatically push new changes to this repository.

### Schema


| Name          | Datatype      |
| ------------- |:-------------:|
| id     | `int` |
| hastide     | `int`      |
| sunrise | `time`       |
| sunset | `time`       |
| moonrise | `time`       |
| humidity | ``       |
| temperature | ``       |
| description | `string`       |
| rainamount | `string`       |
| wind | `string`       |
| sunshine | ``       |

All the data is collected from [Maldives Meteorology](http://www.meteorology.gov.mv/)
