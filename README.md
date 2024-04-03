## Weapon detection system deploying yolo (Pre trained model)for live streams images videos featuring email notification
The Weapon Detection System utilizes the YOLO (You Only Look Once) pre-trained model to detect weapons in live streams, images, and videos in real-time. YOLO's efficient object detection capabilities ensure quick and accurate identification of firearms and other weapons. The system continuously monitors the input data and triggers an alert whenever a weapon is detected. Alongside detection, it sends email notifications to designated recipients, providing instant alerts to security personnel or authorities. This proactive approach enhances safety and security measures in public spaces, airports, schools, and other critical locations. The system's real-time capability enables swift response to potential threats, minimizing the risk of harm. Integrating YOLO's robust detection capabilities with email notifications ensures timely communication and action in critical situations, contributing to a safer environment.
## About
The Weapon Detection System utilizing YOLO (You Only Look Once) pre-trained model is designed to analyze live streams, images, and videos in real-time for the presence of weapons. YOLO is a state-of-the-art object detection algorithm known for its speed and accuracy, making it ideal for rapid detection tasks. The system continuously processes incoming data, identifying weapons such as firearms and knives with high precision.Upon detection of a weapon, the system triggers an immediate email notification to designated recipients, including security personnel or law enforcement authorities. This enables swift response and intervention to mitigate potential threats. The system is capable of handling multiple streams simultaneously, ensuring comprehensive surveillance coverage.

The YOLO model is fine-tuned to optimize detection performance specifically for weapons, achieving reliable results even in challenging environments or varying lighting conditions. Integration with existing security infrastructure is seamless, allowing for easy deployment and scalability.Advanced features such as region of interest (ROI) prioritization and tracking are incorporated to enhance operational efficiency and situational awareness. The system also offers customizable alert thresholds and filtering options to minimize false positives and optimize resource allocation.Robust encryption and authentication mechanisms are implemented to safeguard sensitive data and ensure secure communication channels for email notifications. Regular updates and maintenance are conducted to keep the system resilient against emerging threats and vulnerabilities.

Overall, the Weapon Detection System powered by YOLO provides a powerful solution for enhancing security measures in various settings, including public spaces, transportation hubs, and critical infrastructure facilities, contributing to a safer environment for all.

## Features
The project you described involves several components and features. Here's a breakdown of the main features of the weapon detection system deploying YOLO (You Only Look Once) pre-trained model for live streams, images, and videos, with email notification:

1. **YOLO Pre-Trained Model**: YOLO is a popular object detection algorithm known for its speed and accuracy. You'll utilize a pre-trained YOLO model specifically trained to detect weapons.
2. **Real-Time Object Detection**: The system continuously processes live streams of images and videos in real-time, identifying and localizing weapons present in the scene.
3. **Image and Video Processing**: The system should be capable of processing both individual images and video streams, providing real-time analysis of each frame to detect weapons.
4. **Email Notification**: When a weapon is detected in a stream or video frame, the system generates an email notification. This notification can include relevant details such as the timestamp, location (if available), and a snapshot of the frame containing the detected weapon.
5. **Integration with Email Service**: The system integrates with an email service provider (such as Gmail, Outlook, or custom SMTP servers) to send out notifications. This involves configuring SMTP settings and handling email sending within the application.
6. **Customizable Thresholds**: The system allows for the customization of detection thresholds. Users can adjust parameters such as confidence threshold to control the sensitivity of the detection system.
7. **Multi-Platform Support**: The system should be deployable on various platforms, including desktop computers, servers, and potentially embedded systems for deployment in security cameras or IoT devices.
8. **Scalability and Performance**: The system should be designed to handle a large volume of incoming video streams or images, ensuring efficient processing and minimal latency.
9. **User Interface (Optional)**: An optional feature could include a user interface for monitoring the detection process, configuring settings, and viewing past notifications.
10. **Logging and Analytics**: The system logs detected events and provides analytics such as frequency of weapon detection, trends over time, and performance metrics.
11. **Security and Privacy**: Considerations for data security and privacy should be incorporated into the system design, especially if handling sensitive video feeds or personal information.
12. **Deployment and Maintenance**: The system should be designed for easy deployment and maintenance, with clear documentation and support for updates and patches.
    
By incorporating these features, the weapon detection system deploying YOLO for live streams, images, and videos with email notification can provide effective real-time monitoring and alerting for security purposes.

