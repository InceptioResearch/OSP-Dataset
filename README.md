# OSP-Dataset (ICRA 2025)
Fuel-Optimal **Operational Speed Planning** for Autonomous Trucking on Highways

## Introduction
The full-trip
speed planning problem for autonomous trucks under delivery time and fuel consumption constraints, referred to as the **Operational Speed Planning (OSP)** problem. 

To support andaccelerate research on the OSP problem, we have developed a comprehensive dataset using a fleet of over **400 trucks**. The dataset contains rich, diverse information covering more than **22 million kilometers of real-world highway driving data**.

## Dataset
All dataset files can be found at `dataset` folder. 
All files are in `.csv` format. 
Every file represents a truck's operational data.


Each row in the datasets corresponds to a road segment, segmented according to geohash_p6. The meaning of each item in the dataset is introduced as follows:

| Name | Description |
| ---- | ---- |
| driving_time_seconds | Driving time |
| distance_m | Distance of the segment |
| speed_limit_low | Lower bound of speed limit |
| speed_limit_up | Upper bound of speed limit |
| lane_number_min | Minimum number of lanes |
| lane_number_max | Maximum number of lanes |
| curvature_abs_min | Minimum value of road curvature |
| curvature_abs_max | Maximum value of road curvature |
| slope_rad_min | Minimum value of slope |
| slope_rad_max | Maximum value of slope |
| has_tunnel | Whether there is a tunnel |
| has_toll | Whether there is a toll station |
| has_bridge | Whether there is a bridge |
| is_service_area | Whether there is a service area |
| is_highway | Whether it is a highway |
| road_type_1 | Whether there is a normal road |
| road_type_2 | Whether there is a junction |
| road_type_3 | Whether there is a ramp |
| altitude_m_avg | Average altitude, m |
| altitude_m_std | Standard deviation of altitude |
| traffic_status | Traffic congestion degree |
| standard_remain_time_seconds | Remaining time required by the waybill, second |
| real_travel_time_seconds | Real travel time, second |
| avg_speed | Average speed of the segment, kph |
|  |  |

## Citation
If using our data in your research work, please cite the following paper:
```
@article{wei2025osp,
      author    = {Li, Wei and Wu, Bin and Xiang, Jiahao and Ren, Jiaping and Wu, Yi and Yang, Ruigang},
      title     = {Fuel-Optimal Operational Speed Planning for Autonomous Trucking on Highways},
      journal   = {2025 IEEE International Conference on Robotics and Automation (ICRA)},
      year      = {2025},
    }
```