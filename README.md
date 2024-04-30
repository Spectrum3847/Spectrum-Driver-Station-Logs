
# How To Use
## Setup AdvantageScope for 3847-2024 logs
1. Open AdvantageScope 2024
     - AdvantageScope is included in [WPIlib tools](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/wpilib-setup.html) so any computer with the tools already has the application
2. Import layout to see especially relevant log data  
   - Look to taskbar at top left of AdvantageScope
        - File
          - Import Layout
            -   **Navigate** to the [layout.json](2024 Robot Logs/2024 AdvantageScope Configs/assets/layout.json) in 2024 AdvantageScope Configs
3. Import the 2024 UltraViolet model for viewing poses in 3D fields
   - Look to taskbar at top left
     - Help
       - Show Assets Folder
         - **Copy** [Robot_UltraViolet](2024 Robot Logs/2024 AdvantageScope Configs/assets/robot model/Robot_UltraViolet) folder into userAssets folder
> [!NOTE]
> AdvantageScope may need to be restarted after adding the robot model to the userAssets folder
> [!NOTE]
> Layout may include fields that were not yet created in older versions of logs. This layout was used at 2024 worlds and states

## View Log Files
1. Select log file for a match from the [2024 logs folder](2024 Robot Logs)
   - Look to taskbar at top left
     - File
       - Open
         - **Navigate** to desired log file
2. Select UltraViolet for 3D pose field
   - Look to field taskbar above the timeline
     - Pose Debug (3D Field)
       - Config (bottom right)
         - Robot: 
           - **Select** UltraViolet from dropdown
3. [Optional] View logs synchronized with the match footage from Blue Alliance
   - **Copy** the corresponding YouTube match footage URL to clipboard from [TBA](https://www.thebluealliance.com/team/3847) 
   - Look to field taskbar above the timeline
     - Match Footage [optional] (Video) 
       - Choose Source:
         - **Hit** red clipboard button and wait for AdvantageScope to automatically synch the video with the logs so they play together
> [!NOTE]
> Match logs end in **_p**/**_q**/**_e**<<f>**match number**>. Anything else is a log of the robot at home / practice field / in pit

