<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>


<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

- Create and Configure NSGs
-  Define Security Rules
- Analyze and Act on Traffic Insights

<h2>Actions and Observations</h2>

<p>

  ![image](https://github.com/AEY982312/azure-network-protocols/assets/116044851/ff7961e6-fcff-4a25-961a-fcbe31bfc03e)

</p>
<p>
Begin by creating NSGs and associating them with the appropriate subnets or individual VMs. NSGs act as virtual firewalls that control inbound and outbound traffic based on defined rules. Configure the NSG rules to allow necessary traffic and deny any unauthorized or unnecessary traffic. Specify the source and destination IP addresses, ports, protocols, and action (allow or deny) for each rule
</p>
<br />

<p>

![image](https://github.com/AEY982312/azure-network-protocols/assets/116044851/b1b43ee6-9b79-4c7b-9470-dfe432067cc5)


 ![image](https://github.com/AEY982312/azure-network-protocols/assets/116044851/dbd3d197-f403-4c10-b534-2f6d765830f7)

</p>
<p>
 Define inbound and outbound security rules within the NSGs to control traffic flow between the VMs. For example, you can create rules to allow incoming traffic on specific ports for applications or services hosted on the VMs, or restrict outbound traffic to specific IP addresses or ranges. In addition, you can use NSGs to enable or disable specific protocols or applications. Review and analyze the traffic data captured by Network Watcher to gain insights into the communication patterns and potential security risks. Identify any abnormal or unauthorized traffic flows, and take appropriate actions to mitigate potential threats. This may involve updating NSG rules, implementing additional security measures, or investigating any suspicious activities through Azure Security Center or other security monitoring tools.
</p>
<br />

<p>

</p>
<p>

</p>
<br />
