# IST - Internet Servicing Tool
IST (also known as Internet Servicing Tool) is a free and open-source batch script designed to do network based tasks. Like "ist -check-network" for checking download and upload speed. or "ist -ip" to show the ip address and many more.
For most of these commands, you need to install the drivers, also in the zip file called "IST-network-configuration-drivers.zip" which adds support for "ist -check-network" and many more. Otherwise, most functions would not work.

here are all commands:
   "ist -check-network"       - Runs the speedtest script
   "ist -ip"                  - Shows your IP addresses
   "ist -dns [user input]"    - Shows the DNS of a URL
   "ist -ping [user input]"   - Pings the server chosen (if no server is chosen, google.com is set by default)
   "ist -flushdns"            - Evicts DNS Cache, may also help with internet issues
   "ist -info"                - Shows information about internet in general on your device
   "ist -mac"                 - Shows MAC address
   "ist -hostname"            - Shows the device's name, the name that the router will recognize as the name of the device
   "ist -listend-ports"       - Shows the ports currently getting listend by programs
   "ist -apps"                - Lists all programs currently using the internet
   "ist -monitor"             - Shows you a refreshing view, of how much data is being sent and received every 5 seconds
   "ist -max-speed"           - Shows the maximum speed your network card can output
   "ist -list-connected-nets" - Shows every network ever connected to the windows device
   "ist --help"               - Shows the Help Centre
   "ist --version"            - Shows the IST version and the IST-network-configuration-driver version

                                                   
                                                   DEAD ZONE
The following commands are dangerous to the windows device. May harm your device.
proceed with caution.
   "ist --deadzone-renew"     - Makes a new IP address for your windows device
