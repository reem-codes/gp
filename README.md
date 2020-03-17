# Online Home Automation Control System
This is my graduation project. The basic idea is we wanted to make a smart home control system ourselves using raspberry pi. 

Special thanks to my teammates who helped me make this into reality:

name | email
------------ | -------------
Abeer Ezzat | abeeraaezzat@gmail.com 
Nouf AlDajani  | noufaldeajani@gmail.com
Mona AlKhathlan |  monaalsbi3y@gmail.com
Doha  AlZouhbi | dalzouhbi@gmail.com
Sarah AlHussain | sarakalhussain@hotmail.com

All of them worked hard on all parts. This project showed their skills in time management, responsibility, team-work and flexibility. Not to mention their flawless work.

## Methodology
The System is constructed from 3 components:
- **The android application**: [code here](https://github.com/reem-codes/gp_android). This mobile application works as the user interface. Its main job is sending requests and recieving responses from the server
- **The raspberry pi script**: [code here](https://github.com/reem-codes/gp_rp). This script is installed in any raspberry pi's device. Upon running, the script first check if the raspberry has been registered to the server then logs in. Otherwise, it connects to the server to register. After that, it keeps checking for new commands to execute them.
- **The web application**: [code here](https://github.com/reem-codes/gp_api). This is a REST API web application for managing communication between the androind application and the raspberry pi script.
![Methodology](https://raw.githubusercontent.com/reem-codes/gp/master/img/gp_methodology.png)


