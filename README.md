![img](https://raw.githubusercontent.com/SpotX-CLI/SpotX-commons/main/.github/Pic/Logo/logo-win.png)

**[
SpotX-Win](https://github.com/SpotX-CLI/SpotX-Win)** for Chinese users 



Chinese users normally have problems fetching ***Install.1.ps1*** thus their attempts may be in vail.





### Before the installation

1. **Disable anti-virus software**, for example, 360 Safeguard.

2. Ensure you can **execute PowerShell scripts**. Check it based on this article [How to Enable PowerShell Scripts Execution on Windows 10](https://windowsloop.com/enable-powershell-scripts-execution-windows-10/).

   ------

   **To make the long story short...**

   ```
   To enable PowerShell scripts, follow the steps given below one after the other.
   
   1. Press the Windows Key to open the Start menu.
   2. Type “PowerShell“.
   3. Right-click on the PowerShell result and select “Run as administrator“.
   4. After opening the PowerShell window, execute “get-executionpolicy” to know the current execution policy.
   5. Chances are it will say “Restricted“. This means the scripts are blocked.
   6. In the PowerShell window, execute the “set-executionpolicy remotesigned” command.
   7. Type “A” next to the confirmation message and press “Enter“.
   8. Execute the “set-executionpolicy unrestricted” command in the PowerShell window.
   ```

   





### How to install

1. Download this repo as a zip file, decompress then switch to the destination output folder.![DownloadZIP_Instruction](C:\Users\AndyC\Downloads\Compressed\Spotify_AD-Blocker_for_Windows_August_23,_2022\DownloadZIP_Instruction.png)

2. Run ***Install.bat*** then wait until it's finished.

3. Enjoy!

    





