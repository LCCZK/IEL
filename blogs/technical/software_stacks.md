| Stack name               | Description                                                                                                                                                             |
| ------------------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `Perception`             | Process inputs from Cameras and the Lidar, perform object recognition and locate them.                                                                                  |
| `Localisation & Mapping` | Integrate perception output and odometry measurement, smooth and reduce the noise of the measurements, and produce a map. Then, predict the car's location on that map. |
| `Planning`               | Given the map of the environment and location of the car, produce an optimum path for the car to follow                                                                 |
| `Control`                | Communicate with the hardware parts and control the car to follow the path produced.                                                                                    |
