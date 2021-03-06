========================================================
Portable Python with Robot Framework (for Magik testing)
========================================================

Intention
=========

This collection of open source software is a portable (standalone) installation of the test 
automation framework `Robot Framework`_.

It is named **PortablePythonWithRobot** (PPR) and includes

- the `Portable Python`_ core
- the `Robot Framework`_ `standard test libraries`_ and `RIDE`_ test data editor 
- the `Selenium2Library`_ for web testing and 
- the `Robot Framework Magik`_ extension for testing Smallworld Magik images.
- the `PyScripter`_, a Python Integrated Development Environment (IDE) 

Hope this helps you in your daily work in testing the interacting of Smallworld GIS with 
web applications or other systems.

Have fun with tests, 16. Dec. 2015
`Luiko Czub`_

Download & Installation
=======================

The installer can be retrieved from `GitHup Releases`_ or `SourceForge`_.

Changes are documented in `CHANGES <CHANGES.rst>`_.

Known Problems
--------------

If PPR should be used to start and test Smallworld Magik images, please choose an installation path name without spaces. Details `issue 2 <https://github.com/lczub/PortablePythonWithRobot/issues/2>`_.

First start of PyScripter prompts an error "C:\App not found", but continues.

Directory Layout
================

App/
    `Portable Python`_ installation with `Robot Framework`_, `Ride`_ and `Selenium2Library`_
	
logs/
    default log directory

robot/
    resources like `Robot Framework Magik`_, RobotDemo_, WebDemo_, `Robot Emacs Mode`_
	
MyMagikTests/
    place for your own tests and keyword definitions	
	
run_*_robot_tests.bat
    examples, how to start robot tests
	
start|stop_*.bat
    helper scripts, needed by the examples	
	
ride_*_robot_tests.bat
    examples, how to open RIDE test data editor
	
Documentations
==============

- Robot Framework User Guide `<robot/docs/robotframework-userguide-2.9.2/RobotFrameworkUserGuide.html>`_
- keywords standard test libraries `<robot/docs/robotframework-userguide-2.9.2/libraries>`_
- keywords Selenium2Library `<robot/docs/Selenium2Library.html>`_
- keywords Robot Framework Magik Base `<robot/docs/robot_magik_base.html>`_
- keywords Robot Framework Magik DsView `<robot/docs/robot_magik_dsview.html>`_
- Python 2.7.10 documentation `<App/doc/python2710.chm>`_
- PyScripter Manual `<App/PyScripter.chm>`_

Package Details
===============

============= ============================ ============================
Package Name  `Portable Python`_           Python_
Version        2.7.10.1 (customized)       2.7.10 (32bit)
License       `MIT License`_               `Python License 2.0`_
============= ============================ ============================

============= ============================ ============================
Package Name  `PyScripter`_  
Version        2.6.0    
License       Open Source Software                
============= ============================ ============================

============= ============================ ============================
Package Name  `Robot Framework`_           `Selenium2Library`_
Version        2.9.2                       >= 1.7.4
License       `Apache License 2.0`_        `Apache License 2.0`_
============= ============================ ============================

============= ============================ ============================
Package Name  `Ride`_                      `wxPython`_
Version        1.5                         2.8.12.1
License       `Apache License 2.0`_        `wxWindows Library Licence`_
============= ============================ ============================
                                       
============= ============================ ============================
Package Name  `Robot Framework Magik`_     `Robot Emacs Mode`_
Version        0.3.2                        ---
License       `Apache License 2.0`_        `GPL 3.0`_
============= ============================ ============================

============= ============================ ============================
Package Name  `RobotDemo`_                 `WebDemo`_
Version        20150901                     20150901
License       ---                          ---
============= ============================ ============================

This site is written in reStructuredText_ and converted into HTML with 
`reStructuredText online renderer`_.


.. _Luiko Czub: mailto://luiko.czub@liegkat-archiv.de
.. _Robot Framework: http://robotframework.org/
.. _standard test libraries: http://robotframework.org/#test-libraries
.. _Selenium2Library: https://github.com/rtomac/robotframework-selenium2library/#readme
.. _RIDE: https://github.com/robotframework/RIDE/wiki/How-To
.. _wxPython: http://wxpython.org
.. _Robot Framework Magik: https://github.com/lczub/robotframework-magik/#readme
.. _Portable Python: http://portablepython.com/
.. _RobotDemo: https://bitbucket.org/robotframework/robotdemo/wiki/Home
.. _WebDemo: https://bitbucket.org/robotframework/webdemo/wiki/Home
.. _Robot Emacs Mode: https://github.com/sakari/robot-mode/#readme
.. _Python: http://python.org/
.. _MIT License: http://opensource.org/licenses/MIT
.. _Python License 2.0: http://opensource.org/licenses/Python-2.0
.. _Apache License 2.0: http://www.apache.org/licenses/LICENSE-2.0
.. _wxWindows Library Licence: http://www.wxwidgets.org/about/licence/
.. _GPL 3.0: http://www.gnu.org/licenses/gpl-3.0
.. _reStructuredText: http://docutils.sourceforge.net/docs/user/rst/quickref.html
.. _reStructuredText online renderer: https://www.tele3.cz/jbar/rest/about.html
.. _GitHup Releases: https://github.com/lczub/PortablePythonWithRobot/releases
.. _SourceForge: http://sourceforge.net/projects/portablepythonwithrobot/
.. _PyScripter: http://sourceforge.net/p/pyscripter/wiki/PyScripter/