#T-FAC: Target-free Automatic Calibration of Multi-line LiDAR
================

		**Current version**: 1.0  
		This source code provides a reference implementation for Target-free Automatic Calibration of Multi-line LiDAR.

## 1. Introduction
In the multi-LiDAR system, LiDARs have their own local coordinates. To unify the coordinate system, the 3-D coordinate transformation relation between the laser scanners must be accurately calibrated.

T-FAC (**T**arget **F**ree **A**utomatic **C**alibration) is an automatic calibration method for multi multi-line LiDAR which only use 3D point cloud data.

![image](https://github.com/AlienCat-K/LiDAR-Automatic-Calibration/blob/master/pic/calibration.png)
## 2. License
This software is for non-commercial use only. Any modification based on this work must be open source and prohibited for commercial use.

If you use this source code for your academic publication, please cite our TIM paper:

	@article{gong2018target,
	title={A Target-Free Automatic Self-Calibration Approach for Multibeam Laser Scanners},
	author={Gong, Zheng and Wen, Chenglu and Wang, Cheng and Li, Jonathan},
	journal={IEEE Transactions on Instrumentation and Measurement},
	volume={67},
	number={1},
	pages={238--240},
	year={2018},
	publisher={IEEE}
       }

## 3. Dependencies
		PCL 1.7
		Eigen

## 4. Usage

For compiling the examples, you need CMake library. For building the examples you have to first build the project:  

		mkdir build  
		cd build  
		cmake ..  
		make  
To run the examples, you need some point cloud data:  

**Test data:**  

		L_LiDAR frames: https://drive.google.com/open?id=1r7EY0LDTWw2qpiJb1M-Rh3Tbtl_5vUfk (Copy these pcds into "../data/L-LiDAR-Frames")  	
		H_LiDAR_Maps:   https://drive.google.com/open?id=17mUeT8eyeIGJrGu8fT3_rG_ktYUXkcHX (Copy this pcd map into "../data/H-LiDAR-Map-data")  
	
# Additional Information
Lidar&Camera :https://gitlab.acfr.usyd.edu.au/its/cam_lidar_calibration 
