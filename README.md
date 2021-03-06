# Tethered Auto Focus and Capture with single keystroke Script for C1Pro 20
Prior to the release of C1Pro, when tethered, you could click on Apple Command + k or any edit keyboard shortcut to auto focus and fire the camera at the same time. In Captue One 20, it's a 2 step process. Although this might not seem like a big problem to click on 2 keys, it could cause a problem forgetting to always focus first and then shoot.

I have created an Apple Script for C1Pro 20 that will allow you to use a single keyboard command.

First, in C1Pro you will need to setup the edit keyboard shortcut for "Start/Stop Camera Autofocus". In this case I designated "." for auto-focus, but you can use any character. If you choose to use a different character than ".", reflect that in the line script. Open The Scripts folder inside C1Pro, add the script and Update Scripts Menu. You should now see the script "Focus_Shoot" in the menu.

Next open System Preferences and select Keyboard. Inside Keyboard pick the Shortcuts tab. Select App Shortcuts from the list on the left, and add an app shortcut for Capture One 20 by clicking on the + button. The shortcut is matched to a "Menu Title" where different menu levels are indicated by -> without spaces. The path should look like the following:

Scripts->Focus_Shoot
For the "Keyboard Shortcut", I used F19. I used F19. Note: the only single keystrokes you can enter are Function keys.



Another option is to use Keyboard Maestro with my script which will allow you to use any SINGLE key instead of Apple's Keyboard Shortcuts that require a key combination or only a Function key. I know some studios like to use the "Enter" key" which is all the way to the right on a full-size keyboard. Here is the KM macro w/ the script embedded (Focus Shoot.kmmacros). Remember, in C1Pro you will need to set up the edit keyboard shortcut for "Start/Stop Camera Autofocus". In this case I designated the period "."
