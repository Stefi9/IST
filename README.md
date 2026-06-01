# IST (also known as Internet Servicing Tool) is a free and open-source batch script designed to do network based tasks. Like "ist -check-network" for checking download and upload speed. or "ist -ip" to show the ip address and many more.

Q&A:
Q: How do I download IST?
A: Open the terminal and type the following.
```cmd
curl -L github.com/stefi9/ist/releases/latest/download/ist.zip -o ist.zip
tar -xf .\ist.zip
```

Q: What does IST do?
A: IST is not just a little program anymore, it's an entire Ecosystem of it. You can do the basics, a quick and dirty speedtest, a view of the hosts fie or a view of your IP address (with a prompt) to DeadZone commands like --deadzone-renew, which makes a new IP address or --deadzone-reset-arp, which reset's ARP (also known as Address Resolution Protocol) and more.

Q: How do I update IST?
A: There are 2 Ways:
Method 1:
You go to github and download the latest version of IST
Method 2:
If your IST version is over v1.6, just do ist --update in the terminal.

Q: Can you edit IST's source code?
A: Absolutely! Just download the version of IST you want to change the source code, right click the bat file and click "Edit in Notepad" and there you can edit the source code. Since IST is Open Source, anyone has access to its source code.
