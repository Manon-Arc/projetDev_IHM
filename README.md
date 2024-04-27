# 3D Object Control Project with Qt C++ Interface and Unity C#

### Repository

- Unity server / management: [https://github.com/Manon-Arc/IHM_Unity.git](https://github.com/Manon-Arc/IHM_Unity.git)
- Qt UI client repository: [https://github.com/Manon-Arc/IHM_Unity-Qt.git](https://github.com/Manon-Arc/IHM_Unity-Qt.git)

## Presentation
This project demonstrates the integration of a user interface developed in Qt C++ to control a 3D object visualized in Unity. The Qt user interface allows the user to manipulate the properties of the 3D object, such as its position, rotation, and instantiate GameObjects, while Unity is used to visualize the 3D object and apply the modifications in real time.

## Features

- Qt C++ user interface to control a 3D object in Unity.
- Connection system (database)
- Control of the position, and rotation of the 3D object and instantiate new GameObject.
- Real-time visualization of modifications made to the 3D object in Unity.

## Required Configuration

- [Qt](https://www.qt.io/download): Qt Creator is used to develop the user interface in C++.
- [Unity](https://unity.com/): Unity is used to visualize the 3D object and receive control commands.

## Installation

**Note for Users:**

This project has specific configuration requirements in terms of compatibility between the server and the client.

- The **Unity server** included in this project is specifically designed to run on **Windows** due to Unity's compatibility with this platform.

- The **Qt C++ client**, on the other hand, has been developed and tested on **Linux**. However, it may be possible to run it on other platforms, but this has not been tested.

**Instructions for Windows Users:**

- To run the Unity server on Windows, no additional steps are required, as Unity is natively compatible with this platform.

**Instructions for Linux Users:**

- To use the Qt C++ client on Linux, please follow these steps:
   1. Ensure you have the necessary dependencies installed on your system (Qt, CMake, etc.).
   2. Clone this repository to your local machine.
   3. Compile and run the Qt C++ client by following the instructions provided in the project documentation.

**Instructions for Windows Users Wishing to Use the Client:**

- As the Qt C++ client has been tested on Linux and may not be fully compatible with Windows, you will need to manually install gRPC on your system. Here is the link to the documentation to guide you through the installation process: [Installing gRPC on Windows](https://github.com/grpc/grpc/blob/master/BUILDING.md).

Please note that the compatibility of the client with Windows will also depend on the specific dependencies and configurations of your system.
