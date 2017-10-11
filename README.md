# openproj-w
A modified OpenProj can display week number and export to PNG and open the project file by double clicking it

Like Openproject (another OpenProj-modified one), only the modified files in this openproj-w are available under BSD license - all other code belongs to the Projity corporation.

The modified files includes:

   1818 ExtendedDateFormat.java  
  13628 GraphPageable.java  
 103893 GraphicManager.java  
   8351 SpreadSheetRenderer.java  
  11414 TimeScale.java  
  56680 client.properties  
  36362 configuration.xml  
  40683 menu.properties  

The modifications to the original OpenProj-1.4 includes:

* Display week numbers in the Gantt chart

![](http://openproj-w.googlecode.com/files/week_number_display.png)

* Export to the PNG image (This function is from the Openproject, thank benderamp!)
  As stated in the Openproject, This might be useful, when you want to show diagrams created in openproj on the computer where OpenProj is not installed (or paste it to some kind of presentation or something).

![](http://openproj-w.googlecode.com/files/export_to_PNG.png)

* A modified openproj-w.bat file which can launch OpenProj by simply double-clicking the OpenProj project file in the file explorer.  

  java -Xms128m -Xmx768m -jar D:\Temp\openproj-w\openproj-1.4\openproj.jar %~f1  
                              ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^  

Note that you have to modify the ^ part in the above statement according to your openproj-w installation folder, and then you can use this openproj-w.bat to open the OpenProj project file by double clicking that file in the file explorer.
