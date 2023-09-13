<h1>Hi, I'm Logan! 

<h2>👨‍💻 Cybersecurity and AD projects:</h2>

- <b>Active Directory Home Lab </b> https://www.dropbox.com/scl/fi/ktsqehwwytvs56vilmsdt/Active-directory-homelab-Made-with-Clipchamp_1694539276733.mp4?rlkey=4qi180g7bfroykvf1ed3p80pk&dl=0 
This is a simple video depicting an Active Directory home lab with two instances set up. The left panel is running a Windows Server 2019 which is called DC for domain controller and the right panel is a client running Windows 10. The domain controller is set up to create new users through a PowerShell script and act as a DHCP server for assign IP addresses to clients. The client is connected to the internet through the Active Directory Domain server. This video is just showing some key points of the lab working instead of the actual set up. It shows the client being able to browse the internet and its IP address through the command line function ipconfig/all. I also display the DHCP tool through the sever manager application and show the scope of the DHCP server with associated ranges. The script associated with creating and adding users is displayed as well.
- <b> SIEM Monitoring </b> https://www.dropbox.com/scl/fi/62p4oyg2egdxa8vggqk97/Honeypot-VM-with-SIEM-Made-with-Clipchamp_1694566465407.mp4?rlkey=yvovdlhbr0p39yl976ep21m76&dl=0 The lab shown here is set up through Microsoft’s Azure with several instances created. An Azure workbook was created (Microsoft Sentinel), a VM was created (honeypot-vm) and a Log Analytics workspace was created (law-honeypot). The VM was created with no firewall protection and RDP access which was to entice users to attempt to log on. Failed log on attempts were then captured through a PowerShell script to export to a .txt document which was then created as a query in the Log Analytics workspace. This query was then run through Microsoft Sentinel to output a map containing the longitude and latitude on a map with different colored dots depicting where each failed login attempt came from. The script was not written by me and was a sample script provided by Josh Madakor (https://www.linkedin.com/in/joshmadakor/). I have included several screenshots indicating the increase number of log in attempts as the script kept running.

<h2> 🤳 Connect with me:</h2> 


[<img align="left" alt="LoganZerbato | LinkedIn" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/linkedin.svg" />][linkedin]



[linkedin]: https://www.linkedin.com/in/logan-zerbato-9187a5218/

