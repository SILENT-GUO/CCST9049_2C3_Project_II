# CCST9049_2C3_Project_II

This is the group project II of CCST9049, where we use Unity VR for Meta Quest 3 artwork creation.

Group Member: (Alphabetical Order)
- Dong Huaiwen
- Guo Zebin
- Zhang Shenru
- Zhou Ziyue

Acknowledgement:
- We relied on Unity's Tutorial for VR development on Meta Quest 3. For more details please view https://developer.oculus.com/documentation/unity/unity-tutorial-hello-vr/.

Where does our scenes and materials come from?
- Most of the scenes and materials are all built from scratch in Blender. The model of trees are downloaded from [Internet](https://www.turbosquid.com/3d-models/lowpoly-trees-carrot-crystal-1189852).

How to build our project?
1. Clone this project, the total size is over 6.9 GB
   ```python
   git clone https://github.com/SILENT-GUO/CCST9049_2C3_Project_II.git
   ```
2. Download Unity on your platform. Remember to tick Android SDK when installing Unity editor.
3. In Unity Hub, Choose Add Project from Disk and select **Unity-StarterSamples** folder
4. After opening the unity editor, make sure you have downloaded [Meta XR All-in-One SDK](https://assetstore.unity.com/packages/tools/integration/meta-xr-all-in-one-sdk-269657) and [Meta XR Audio SDK](https://assetstore.unity.com/packages/tools/integration/meta-xr-audio-sdk-264557) from package manager.
5. After connecting the XR device with your computer, press File -> Build Settings -> Select SampleScene1 and Android Platform -> Switch Platform (If needed) -> Build and Run. By this the built file CCST9049_2C3_Project_II.apk with be copied to Quest device. You can also find this apk in Unknown sources of application folder.
6. To view the scene of our project, select File -> Open Scene, Select "CCST9049_2C3_Project_II\Unity-StarterSamples\Assets\StarterSamples\Usage\Usage\SampleScene1.unity".

Trouble Shooting:
+ If you encounter any problems related to building our project, please refer to the [official startup tutorial](https://developer.oculus.com/documentation/unity/unity-tutorial-hello-vr/) as your first step. If your problem remains unresolved, feel free to open issues and contact us!

P.S. As the apk file is ignored by git unity when uploading and its size is larger than 25 MB, we decided not to put the apk file here. You may access the apk file via this [google drive link](https://drive.google.com/file/d/1ntohamSag3WV3QVLWNyJKnFVvTjU9Adh/view?usp=drive_link)
