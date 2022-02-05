# sscan
Stealth Port Scan

The script performs a ping sweep and then port scans the active IPs. It is designed to be slow to make it more stealthy. You can adjustthe wait time between pings and port connections with the -s <secconds> command. Default is 30 seconds. The script will randomize the ports on each run so that it avoids the detection of sequential ports.

It can take a single IP with -t <IP>, a subnet in CIDR notation with -c <CIDR notation>, or a file containing a list of IPs or a list of CIDR blocks with -f <file< or  -cf <cidr file>.
  
Ports are passed as a single port with -p <port>, -t 10 for namp top 10 ports, -t 100 for nmap top 100 ports, -t 1000 for nmap top 1000 ports, or -a for all TCP ports.   Default is a list of 6 TCP ports [80, 21, 22, 20, 443, 8080].
  
This script is intentionally slow.

![image](https://user-images.githubusercontent.com/84335647/152654915-046d3fa0-3569-4b11-96d6-e69bf5e4daf4.png)

![image](https://user-images.githubusercontent.com/84335647/152654934-56d889f8-9771-4d3a-ad40-1425b3364e90.png)
 
