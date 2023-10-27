# Being real goofy with windows part 1.
> [!IMPORTANT]
> Again Please provide feedback its super valuable & BE HONEST ABOUT IT. Thanks.

- Services that should be stopped for extra goofyness aka performance. Make script named Goofy disable & Goofy Enable for the 3 windows processors. Run script only when game is opened. DONT RUN SCRIPT WHEN MULTI TASKING! MAKE A REBOOT SCRIPT TO REPLACE CMD METHOD

- Testing if these 3 services disabled allows cmd to be visible. Failed

- Method 1 restarting pc: Best because of the uptime & it restarts it.
1. When you have closed your game Press control + shift + esc to open task manager.
2. Navigate to the top, click on file, run new task.
3. Type [explorer.exe]() then enter.
4. control + R type [cmd]() & click enter.
5. In command prompt type [shutdown.exe /r /t 0]() THIS RESTARTS PC!
6. After boot it will be back to normal.

- Method to fix the goofy look:
4. Do the same for the other 2 services. Find name for them i need to.

- The 3 windows services
1. Windows explorer 

2. fontdrvhost.exe

3.


taskkill /F /IM explorer.exe
taskkill /F /IM fontdrvhost.exe
timeout /t 10
start explorer.exe
start fontdrvhost.exe