## Requirements
1. Operating System: Compatible with Windows, macOS, and Linux distributions.
2. Programming Language: Utilize Python for backend development.
3. Framework: Implement YOLO (You Only Look Once) pre-trained model for real-time object detection.
4. Integration: Incorporate OpenCV library for image and video processing.
5. Email Notification: Integrate SMTP protocol for sending email notifications upon detection.
6. Database: Implement SQLite for storing detection records and configuration settings.
7. User Interface: Develop a user-friendly interface using libraries such as Tkinter or PyQt.
8. Logging: Utilize logging module for recording system activities and errors.
9. Deployment: Package the application into executable files for easy deployment.
10. Documentation: Provide comprehensive documentation including installation guide, usage instructions, and troubleshooting tips..

## System Architecture

![Screenshot 2024-04-03 225747](https://github.com/KHADAR134/Projectwork2/assets/75235233/d28fbf1d-f945-44d3-9369-2a77e8e17d31)


## Output

#### Output1 - Detection For Image

![image](https://github.com/KHADAR134/Projectwork2/assets/75235233/f6a51735-dff4-4c2f-8b1a-9548ba1c4a09)


#### Output2 - Detection For Video

![image](https://github.com/KHADAR134/Projectwork2/assets/75235233/46075a7c-9217-4fa5-ac53-7045300fe73d)

#### Output3 - Detection For Live Stream

![image](https://github.com/KHADAR134/Projectwork2/assets/75235233/d107ea80-398f-4507-becd-4bd7450e64a9)


#### Output4 - Email Notification

![image](https://github.com/KHADAR134/Projectwork2/assets/75235233/6b6a56f2-dd24-48d4-b8d1-9c2f1231bed5)


## Results and Impact
1)Implementing a YOLO-based weapon detection system in live streams and videos enhances security by swiftly identifying weapons.
2)Email notifications promptly alert authorities, enabling rapid response to potential threats.
3)Users experience heightened safety and peace of mind in public spaces and sensitive environments.
4)Real-time monitoring fosters proactive measures against violence and unlawful activities.
5)The system minimizes human error and improves overall surveillance efficacy.
6)It empowers law enforcement to intervene swiftly, preventing potential harm.
7)Public trust in safety measures is bolstered, fostering a sense of security and wellbeing.
8)Ultimately, the integration of YOLO technology enhances situational awareness and promotes safer communities.

## Articles published / References
[1] P. Mohanty, A. Tushir, and A. Patwardhan, "Weapon detection in surveillance videos using YOLO v3," in 2019 3rd International Conference on Computing Methodologies and Communication (ICCMC), 2019, pp. 1204-1208.Link: https://ieeexplore.ieee.org/document/8930745
[2]  S. E. Elmahmoud, A. E. Hassanien, and A. S. Elmahallawy, "Firearm detection in videos using deep learning," in 2019 IEEE International Conference on Systems, Man and Cybernetics (SMC), 2019, pp. 3854-3859.Link: https://ieeexplore.ieee.org/document/8914411
[3]  S. Al-Din, M. F. Fazal, and M. Arif, "Firearm detection in videos using deep learning," in 2020 8th IEEE International Conference on Engineering Technologies and Applied Sciences (ICETAS), 2020, pp. 1-6.Link: https://ieeexplore.ieee.org/document/9333619
[4]  H. Yuan, H. Xia, J. Wu, Z. Wang, and Z. Yang, "Firearm detection in surveillance videos based on YOLOv3," in 2021 4th International Conference on Mechatronics, Control and Robotics (ICMCR), 2021, pp. 242-246.Link: https://ieeexplore.ieee.org/document/9392905
[5]  A. Khokhar, M. A. Khan, M. Arif, and S. Iqbal, "Firearm detection in surveillance videos using deep learning," in 2020 IEEE International Conference on Consumer Electronics - Taiwan (ICCE-TW), 2020, pp. 1-4.Link: https://ieeexplore.ieee.org/document/9259631
[6]  S. O. Vimal, R. Rekha, and S. S. Vinay, "Gun detection using deep learning techniques," in 2021 4th International Conference on Intelligent Sustainable Systems (ICISS), 2021, pp. 2295-2300.Link: https://ieeexplore.ieee.org/document/9436266
[7]  V. Agarwal, S. M. Ak, R. Kumari, and P. Tripathi, "Firearm detection in video surveillance using deep learning techniques," in 2020 3rd International Conference on Computing, Communication and Security (ICCCS), 2020, pp. 1-6.Link: https://ieeexplore.ieee.org/document/9189023
[8]  X. Zheng, J. Zhang, and L. Zhu, "Firearm detection based on improved YOLOv3," in 2021 IEEE International Conference on Artificial Intelligence and Virtual Reality (AIVR), 2021, pp. 284-289.Link: https://ieeexplore.ie







