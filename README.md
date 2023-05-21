Instructions:
1. Follow the instruction in the sb_web_app folder to start a HTTP and ROS server within your ROS setup for survivor buddy. Turn on the Camera.
2. Run 'python3 sb_project.py'.

Description:
The file sb_project.py has the implementation of 4 Behaviors - Attention, Mirroring Face, Youtube Interaction and Dance.

Observer pattern has been used to implement this. Its brief working is explained below: 
1. In this a subject like Camera Perception will notify its observers when it gets a new image. 
2. The notification from the subject updates the values at the observers like Face Cartographer to process the image for face recognition.


![image](https://github.com/Sushant369/Survivor_Buddy_Hybrid_Delibrative-Reactive_Architecture_for_subsystems/assets/72655705/09c13ced-0368-4ccc-87f6-91bdc5fc77b2)


![image](https://github.com/Sushant369/Survivor_Buddy_Hybrid_Delibrative_Architecture/assets/72655705/0b068cbf-4bcc-4741-837c-a36b129a8cf4)

![image](https://github.com/Sushant369/Survivor_Buddy_Hybrid_Delibrative_Architecture/assets/72655705/c9fa8568-346b-460e-87c7-2901c51187cd)

![image](https://github.com/Sushant369/Survivor_Buddy_Hybrid_Delibrative_Architecture/assets/72655705/44207e99-107c-4f24-a53c-1b6752cd8127)

![image](https://github.com/Sushant369/Survivor_Buddy_Hybrid_Delibrative_Architecture/assets/72655705/94b1c68d-f70c-4860-9706-ef1afc505b53)

