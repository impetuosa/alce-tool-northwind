# Alce: Predicting Software Migration

In the following [link](https://www.dropbox.com/s/zvwobrbindggh0o/Alce-Northwind.zip?dl=0) [^1] you are going to find a Alce tool loaded with a modified version of Microsoft Northwind traders[^2]. 
The modification of this version of Northwind consist in using Microsoft Access tooling to transform all macros into VBA code. 
We require to do this because our tool does not do reverse engineering on Macros

## Getting Pharo 
  Alce is a tool built on top of Moose [^3] platform. 
  Moose is built on the Pharo language [^4] 
  For getting started you must [download](https://www.pharo.org/download)[^4] first a pharo launcher according to your operative system.
  If you are a pharo user, the image in the zip file works with a Pharo 10 virtual machine. 
  
## Importing Alce
  Unzip the Alce-Nortwind.zip file in a place easy to find of your file system. 
  
  Start the pharo launcher. 
  In the pharo launcher toolbar you will find an *import* button.
  Click on the import button. Choose the second option "Import the image directory". 
  A file dialog will open. Navigate to to the unzipped folder. And click on the file "Alce-Northwind.image"
  This process should add a new entry in your pharo launcher named Alce-Northwind. 
 
## Starting Alce 

  After importing Alce into your pharo launcher you must have, in the list below the tool bar, a new entry named Alce-Northwind. 
  Double click the entry (or click over it and push the button "Launch"). 
  The first time you need to have an internet connection, for the pharo launcher to download the propoer virtual machine. 
  Right after a new window will open presenting a Pharo image with the Alce tool opened.


## Using Alce 
   On the left part of the tool, there is a tool bar. Under the tool bar there are three entries named: "Architecture", "Pie complexity", "Pareto complexity". 
   These three entries are three different perspectives previously configured by my self to ease the usage. 
   However, if you want to play a bit more, do not hesitate in adding new perspectives with the last button of the tool bar. 
   
   Once you finished, to quit Pharo you must click on the Pharo entry of the system toolbar (located on the top of the window). 
   There you will find two quitting options: Quit and Save & Quit. 
   If you quit without saving, the next time you open the application is going to be in the same status as you found it when you opened.
   If you quit saving, the next time you open the application is going to be in the same status as it is right now.
   
   

## Troubleshooting

  Please if you find any problem on the process do not hesitate sending me an email or adding an issue in this repository.
  Ill be pleased to help you on testing the tool.


  [^1]: https://www.dropbox.com/s/zvwobrbindggh0o/Alce-Northwind.zip?dl=0
  [^2]: https://learn.microsoft.com/en-us/power-apps/maker/canvas-apps/northwind-install
  [^3]: https://modularmoose.org/
  [^4]: https://pharo.org/download
