GetSmarter
==========

To open new project
- Import project (build.gradle) into Android Studio

To Add Desktop target
- Run -> Edit Configurations...
- click the plus (+) button and select Application
- Set the Name to Desktop
- Set the field "Use classpath of module" to desktop
- Click on the button of the Main class field and select the DesktopLauncher class. 
- Set the Working directory to your android/assets/ (or your_project_path/core/assets/) folder! 
- Click Apply and then OK.

To Add iOS target
- Run -> Edit Configurations...
- click the plus (+) button and select Gradle
- Set the Name to iOS
- Select ios for the Gradle Project
- Set the Tasks to launchIPhoneSimulator or launchIPadSimulator or launchIOSDevice
- Click Apply and then OK.

