# AutomatedProfiler

The profiler script will parse an image utilizing RegRipper, RECmd, and various PowerShell cmdlets. The output of the script will be in a text file called 'profiler.txt' and will contain information about said system such as system info, networking settings, firewall details, user data, autorun, service, and mru keys. The returned data will not provide you everything you need to do forensics on the image but it will present a lot of the data that you would find yourself looking for.<br><br>
# Usage
In order for this script to work, it will need to be in the same directory with the other supporting directories (RegRipper, RECmd, and plugins) that are included. A mounted image also needs to be available through FTK Imager.<br><br>
1) Mount an image using FTK Imager. <br>
2) Take note of the drive letter assigned to the mounted image. <br>
3) Download the script and supporting files. 
4) Unzip the contents of the zip. <br>
5) Verify that a folder called ‘profiler’ is what was unzipped.<br>
<br>
# Output
Example output from this script is in the '__example_output.txt' in this repo.
