# Task4--Windows-firewall
How to setup Firewall Rule
Open Windows Defender Firewall with advanced security and check the current inbound rules in Firewall
To block the telnet(port 23),click inbound rule and add new rule blocking telnet giving port no 23
Test the rule by checking from other system. 
To verify,In command box, run telnet <ip address> 23
Got the output couldnot open connection to host.Connection failed.
Revert back the block rule to original state
This is how firewall fileration works-
*Once the data packet enters or leaves a network,1st line of defence is firewall. After checking Source IP, destination IP, port number and protocol, it makes the decision based on predefined rules.If a packet matches allow rule, it will allow to pass through firewall. If it matches deny rule, it will block it. If it doesnt match any rule, default rule is deny all.
