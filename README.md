# CCST9049_2C3_Project_II
This is the group project II of CCST9049, where we use Unity VR for Meta Quest 3 artwork creation
Acknowledgement: We relied on Unity's Tutorial for VR development on Meta Quest 3. For more details please view https://developer.oculus.com/documentation/unity/unity-tutorial-hello-vr/.

How to build our project?
1. Clone this project, the total size is over 6.9 GB
   ```python
   git clone https://github.com/SILENT-GUO/CCST9049_2C3_Project_II.git
   ```
2. Download Unity on your platform.
3. In Unity Hub, Choose Add Project from Disk and select **Unity-StarterSamples** folder
4. After opening the unity editor, make sure you have downloaded [Meta XR All-in-One SDK](https://developer.oculus.com/documentation/unity/unity-tutorial-hello-vr/) and [Meta XR Audio SDK](https://assetstore.unity.com/packages/tools/integration/meta-xr-audio-sdk-264557) from package manager.
5. After connecting the XR device with your computer, press File -> Build Settings -> Select SampleScene1 and Android Platform -> Switch Platform (If needed) -> Build and Run. By this the built file CCST9049_2C3_Project_II.apk with be copied to Quest device. You can also find this apk in Unknown sources of application folder.
6. To view the scene of our project, select File -> Open Scene, Select "CCST9049_2C3_Project_II\Unity-StarterSamples\Assets\StarterSamples\Usage\Usage\SampleScene1.unity".

Although the apk file is ignored by git unity when uploading, we seperately upload CCST9049_2C3_Project_II.apk in the root directory. You can also use SideQuest to install this apk file from local computer to Quest device.
