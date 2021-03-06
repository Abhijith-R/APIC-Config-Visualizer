[![published](https://static.production.devnetcloud.com/codeexchange/assets/images/devnet-published.svg)](https://developer.cisco.com/codeexchange/github/repo/Abhijith-R/APIC-Config-Visualizer)

# APIC-Config-Visualizer
 Project to visualize APIC configuration data using GoJS graph library. It is hard to visulise APIC config on APIC dashboard as the object are listed down in a tree structure. This app helps visualise these objects in a graph which help the user to undertsand the object and trace the object graphically in turn help in debugging.

#### Author:

* Abhijith R (abhr@cisco.com)
*  July 2019
***

#### Prerequisites
* Python 3.X and its libraries mentioned in requirements.txt
* PyCharm/Any text editor
* Flask

#### Steps to Reproduce
* Download/clone the repository
* Import the code into a text editor suck as pycharm
* Make sure all the dependencies are satisfied as mentioned in requirements.txt
* Open controller.py file and make necessary changes as mentioned in the comments
* Import the virtual env(apic_python) into your development environment or you can setup your own with the necessary libraries
* After necessary changes are made to the code as specified in the comments, execute/run main.py file on the editor or on the terminal and click on the URL (http://0.0.0.0:5001)
* If running on terminal use the following commands
```export FLASK_APP=main.py```
```flask run```

#### Screenshot
![alt text](https://github.com/Abhijith-R/APIC-Config-Visualizer/blob/master/APIC_visualizer.png)

#### API Reference/Documentation:
* [Cisco APIC REST API](https://www.cisco.com/c/en/us/td/docs/switches/datacenter/aci/apic/sw/2-x/rest_cfg/2_1_x/b_Cisco_APIC_REST_API_Configuration_Guide/b_Cisco_APIC_REST_API_Configuration_Guide_chapter_01.html)
* [GoJS graph library Docs](https://gojs.net/latest/samples/ldLayout.html)

#### DISCLAIMER:
<b>Please note:</b> This script is meant for demo purposes only. All tools/ scripts in this repo are released for use "AS IS" without any warranties of any kind, including, but not limited to their installation, use, or performance. Any use of these scripts and tools is at your own risk. There is no guarantee that they have been through thorough testing in a comparable environment and we are not responsible for any damage or data loss incurred with their use.
You are responsible for reviewing and testing any scripts you run thoroughly before use in any non-testing environment.

