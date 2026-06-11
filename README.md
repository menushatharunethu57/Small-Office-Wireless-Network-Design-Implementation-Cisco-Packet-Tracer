**Small Office Wireless Network Design Implementation Cisco Packet Tracer**

Designed and deployed a fully functional small office wireless network simulation using Cisco Packet Tracer, covering end-to-end network infrastructure from ISP connectivity to end-user wireless access.

What I Built:
🖧 Multi-department network with VLAN segmentation (Management, Sales, IT) using a Cisco 3560 Multilayer Switch
📡 Wireless infrastructure with 3 WRT300N Access Points, each with dedicated SSIDs and WPA2-PSK security per department
🔁 Inter-VLAN routing using Switch Virtual Interfaces (SVIs)
🌍 NAT (PAT) configuration for internet access through a fiber WAN link
⚙️ DHCP server providing automatic IP assignment across all VLANs
🔒 Access Control Lists (ACLs) to restrict inter-department traffic
🖥️ DNS & HTTP server hosting an internal company website (www.newtec.com)
🔐 SSH configured on all network devices for secure remote management
🛡️ Port Security — Per-port MAC address limits enforced on all access ports:
        * Sales → max 10 devices
        * Management → max 10 devices
        * IT → max 20 devices (extra lab equipment)
🔌 Fiber optic WAN link (GLC-LH-SMD) replacing legacy serial connections

📊 Technologies Used:
Cisco IOS VLANs Inter-VLAN Routing NAT/PAT DHCP WPA2-PSK ACLs SSH DNS STP Fiber WAN Cisco Packet Tracer
