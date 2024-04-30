
# How To Use
## Setup AdvantageScope for 3847-2024 logs
1. <span style="color: #8267b9;">Open AdvantageScope 2024</span>
     - AdvantageScope is included in [WPIlib tools](https://docs.wpilib.org/en/stable/docs/zero-to-robot/step-2/wpilib-setup.html) so any computer with the tools already has the application
2. <span style="color: #8267b9;">Import layout to see especially relevant log data</span>
   - Look to taskbar at top left of AdvantageScope
        - File
          - Import Layout
            -   **Navigate** to the [layout.json](https://github.com/Spectrum3847/Spectrum-Driver-Station-Logs/blob/main/2024%20Robot%20Logs/2024%20AdvantageScope%20Configs/assets/layout.json) in 2024 AdvantageScope Configs
3. <span style="color: #8267b9;">Import the 2024 UltraViolet model for viewing poses in 3D fields</span>
   - Look to taskbar at top left
     - Help
       - Show Assets Folder
         - **Copy** [Robot_UltraViolet](https://github.com/Spectrum3847/Spectrum-Driver-Station-Logs/tree/main/2024%20Robot%20Logs/2024%20AdvantageScope%20Configs/assets/robot%20model/Robot_UltraViolet) folder into userAssets folder
> [!NOTE]
> AdvantageScope may need to be restarted after adding the robot model to the userAssets folder

> [!NOTE]
> Layout may include fields that were not yet created in older versions of logs. This layout was used at 2024 worlds and states

## View Log Files
1. <span style="color: #8267b9;">Select log file for a match from the</span> [2024 logs folder](https://github.com/Spectrum3847/Spectrum-Driver-Station-Logs/tree/main/2024%20Robot%20Logs)
   - Look to taskbar at top left
     - File
       - Open
         - **Navigate** to desired log file
2. <span style="color: #8267b9;">Select UltraViolet for 3D pose field</span>
   - Look to field taskbar above the timeline
     - Pose Debug (3D Field)
       - Config (bottom right)
         - Robot: 
           - **Select** UltraViolet from dropdown
3. <span style="color: #8267b9;">[Optional] View logs synchronized with the match footage from Blue Alliance</span>
   - **Copy** the corresponding YouTube match footage URL to clipboard from [TBA](https://www.thebluealliance.com/team/3847) 
   - Look to field taskbar above the timeline
     - Match Footage [optional] (Video) 
       - Choose Source:
         - **Hit** red clipboard button and wait for AdvantageScope to automatically synch the video with the logs so they play together
> [!NOTE]
> Match logs end in **_p**/**_q**/**_e**<<f>**match number**>. Anything else is a log of the robot at home / practice field / in pit

> [!IMPORTANT]
> If you have any questions about what a specific field that we log is just ask!