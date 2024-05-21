# New_Digital_Twin
## 1. SETUP UNITY3D ENVIRONMENT

### 1.1. Installation and implementation - URDF files importer at [here](https://github.com/Unity-Technologies/URDF-Importer)

a. Adding the URDF package
Open the Package Manager from Unity Menu. Click Window -> Package Manager. A new package manager window will appear.

b. Click on the + sign on the top left corner of the package manager window and click on Add Package from Git URL.

c. Enter the git URL for the URDF Importer with the latest version tag (currently v0.5.2)
``` https://github.com/Unity-Technologies/URDF-Importer.git?path=/com.unity.robotics.urdf-importer#v0.5.2 ``` 
in the text box and press Enter.

d. Click Import URDF

### 1.2. Installation and implementation - ROS-tcp Connector at [here](https://github.com/Unity-Technologies/ROS-TCP-Connector)

a. Using Unity 2020.2 or later, open the Package Manager from Window -> Package Manager.

b. In the Package Manager window, find and click the + button in the upper lefthand corner of the window. Select ``` Add package from git URL....
image ```

c . Enter the git URL for the desired package. Note: you can append a version tag to the end of the git url, like #v0.4.0 or #v0.5.0, to declare a specific package version, or exclude the tag to get the latest from the package's main branch.

d. For the ROS-TCP-Connector, enter ``` https://github.com/Unity-Technologies/ROS-TCP-Connector.git?path=/com.unity.robotics.ros-tcp-connector```.
g. For Visualizations, enter https://github.com/Unity-Technologies/ROS-TCP-Connector.git?path=/com.unity.robotics.visualizations.
e .Click Add.

To install from a local clone of the repository, see installing a local package in the Unity manual.

