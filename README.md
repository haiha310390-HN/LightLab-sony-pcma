LightLab is an app that runs on Sony cameras.
sony nex 5R, 5T, 6 . sony a6000, a6300, a6500 , a5000, a5100. Sony A7 , A7R, A7S, . Sony A7II, A7RII, A7SII

If you have any questions or encounter any issues/errors during the installation process, please feel free to reach out via email at: haiha310390@gmail.com for assistance. Or ZALO +84.985016729 (Viet Nam)


Extract and copy the CUBE folder to the memory card, ensuring that the CUBE folder is not located inside any subfolders. Once you open the application, you will immediately see those color presets without needing to install anything else

APK Installation Guide via pmca-gui
1. Prerequisites
Required Software & Files:

Download pmca-gui-v0.18-win.exe from the official project releases page on GitHub.

Prepare the .apk file you want to install on your camera (e.g., utility apps, custom UI tools, or pmcaFilesystemServer).

Hardware Requirements:

A reliable USB cable (using the original cable that came with the camera is recommended to ensure stable data transfer).

A compatible Sony camera running the Android-based app subsystem, with an SD card inserted.

Camera Setup:

Turn on the camera, go to Menu -> Setup -> locate USB Connection, and set it to Mass Storage (or MTP depending on your camera model).

2. Step-by-Step Installation
   
Step 1: Launch the tool

Double-click pmca-gui-v0.18-win.exe on your Windows PC (right-click and select Run as administrator if prompted).

Step 2: Connect the camera

Connect your Sony camera to the computer using the USB cable.

The software will automatically scan and detect your camera details once successfully connected.

Step 3: Navigate to the Install tab

On the pmca-gui interface, switch over to the Install tab.

Step 4: Select the APK file

Click the file browse option (e.g., Select an apk / Install app from file).

Locate the prepared .apk file on your computer and click Open.

Step 5: Start installation

Click Install to begin pushing the application to the camera's system partition.

Wait a few moments until the completion message appears on your screen.

Step 6: Verify on camera

Safely disconnect the USB cable.

Turn on your camera, go to the Application List (or app manager) to launch and use your newly installed application.

3. Troubleshooting Connection Issues
If the software fails to detect the camera or throws a connection error, it is usually caused by missing Windows USB drivers:

Download and install the driver utility Zadig.

Open Zadig, select your Sony device from the list, choose the libusb-win32 driver, and click Install Driver. Afterward, restart pmca-gui.

4. Important Notes
Check Battery Level: Ensure your camera's battery is charged above 50% to prevent sudden power loss during the transfer, which could cause system glitches.

Recovery: Since this tool interacts with the camera's subsystem via open-source methods, if you experience app conflicts or display glitches, performing a Factory Reset from the camera's menu will safely restore your camera to its default state.
