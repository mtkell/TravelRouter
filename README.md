# [TravelRouter] (https://github.com/mtkell/TravelRouter/)

Travel Router using Raspberry Pi, ZeroTier, and Flask-Bulma website for configuration.  
The design allows connection into any wireless LAN to include hotels, coffee shops and private wireless LANs.
The configuration scans for available WLANs and displays them as part of the configuration.  The web page shows
the existing configured WLANS and for the additional WLANS the ablity to log in and add to the WLAN configurations.
The program utilizes seperate configuration files within the wpa_authorization folder.  Priority is used to
rotate through the WLANs for connectivity.  WLAN 0 the on-board WLAN is used for external connectivity. 
A second WLAN dongle is required for the protected WLAN.  The Travel Router networks is added to the client
devices.  This allows multiple devices to share a single WLAN connection.  
