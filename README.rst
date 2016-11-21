# raspberrypi

Raspberry pi projects and notes
===============================

.. contents:: Table of Contents
   :depth: 3


Complete guide to set up headless raspberry pi
----------------------------------------------

Prepare raspbian OS on SD card using instructions at raspberrypi.org_.

.. raspberrypi.org_: https://www.raspberrypi.org/documentation/installation/installing-images/


None: on Mac, for example, if ``BSD Name:	disk2s5`` in diskutil, then  ``of=/dev/rdisk2``, where rdisk``<n>`` corresponds to disk``2``s5

.. code :: sh
    
    $sudo dd bs=1m if=/path/to/raspbian.img of=/dev/rdisk<n>
