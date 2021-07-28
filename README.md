# Universal AutoIT Extractor and De-obfuscator
<center>
<b>Before use this tool I must warn you, that this tool should be used in VM (Virtual Machine), you can use it on a real OS, but I won't be responsible for any damage! You take responsibility for using this tool.</b>
<br>
<br>
Also, some of the tools used are detected and blocked by some AV, so, please consider use the VM (eventually with AV disabled), or disable the AV for your own risk, if it won't work with any AutoIT compiled programs.
<br>
<br>
<b>Q</b>: Is the restarting the OS is really needed?<br>
<img src="https://i.imgur.com/YtcMiOu.png" alt="Reboot the OS is really needed">
<b>A</b>: Yes, for firmly protected programs restarting the OS is really needed because of the missing device, the device will be available after restarting the OS. So, also because of that you should use the VM, instead of real OS.<br>
<br>
<br>
Before restarting the OS, script adds itself to the run section for current user, so, it will be automatically executed after the OS starting again with current file to extract.
<br>
If you want to remove the the auto-execution after OS restarting, just execute it again and close - it will delete the run entry. For example, if you change decision.
<br>
<br>
I saw that some scripts after extraction has some function with random name before the "#NoTrayIcon", you need to comment it or delete, if the script does not work after compilation.
<br>
<br>
By the way, I added that now it saves All Resources of *.exe to a *.res file - use the "Resource Hacker" after re-compilation, to import all resources from extracted *.res file (with overwrite) for the newly compiled file.
<br>
<br>
<b>Please take in mind that some AutoIT compiled programs can be dangerous for your OS and/or for the files you have!</b>
</center>
