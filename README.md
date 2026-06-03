# Woodpecker_Autonomy
This is a collection of programs encompassing a Linux command line CAN bus monitoring tool and autonomous line following Python script for the Woodpecker LSEV. 
Part of my senior capstone design team at Oregon State University.

## wp_can_monitor: A simple Linux command line CAN bus tool for the Woodpecker
This is a simple bash script that allows you to view the data flowing on the Woodpecker's CAN bus.

## line_following_v2: A line detection OpenCV-Python script
This is a Python script that uses OpenCV to detect a lane marking on the ground in front of the Woodpecker and draws lines. Goal is to output steering angle and control the EPS via CAN.

<img width="1531" height="973" alt="CAN monitoring" src="https://github.com/user-attachments/assets/dd2f5e58-c4d1-4beb-8d0e-d24efa574943" />

<img width="940" height="542" alt="Line_detection_v2" src="https://github.com/user-attachments/assets/7e0e029f-5509-45ee-8f5c-80380d928407" />
