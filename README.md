# Real-World Thermal-Inertial Dataset for Self-TIO
 
## Dataset
  * Download dataset
    - [[Google Drive](https://drive.google.com/drive/folders/1nSRaHt6HGazyHHi3sbUz7Nb7pw3BK9gm?usp=sharing)] 
  * Sensors
    - MicroStrain 3DM-GX5-25 IMU and FLIR Boson+640 Infrared Thermal Camera
  * Sequences
    - Total five sequences (Grassland (3) and Street (2))
  * Calibration
    - Calibration is performed with [Kalibr]([https://drive.google.com/drive/folders/1nSRaHt6HGazyHHi3sbUz7Nb7pw3BK9gm?usp=sharing](https://github.com/ethz-asl/kalibr/wiki/supported-models)) with heated circle grid target.
  * Ground truth
    - Ground truth is captured with GNSS and transformed with TUM dataset format (timestamp x y z q_x q_y q_z q_w).
  
<p align='center'>
    <img src="robot_env.png" alt="drawing" width="500"/>
</p>  

## Paper
  * Self-TIO: Thermal-Inertial Odometry via Self-Supervised 16-bit Feature Extractor and Tracker (Accepted to RA-L).
  * Authors: Junwoon Lee, Taisei Ando, Mitsuru Shinozaki, Toshihiro Kitajima, Qi An, and Atsushi Yamashita
  * Acknowledged: This work was supported under the university-corporate collaboration agreement between Kubota Corporation and the University of Tokyo.
  * Contact: [Junwoon Lee](mailto:leejunwoon@robot.t.u-tokyo.ac.jp?subject=[GitHub]%20Source%20Han%20Sans)
  

