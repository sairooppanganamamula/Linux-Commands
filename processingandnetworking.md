## Process Management Commands 
If we want to get a snapshot of what is currently running in the system we use the following command
*top*
Another program to look for processes is 
*ps*
ps gives list of processes running in our terminal. If we add an argument aux it will show a complete system view.
*ps[aux]*
## Killing a process 
*kill <Pid>*
If this does not work, we can use force kill.
*kill -9 <Pid>*
## Foreground and Background jobs
We can get a list of jobs running by typing jobs
*jobs*
If we want to shift our process to background, we can use CTRL + Z.
Background jobs can be brought to foreground using the command
*fg <jobnum>*
To show all running processes and full listing we use
*ps -ef*
*htop* - Similar to top with an easier to understand layout.
*pstree* - Displays processes in tree format.
*pgrep* - Returns the process id that matches it.
*pkill and killall* - Used to kill a process.
*renice* - Changes the nice value of the process which determines the priority of the process. A value of -19 is high priority, 19 is low priority and 0 is the default.
*xkill* - kill graphical programs


# Networking Commands
*ifconfig -a* - Used to configure network interface parameters.
*traceroute geekflare.com* - Prints the route packets take to network host.
*dig* - Domain Information Groper is a tool for interrogating DNS name servers. Performs DNS lookups.
*telnet* - Connects to a destination host.
*nslookup* - Program to query Internet domain name servers.
*netstat* - Allows a simple way to review each of network connections and open sockets. To display routing table information use -r.
*scp* - Allows us to securely copy files to and from another host in the network.
*w* - Prints a summary of current activity on the system including what each user is doing and their processes.
*nmap* - Checks the opened port of the server.
*ifup* - To enable network interface.
*ifdown* - To disable network interface.
*ping* - To test connectivity between two nodes.
*ping c -5 www.test.com* - Ping with c exits after N number of requests.
*route* - Shows and manipulates ip routing table.
*route add -net 0.0.0.0 192.168.10.2* - To add a default route.
*route flush* - To remove all routes.
*host* - To find name to IP and IP to name and query DNS records.
*arp* - Used to view/add contents of the Kernel�s ARP tables. Used to translate IP addresses to Ethernet addresses. 
*iwconfig* - Used to configure a wireless network interface.
*system-config-network* - Used to configure IP address, DNS..etc.
*ftp <host>water* - Transfers files to host.
*rlogin -l* - Logs into host with a virtual terminal.
*/etc/hosts* - Names to ip addresses.
*/etc/networks* - Network names to ip addresses.
*/etc/protocols* - Protocol names to ip addresses.
*/etc/services* - TCP/UDP service names to port numbers.
*udpmt -p [port] -s [bytes] target_host* - Creates UDP traffic.
*udptarget -p [port]* � Able to receive UDP traffic.
*tcpmt -p [port] -s [bytes] target_host* - Creates TCP traffic.
*tcptarget -p [port]* - Able to receive TCP traffic.
