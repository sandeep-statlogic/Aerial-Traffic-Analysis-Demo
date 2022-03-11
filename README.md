# Aerial Traffic Analysis Demo

This repository is only to show the working of aerial traffic analysis and thus only contains product features and demo video. All the development codes are kept confidential.

## Project Description


This project is developed to provide On-demand Real-time analytics on data captured through an UAV which allows for instant deployment of drone cameras for traffic analysis anywhere, anytime.

### Project background

While fixed cameras are already being used for traffic monitoring they only cover a very small portion of the roads. In cases such as surveying or emergencies there is a need to cover much larger areas and drones are quick and cost-effective for providing on-demand coverage of traffic without any prior calibration. But tracking multiple moving objects through a moving camera requires much advanced techniques than traditional methods.

We use a cascade of deep learning models for accurate detection and tracking. A total of 7 different classes of vehicles are used to detect the targets. Our models are trained to be robust and can perform in different lighting, weather conditions and altitude. Speed of each vehicle is estimated with Continuous geo-referencing and calibration of the drone.

## Features


- Individual vehicle labels with ID, Vehicle class
- Speed estimation of each vehicle.
- Vehicle trajectories and heatmaps
- More than 100 vehicles tracked simultaniously
- Capability to add virtual gates anywhere.
- Can be customized for various traffic analysis applications like single lane monitoring, single class monitoring, idle time calculation etc.


## Results


Our detection system provides consistent results across different classes on data captured with varying altitude and angles. 

![asteria_accuracy1](https://user-images.githubusercontent.com/81687641/157895034-9e25e417-bbcb-42ce-a0d0-fe06902060f0.png)

> Note: `At altitudes higher than 300 feet pedestrian detection isn't recommended`


## Demo


#### High altitude - High volume traffic monitoring with heatmap



https://user-images.githubusercontent.com/81687641/157913953-21624ba8-236e-4f11-b61d-74cef0999f7e.mp4

##### Heatmap overlay

![stacked_heatmap](https://user-images.githubusercontent.com/81687641/157911132-e4c58aae-2560-4966-a7f4-734af0fe2fee.png)


#### Added Virtual gates for automated traffic count in each lane



https://user-images.githubusercontent.com/81687641/157915227-1d0204c3-6943-4e12-8d45-3f7467520eef.mp4

##### Sample vehicle record

![sample_vehicle_record](https://user-images.githubusercontent.com/81687641/157911105-77e12c42-b52e-45ca-a2a8-2270c2ba6975.png)

##### Satellite Imagery Overlay

![satellite_overlay](https://user-images.githubusercontent.com/81687641/157916449-06171d03-7fa9-4460-9e78-fcd0d1760cca.jpeg)
