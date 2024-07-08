# UAC-Bypass
3 ways of bypassing admin restrictions/uac

# Bruteforce
1. Run userbruteforce.bat
2. Press 1 and choose your target
3. Press 2 and enter your targets username
4. Enter your password list (passlist.txt for default passlist)
5. Wait...

NOTE: if it stops at a random attempt that means the password its on contains one of these characters: !><|^ (or another weird character), just delete that attempt from the file and restart

# Fake UAC Prompt
1. Close any cmd windows you got open. WinKey+R and type taskkill /im cmd.exe /f
2. Run main.vbs
3. Hide the folder (to not be sus)
4. Ask parent/teacher to help...
5. Enjoy the admin cmd!

# Bypass
This scirpt runs any program that requires admin privilages as a regular user.
For example an installer that has the UAC shield icon on it.
1. Download bypass.bat.
2. Locate the program / installer you want to execute.
3. Drag it on to bypass.bat.
4. The program will execute as user / as invoker, allowing you to run it with low privilages.
5. If you're trying to install a program with this method, you may want to change the install location to somewhere like the desktop in case you do not have access to the program files directory.

NOTE A: Don't be afraid to ask for help, post something in issues if you're lost.

NOTE B: If antivirus is detecing bypass.bat, do this with newbypass.bat
