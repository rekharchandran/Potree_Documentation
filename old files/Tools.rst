Tools
+++++++++++
Measurement
==================================
.. image:: /images/Tools.png
   :align: center
   

Potree 3D viewer module provides several tools for measurement. This tool set consist of 12 elements. It also has controls for showing or hiding the resulting measurement labels.

Measurements are performed by use of left clicking the mouse on the desired points and right clicking is needed to terminate the process.

 
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





Azimuth
-------------------
This tool measures the azimuthal angle of a line. This line is formed by two points selected by the user, the angle is measured in degrees, clockwise from 0 to 360 and starting from the geographical north. To start a measurement, click on the azimuth icon and then click on the desired two points. The process will be automatically ended. 

Further information can also be obtained from selecting this element under the scene section.


.. raw:: html

  <center>
    <video controls src="../_static/Azimuth.mp4" width ="500" height="300"></video>
  </center>



Area
---------------------

This tool measures the horizontal area formed by a polygon. To start a measurement, click on the area icon and start clicking on the points forming the desired polygon (three or more). Right click to finish measurement. 

Further information can also be obtained from selecting this element under the scene section.

.. raw:: html

  <center>
    <video controls src="../_static/Area.mp4" width ="500" height="300"></video>
  </center>

 
Volume (cube)
---------------------

This tool measures the horizontal area formed by a polygon. To start a meaurement, click on the volume(cube) icon and click on the model to place the cube. It is possible to relocate, rescale and rotate the cube using the displayed handlers. Right click to finish the measurement.
Further information can also be obtained from selecting this element under the scene section.

.. raw:: html

  <center>
    <video controls src="../_static/Volume_cube.mp4" width ="500" height="300"></video>
  </center>



Volume (sphere)
-----------------------
This tool measures the volume formed by a sphere. To start a measurement, click on the volume (sphere) icon and click on the model to place the sphere. It is possible to relocate, rescale and rotate the sphere using the displayed handlers. Right click to finish measurement. 
Further information can also be obtained from selecting this element under the scene section.

.. raw:: html

  <center>
    <video controls src="../_static/Volume_sphere.mp4" width ="500" height="300"></video>
  </center>



Height profile
---------------------------
The tool icon that looks like a multicolored M.
This tool creates a height profile formed by a line on the model. To start a measurement, click on the Height profile icon and then form a line on the model by clicking on the desired points (two or more). 

When you mouse over the point cloud data, you should now see a red ball attached to your mouse cursor. This allows you to drop nodes and establish the location of your profile. When you want to finalize your profile double click on the last node. Once a profile is finalized, you can still change its location by clicking on the red nodes and dragging them to a different location.

Further information and options, such as ``Show 2d Profile``, can also been obtained from selecting this element under the scene section.

A profile of the lidar data should now be visible at the bottom of the screen. The profile will also update in real time if you move the profile throughout the data.

The save button in the upper right corner of the profile window will download a las file containing the points from the profile. This is useful for extracting the data you want to use for further analysis.

.. raw:: html

  <center>
    <video controls src="../_static/Height_profile.mp4" width ="500" height="300"></video>
  </center>




Annotation
---------------------------------

This tool creates an annotation label on a highlighted point on the model. To start a measurement, click on the annotation icon and then click on the desired point. The process will be automatically ended. To edit the annotation, select this element under the scene section, then edit Title and Description.

.. raw:: html

  <center>
    <video controls src="../_static/Annotation.mp4" width ="500" height="300"></video>
  </center>


Remove measurements
----------------------------------

This tool removes all measurements on the model. To remove all measurement, click on the ``Remove all measurements``  icon.



Clipping
==================================
Point cloud can be clipped by selecting an area. Clipping options include **None / Highlight / Inside /outside**.

To clip a point cloud, click on the volume clip icon, place the cube on the model and relocate, rescale, and rotate to contain the desired area. Highlight is set by default as the clipping method. 

If only the points contained within the cube needs to be displayed, click on "Inside", otherwise click on "Outside".

To remove the clipping volume or polygons click on the ``Remove all clipping volumes`` icon.


.. raw:: html

  <center>
    <video controls src="../_static/Clipping.mp4" width ="500" height="300"></video>
  </center>



Navigation
==================================
Potree 3D viewer have 4 Navigation controls which define its behavior.

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



Helicopter control
--------------------
.. image:: /images/helicopter_controls.png
   :width: 100
   
Helicopter control moves the camera as in an aircraft using the keyboard. Keys "W" and "S" moves forward and backwards, respectively restricted in a horizontal plane, while "A" and "D" moves left and right respectively. 

Also, the "R" and "F" keys moves the camera up and down. The mouse left button changes the direction of the camera, mouse wheel controls zoom, and right button moves the model in the XY axis.

The speed for these movements can be controlled using the sliding control.

Orbit Control
------------------------
.. image:: /images/orbit_controls.png
   :width: 100

Orbit Control is the default navigation behavior. The mouse left button orbits the model, the wheel controls zoom, and the right button moves the model in the XYZ axis.

.. raw:: html

  <center>
    <video controls src="../_static/orbitcontrol.mp4" width ="500" height="300"></video>
  </center>

Full extent
---------------------
Full extent button restores the model view.

Navigation cube
------------------------
Navigation cube displays a wireframe cube containing the model.

Compass
-------------------------
Compass button displays a compass on the upper right corner.



