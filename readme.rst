###################
What is CubiMobile
###################

CubiMobile is the mobile extension for Openbiz Cubi Application Platform. 
This mobile extension contains 2 parts:

-  Mobile-enabled modules

-  Mobile-enabled themes

This mobile extension mainly uses jquerymobile library for mobile UI display.

*******************
Release Information
*******************

This repository is to support mobile UI for Cubi platform. Please visit 
http://code.google.com/p/openbiz-cubi/ for more information about Cubi platform.

************
Installation
************

- Pull the latest source code from http://code.google.com/p/openbiz-cubi/source/checkout. Install Openbiz Cubi by following instruction at http://code.google.com/p/openbiz-cubi/wiki/CubiInstallation

- Install mobile modules. Copy user_mob and contact_mob under cubi/modules/ directory

- Install mobile theme. Copy touch under cubi/themes/ directory

- Load user_mob and contact_mob modules by using cubi/bin/tools/load_module.php::

    php load_module.php user_mob
    php load_module.php contact_mob

-  Hit your url from either iPhone or Android phone, or their native simulators. If you want to test it on your desktop browser, you can chang useragent to iphone or android with browser developer tool, such as Firefox Modify Header https://addons.mozilla.org/en-US/firefox/addon/modify-headers/

*******
License
*******

The Cubi mobile extension is released under BSD license.

*********
Resources
*********

-  `Openbiz Cubi project <http://code.google.com/p/openbiz-cubi/>`_
-  `Discussion Group <http://groups.google.com/group/openbiz-cubi>`_
-  `Community Wiki <http://code.google.com/p/openbiz-cubi/w/list>`_
-  `Facebook with screenshots <http://www.facebook.com/OpenbizSolution>`_

***************
Acknowledgement
***************

Great thanks for the work done by developers of excellent jquerymobile project.
http://jquerymobile.com/
