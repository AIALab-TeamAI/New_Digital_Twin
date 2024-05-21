# New_Digital_Twin
## 1. SETUP UNITY3D ENVIRONMENT

### 1.1. Installation and implementation - URDF files importer at [here](https://github.com/Unity-Technologies/URDF-Importer)

a. Adding the URDF package
Open the Package Manager from Unity Menu. Click Window -> Package Manager. A new package manager window will appear.

b. Click on the + sign on the top left corner of the package manager window and click on {\color{red}Add \space Package \space from \space Git \space URL}
![image](https://github.com/AIALab-TeamAI/New_Digital_Twin/assets/58129562/6368b1e7-7c03-497a-a97d-6eb8091e2a51)

c. Enter the git URL for the URDF Importer with the latest version tag (currently v0.5.2)
``` https://github.com/Unity-Technologies/URDF-Importer.git?path=/com.unity.robotics.urdf-importer#v0.5.2 ``` 
in the text box and press Enter.

d. Click Import URDF

### 1.2. Installation and implementation - ROS-TCP Connector at [here](https://github.com/Unity-Technologies/ROS-TCP-Connector)

a. Using Unity 2020.2 or later, open the Package Manager from Window -> Package Manager.

b. In the Package Manager window, find and click the + button in the upper lefthand corner of the window. Select ``` Add package from git URL....
image ```
![image](https://github.com/AIALab-TeamAI/New_Digital_Twin/assets/58129562/5dfc62e5-3b46-4d35-b16a-a32ad5940c45)

c . Enter the git URL for the desired package. Note: you can append a version tag to the end of the git url, like #v0.4.0 or #v0.5.0, to declare a specific package version, or exclude the tag to get the latest from the package's main branch.

  i.For the ROS-TCP-Connector, enter``` https://github.com/Unity-Technologies/ROS-TCP-Connector.git?path=/com.unity.robotics.ros-tcp-connector```.

  ii.For Visualizations, enter https://github.com/Unity-Technologies/ROS-TCP-Connector.git?path=/com.unity.robotics.visualizations.

d .Click Add.

To install from a local clone of the repository, see [installing a local package](https://docs.unity3d.com/Manual/upm-ui-local.html) in the Unity manual.

