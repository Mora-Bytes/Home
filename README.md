# **K9-Software** ![K9-Software](https://github.com/K9-Software/K9-Software-LLC-Handbook-Documentation/blob/main/image1.png?raw=true)

# Code Samples

**[Start /i /b]**  This sample can be used to run two things at the same time in one window.

**[for /f "tokens=2* delims=\" %%a in ('WHOAMI /USER /GROUPS ^| findstr /c:"MicrosoftAccount" /c:"User"') do for /f "tokens=1*" %%a in ("%%a") do set Email=%%a]**  This sample can be used to get a user's email.

**[powershell -WindowStyle "hidden"]**  This sample can be used to hide the window.

**[powershell -ExecutionPolicy Bypass -Command Start-Process -FilePath """%file%""" -verb RunAs]**  This sample can be used to run %file% as admin.

# Copyright

©K9-Software All Content is reserved as the property of Mora and  K9-Software

###Where do you want to go?

######  [Mavric](https://k9-software.github.io/Mavric-Antimalware-Protection)
###### [Docs](https://k9-software.github.io/K9-Software-LLC-Handbook-Documentation)
