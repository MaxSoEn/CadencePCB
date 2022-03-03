# CadencePCB
Setup Cadence Full for circuits and PCB Simulation

Video for setup:
    https://youtu.be/06S1MDm_Xx4

1- Extract files(Password 123)

2- Remove old versions if you setup before(Restart Computer after finish is prefered)
	-Remove "Orcad and Allegro Product"
	-Remove "License Manager"

3- Install Program 
	Select "Product Installation" and install app with default settings
		Path: "orcad\Cadence_SPB_OrCAD_17.20.000\Cadence_SPB_OrCAD_17.20.000\setup.exe"
	install "License Manager" and close "Cadence License Server Configuration" window
		Path: "orcad\Cadence_SPB_OrCAD_17.20.000\Cadence_SPB_OrCAD_17.20.000\Crack\Cadence License Manager 12.06\setup.exe"

4- Open "Cadence SPB OrCAD 17.2-2016 Crack Fixed" Folder and "C:\Cadence\"  
	Path: "orcad\Cadence_SPB_OrCAD_17.20.000\Cadence_SPB_OrCAD_17.20.000\"

4- Copy and Replce "LicenseManager" Folder and run "LicenseManagerPubKey.bat" wait...!
	Source Path: "Cadence SPB OrCAD 17.2-2016 Crack Fixed\" 
	Distenation Path: "C:\Cadence\"

5- Copy and Replce "tools" Folder and run "ToolsPubKey.bat" Wait...!
	Source Path: "Cadence SPB OrCAD 17.2-2016 Crack Fixed\"
	Distenation Path: "C:\Cadence\SPB_17.2\"

6- Copy "License.dat" 	
	Source Path: "Cadence SPB OrCAD 17.2-2016 Crack Fixed"
	Distenation Path: "C:\Cadence\LicenseManager"

7- In "C:\Cadence\LicenseManager\" open "LicenseServerConfiguration.exe" and point "License.dat" (Click Next and Finish)

8- In "C:\Cadence\LicenseManager" open "license.dat" with editor and REMOVE ONLY two lines after "DAEMON cdslmd"
		
	SERVER localhost ID = 07071982 5280
	DAEMON cdslmd
	"C:\Cadence\SPB_17.2\LicenseManager\cdslmd
	.exe" PORT=3000

Will be:

	SERVER localhost ID = 07071982 5280
	DAEMON cdslmd

9- *****Important*****

In "C:\Cadence\LicenseManager" open "lmtools.exe", select "Start/Stop/Reread" Tab and click on "Stop Server"
if you found "Unable to Stop" so you should stop service manually
	from Search bar Type "Service" and Run it as administrator 
	Find "Cadence License Manager" Right Click on it and choose "stop"

10- In "lmtools.exe" program click on "Start Server"
	you Should see "Server Start Successful" 
	if any thing else is written this mean you don't close the server so return to the previous step 

