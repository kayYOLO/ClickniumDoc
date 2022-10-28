Python API
=============================== 

:doc:`Clicknium Python package <https://pypi.org/project/clicknium/>` supports automating various types of applications, such as **Web** browser, **Windows** application, **Java** application and **SAP** Windows GUI App, etc.

**Install Clicknium Python pacakge**

System Requirements​:
- Python 3.7 or above
- Windows 7 SP1 or above

Install:

pip install clicknium


API reference : 


- :doc:`Global Functions <globalfunctions/globalfunctions>` : the root level APIs for UI element.  
- :doc:`UiElement <uielement/uielement>` : the UI element operations.  
- :doc:`WebDriver <webdriver/webdriver>` : the web automation related objects and APIs.  
- :doc:`Window <window/window>` : the window specific automation APIs.  
- :doc:`SAP <sap/sap>` : the SAP specific automation APIs.   
- :doc:`Java <java/java>` : the Java extension APIs.  
- :doc:`Configuration <config/config>` : the configuration setting APIs.
- :doc:`Exceptions <exceptions/exceptions>` : the errors defined in clicknium.  


Global Functions
------------------
.. toctree::
    :caption: Global Functions
    :hidden:
    :maxdepth: 1

    globalfunctions/globalfunctions
    globalfunctions/find_element
    globalfunctions/find_elements
    globalfunctions/get_screenshot
    globalfunctions/is_existing
    globalfunctions/send_hotkey
    globalfunctions/send_text
    globalfunctions/wait_appear
    globalfunctions/wait_disappear
    
UiElement
------------------
.. toctree::
    :caption: UiElement
    :hidden:
    :maxdepth: 1

    uielement/uielement
    uielement/child
    uielement/clear_text
    uielement/click
    uielement/double_click
    uielement/drag_drop
    uielement/get_position
    uielement/get_property
    uielement/get_size
    uielement/get_text
    uielement/highlight
    uielement/hover
    uielement/mouse_down
    uielement/mouse_up
    uielement/mouselocation
    uielement/save_to_image
    uielement/select_item
    uielement/select_items
    uielement/send_hotkey
    uielement/set_checkbox
    uielement/set_focus
    uielement/set_text
    uielement/wait_property
    

WebDriver
------------------
.. toctree::
    :caption: WebDriver
    :hidden:
    :maxdepth: 1

    webdriver/attach
    webdriver/attach_by_title_url
    webdriver/open
    webdriver/webdriver
    webdriver/browser/browser
    webdriver/browser/close
    webdriver/browser/get_active_tab
    webdriver/browser/get_tab
    webdriver/browser/maximize
    webdriver/browser/new_tab
    webdriver/browser/browsertab/browsertab
    webdriver/browser/browsertab/activate
    webdriver/browser/browsertab/close
    webdriver/browser/browsertab/find_element
    webdriver/browser/browsertab/find_element_by_css_selector
    webdriver/browser/browsertab/find_element_by_xpath
    webdriver/browser/browsertab/find_elements
    webdriver/browser/browsertab/find_elements_by_css_selector
    webdriver/browser/browsertab/find_elements_by_xpath
    webdriver/browser/browsertab/goto
    webdriver/browser/browsertab/is_existing
    webdriver/browser/browsertab/is_existing_by_css_selector
    webdriver/browser/browsertab/is_existing_by_xpath
    webdriver/browser/browsertab/refresh
    webdriver/browser/browsertab/scroll
    webdriver/browser/browsertab/wait_appear
    webdriver/browser/browsertab/wait_appear_by_css_selector
    webdriver/browser/browsertab/wait_appear_by_xpath
    webdriver/browser/browsertab/wait_disappear
    webdriver/browser/browsertab/wait_disappear_by_css_selector
    webdriver/browser/browsertab/wait_disappear_by_xpath
    webdriver/browser/browsertab/webelement/webelement
    webdriver/browser/browsertab/webelement/child
    webdriver/browser/browsertab/webelement/execute_js
    webdriver/browser/browsertab/webelement/execute_js_file
    webdriver/browser/browsertab/webelement/find_element
    webdriver/browser/browsertab/webelement/find_element_by_css_selector
    webdriver/browser/browsertab/webelement/find_element_by_xpath
    webdriver/browser/browsertab/webelement/find_elements
    webdriver/browser/browsertab/webelement/find_elements_by_css_selector
    webdriver/browser/browsertab/webelement/find_elements_by_xpath
    webdriver/browser/browsertab/webelement/scroll
    webdriver/browser/browsertab/webelement/set_property
    webdriver/webextension/webextension
    webdriver/webextension/detect
    webdriver/webextension/install
    webdriver/webextension/install_or_update
    webdriver/webextension/update


Window
------------------
.. toctree::
    :caption: Window
    :hidden:
    :maxdepth: 1

    window/window
    window/maximize
    window/minimize
    window/restore


Mouse
------------------
.. toctree::
    :caption: Mouse
    :hidden:
    :maxdepth: 1

    window/window
    window/maximize
    window/minimize
    window/restore


SAP
------------------
.. toctree::
    :caption: SAP
    :hidden:
    :maxdepth: 1

    sap/sap
    sap/login
    sap/find_element
    sap/sapelement/sapelement
    sap/sapelement/child
    sap/sapelement/get_statusbar
    sap/sapelement/select_item


Java
------------------
.. toctree::
    :caption: Java
    :hidden:
    :maxdepth: 1

    java/java
    java/install
    java/uninstall


Configuration
------------------
.. toctree::
    :caption: Configuration
    :hidden:
    :maxdepth: 1

    config/config
    config/disable_telemetry
    config/enable_telemetry


Exceptions
------------------
.. toctree::
    :caption: Exceptions
    :hidden:
    :maxdepth: 1

    exceptions/exceptions
    exceptions/argumenterror
    exceptions/argumentnullerror
    exceptions/argumentoutofrangeerror
    exceptions/baseerror
    exceptions/browsernotinstallerror
    exceptions/browsernotrunerror
    exceptions/elementcannotfounderror
    exceptions/extensionoperationerror
    exceptions/invalidoperationerror
    exceptions/invalidselecteditemerror
    exceptions/locatorrequesterror
    exceptions/locatorundefinederror
    exceptions/notsupportederror
    exceptions/notsupportedoperationerror
    exceptions/notsupportedoperationoptionerror
    exceptions/projectsettingnotfounderror
    exceptions/screenoperationerror
    exceptions/timeoutoperationerror
    exceptions/uiapatternnotfounderror
    exceptions/unauthoriederror
    exceptions/unreachablebrowserextensionerror
    exceptions/webelementnotrespondingerror
    exceptions/weberror
    exceptions/windowerror
    exceptions/windowsnativeerror


Change Log
------------------
.. toctree::
    :caption: Change Log
    :hidden:
    :maxdepth: 1

    changelog/changelog