# raspberrypi

Raspberry pi projects and notes
===============================

.. contents:: Table of Contents
   :depth: 3


Complete guide to set up headless raspberry pi
----------------------------------------------

Prepare raspbian OS on SD card using instructions at raspberrypi_.

.. raspberrypi_: https://www.raspberrypi.org/documentation/installation/installing-images/


None: on Mac, for example, if ``BSD Name:	disk2s5`` in diskutil, then  ``of=/dev/rdisk2``, where rdisk<n> corresponds to disk<2>s5

.. code :: sh
    
    $sudo dd bs=1m if=/path/to/raspbian.img of=/dev/rdisk<n>
    
    
DO NOT DO THIS : here is how to set up static-IP-address_.

..  static-IP-address_: http://raspberrypi.stackexchange.com/questions/37920/how-do-i-set-up-networking-wifi-static-ip


set 

     http://www.techjawab.com/2013/06/setup-dynamic-dns-dyndns-for-free-on.html
