IST (also known as Internet Servicing Tool) is a free and open-source batch script designed to do network based tasks. Like "ist -check-network" for checking download and upload speed. or "ist -ip" to show the ip address and many more.

here are all commands:
   ist -check-network                  - Runs the speedtest script
   ist -ip                             - Shows your IP addresses
   ist -dns [user input]               - Shows the DNS of a URL
   ist -ping                           - Pings the server chosen (if no server is chosen, google.com is set by default)
   ist -flushdns                       - Evicts DNS Cache, may also help with internet issues
   ist -info                           - Shows information about internet in general on your device
   ist -mac                            - Shows MAC address
   ist -hostname                       - Shows the device's name, the name that the router will recognize as the name of the device
   ist -listend-ports                  - Shows the ports currently getting listend by programs
   ist -apps                           - Lists all programs currently using the internet
   ist -monitor                        - Shows you a refreshing view, of how much data is being sent and received every 5 seconds
   ist -max-speed                      - Shows the maximum speed your network card can output
   ist -list-connected-nets            - Shows every network ever connected to the windows device
   ist -list-pass [user input]         - Shows WiFi Password
   ist -list-wifi-info [user input]    - Shows WiFi Info of a specified WiFi network
   ist -trace [user input]             - Shows what other IPs/URLs a website needs before you can use it
   ist -active-ips                     - Shows Currently active IPs
   ist -dns-cache-history              - Shows DNS cache that built up by the internet
   ist -install-drivers [user input]   - Installs the selected IST drivers
   ist -usage                          - Lists how many bytes were Recieved and Sent
   ist -adapter-status                 - Lists the status of every network adapter
   ist -gateway                        - Shows The Windows Device's Gateway
   ist --install                       - Installs IST as a Local Program instead of a portable one
   ist -set-dns [user input]           - Sets a custom DNS
   ist -show-log                       - Shows all log files
   ist --update                        - Shows if IST has updates available
   ist -optimize                       - Optiizes The Computer (in terms of Networking)
   ist -type                           - Shows what type of program IST iis (portable or installed)
   ist -export-log                     - Exports every Log to the desktop
   ist -restart                        - Restarts the Terminal
   ist  --reinstall                    - Reinstalls IST into ProgramFiles
   ist -installed-time                 - See The time, when IST was installed as local program
   ist -check-use                      - Is the Internet even Working?
   ist -connection                     - The Type of the current Internet connection IST can detect

                                                   
                                       DEAD ZONE
The following commands are dangerous to the windows device. May harm your device.
proceed with caution.
   ist --deadzone-renew                - Makes a new IP address for your windows device
   ist --deadzone-remove-driver        - Removes the Network Configuration drivers
   ist --deadzone-rmwinsock            - Resets WinSock, may fix "connected, but no internet" issues
   ist --deadzone-reset-firewall       - Resets the rules of the firewall (good if you made mistakes in it)
   ist --deadzone-ipv6-off             - Turns off IPv6 IPs (recommended for older routers, that hate IPv6)
   ist --deadzone-set-dns              - Sets the dns to googles DNS (good, if you mistakenly set a non-working DNS)
   ist --deadzone-uninstall            - Uninstalls IST but downloads the Portable one back

New in v1.6:
   ist -show-log-amount                 - Shows All Logs in IST
   ist --whats-new                      - Shows Everything New to IST (like now Commands and more)
   ist --error-codes                    - Shows Info about a given Error Code
   ist --tui                            - Opens Up IST TUI mode (experiental)
   ist -check-proxy                     - Checks The Proxy
   ist -convert-bits                    - Converts Bits to bytes
   ist -export-configs                  - Exports the Configs for the Network Tools in Windows

DEAD ZONE:
   ist --deadzone-reset-arp             - Resets ARP
   ist --deadzone-tui                   - Launches the DeadZone TUI
   ist --deadzone-[command] --yolo      - If you have --yolo, the DeadZone will be executed without a conformation scree
