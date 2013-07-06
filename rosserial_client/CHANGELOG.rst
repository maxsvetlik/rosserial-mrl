^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package rosserial_client
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Forthcoming
-----------
* modefied the return value of publish()
* Modefied the frame structure for serial communication, particularly add the checksum for msg_len

0.4.5 (2013-07-02)
------------------
* fail gently when messages/packages are corrupt. update print statements while at it
* Fixed a bug in ros_lib install logic which took an exception because it copied files to themselves
  Added execute permission to make_libraries.py in rosserial_embeddedlinux
  Moved examples under src in rosserial_embeddedlinux

0.4.4 (2013-03-20)
------------------

0.4.3 (2013-03-13 14:08)
------------------------

0.4.2 (2013-03-13 01:15)
------------------------
* fix build issues when in isolation by moving more stuff into make_library

0.4.1 (2013-03-09)
------------------

0.4.0 (2013-03-08)
------------------
* initial catkin version on github
* Temporary patch for `#30 <https://github.com/ros-drivers/rosserial/issues/30>`_
* Added missing math.h include.
* Changed DEBUG log level to ROSDEBUG.