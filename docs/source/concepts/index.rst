Automation Concepts
======================================


In this section, we will illustrate the technology information about Clicknium automation, including how to leverage Clicknium automation technology to make RPA/automation project robust and easily edited, writed and maintained. 

Clicknium automation integrate mulitple automation technologies in backgroup, Clicknium Recorder default use `Auto Detect` mode, it means Clicknium will automatically detect the application type, and choose appropriate background technology.  

Clicknium defined unified :doc:`locator <locator>` schema to identify UI element, a locator stores the attributes of a UI element and its parents, for example, button on Windows application, input on web page or combobox on Java application can be stored as one locator.  

The following technologies are freqeuntly used:   

- :doc:`Clicknium Chrome/Edge/IE/Firefox <web>`: automation on many popular web browsers.  
- :doc:`Clicknium UIA <uia>`: automation on most Windows/desktop application, based on Microsoft UI Automation.  
- :doc:`Clicknium IA <ia>`: automation on Windows/desktop application, it can be supplement for UIA, on some electron&CEF applications or some legacy application, IA can be better.  
- :doc:`Clicknium Image Automation <image>`: image automation can be used combied with above technologies.  
- :doc:`Clicknium Java <java>`: automation on Java application, support Java 1.6 or above.  
- :doc:`Clicknium SAP <sap>`: automation on SAP WinGUI, it requires the SAP WinGUI API scripting enabled.  

Articles:

- :doc:`Locator <locator>`
- :doc:`UIA automation <uia>`
- :doc:`Web automation <web>`
- :doc:`Java automation <java>`
- :doc:`SAP Automation <sap>`
- :doc:`IA Automation <ia>`
- :doc:`Image Automation <image>`

.. toctree::
   :hidden:

   locator
   uia
   web
   java
   sap
   ia
   image