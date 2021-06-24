# MSWinProdKeyRecovery
VB Script for recovering an OEM Manufacturers MS Windows Vista-Win11 Product Key 

//////////////////////////////////////////
How to use:
1. Download/clone this repo - or simply copy the VBS file "WinProductKey-reveal.vbs" - Save to a location which you can find easily such as the Windows Desktop.
2. Double Click the file
3. A new window will appear revealing your original Windows Product Key.
4. enjoy.

//////////////////////////////////////////
Note:

This script pulls the key from the local Windows Registry.
Older laptops/PC's which do not have UEFI Bios's cannot store the Windows Product Key in the bios location. 
To recover a Windows Product key from a modern BIOS based system, use the following command from an **Admin** Command prompt or Admin Powershell session:
  C:\wmic path softwarelicensingservice get OA3xOriginalProductKey
  
  
