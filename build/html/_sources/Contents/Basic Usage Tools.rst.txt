Basic Tools
+++++++++++
Information Bar
==================================
.. image:: /images/informationbar.png
   :align: center
   

Information bar is displayed at the top right corner of the screen. This is where you can find details about the data set.
At the top it shows the name the county followed by Muncipality name. The numer in white denotes the dataset name. The other details availbale are the time stamps, Number of points and the length of the dataset.


Measurements
==================================
 
Angle
------------------------       
.. image:: /images/angle.png
   :width: 100

This tool measures the tridimensional angle formed by the lines connecting three points.To start a measurement, click on the angle icon, then left click on the third point and the process will be automatically ended.


.. raw:: html

  <center>
    <video controls src="../_static/Angle.mp4" width ="500" height="300"></video>
  </center>



Point
------------------------
.. image:: /images/point.png
   :width: 100

This tool highlights a selected point and display its XYZ coordinate. To start a measurement, click on the point icon, then click on the desired point and the process will be automatically ended. 


.. raw:: html

  <center>
    <video controls src="../_static/Point.mp4" width ="500" height="300"></video>
  </center>



Distance
------------------------
.. image:: /images/distance.png
   :width: 100

This tool measures the tridimensional distance of the lines connecting a series of points. To start a measurement, click on the distance icon and start clicking on the desired points (two or more). Right click to finish measurement.

Further information such as total length can also be obtained from selecting this under the scene section.


.. raw:: html

  <center>
    <video controls src="../_static/Distance.mp4" width ="500" height="300></video>
  </center>




Height
----------------------
.. image:: /images/height.png
   :width: 100

This tool measures the height or vertical distance between two points. To start a measurement, click on the height icon and then click on the desired two points. The process will be automatically ended. 
Further information can also be obtained from selecting this element under the scene section.

.. raw:: html

  <center>
    <video controls src="../_static/Height.mp4" width ="500" height="300"></video>
  </center>





Circle
-----------------
.. image:: /images/circle.png
   :width: 100

This tool measures the radius of a circle formed by three points. To start a measurement, click on the circle icon and then click on the desired three points. The process will be automatically ended. 

Further information such as Circumference can also be obtained from selecting this element under the scene section.

.. raw:: html

  <center>
    <video controls src="../_static/Circle.mp4" width ="500" height="300"></video>
  </center>


Navigation
==================================

Earth Control
----------------------------------
.. image:: /images/earth_controls_1.png
   :width: 100

Earth control navigated as anchored to the ground. Mouse left button moves the model horizontally, mouse wheel controls zoom, and right button orbits the model.

.. raw:: html

  <center>
    <video controls src="../_static/earthcontrol.mp4" width ="500" height="300"></video>
  </center>

Fly control
----------------------------------
Fly control moves the camera as in birds eye using the keyboard. Keys "W" and "S" moves forward and backwards, respectively and in the direction of the camera, while "A" and "D" moves left and right respectively. 

Also, the "R" and "F" keys moves the camera up and down. The mouse left button changes the direction of the camera, mouse wheel controls zoom, and right button moves the camera in the XYZ axis.

The speed for these movements can be controlled using the sliding control.

.. raw:: html

  <center>
    <video controls src="../_static/flycontrol.mp4" width ="500" height="300"></video>
  </center>


Point Budget
==================================

The point budget limits the number of points loaded and rendered at any given time, which helps to adapt performance requirements to the capabilities of different hardware. It gives you a complete version of point clouds.

Recommended values are between 500.000 and 10.000.000.

.. raw:: html

  <center>
    <video controls src="../_static/Pointbudget.mp4" width ="500" height="300"></video>
  </center>


360 Images
==================================
360 Imagess allow you to see actual images of the point cloud.These images are displayed as white sphere in the viewr, click on any of them to enter it. This view will give you an overlook on how the territory looked like and what objects could be captured. 

360 Images can add meaningful context to collected data and fill in the information lacking in the point cloud.

.. raw:: html

  <center>
    <video controls src="../_static/360image.mp4" width ="500" height="300"></video>
  </center>


Display Options
==================================

RGB
----------------------------------
RGB display each point based on the original scan colors


Intensity
----------------------------------
Display each point based on the laser pulse return intensity value. Scanners identify an intensity value for each point during the capture process. Intenisity is a measure of point reflectivity, which can vary depending upon color, surface texture, surface angle and the environment.


.. raw:: html

  <center>
    <video controls src="../_static/RGB.mp4" width ="500" height="300"></video>
  </center>

