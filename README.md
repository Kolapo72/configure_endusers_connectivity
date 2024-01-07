# configure_endusers_connectivity

<p>Connect a PC and a laptop to the Wireless router. The PC will be connected to the network using an Ethernet cable. For the Laptop, you will replace the wired Ethernet network interface card (NIC) with a wireless NIC and connect the Laptop to the router wirelessly.</p>
<p>After both end devices are connected to the network, you will verify connectivity to cisco.srv. The PC and the Laptop will each be assigned an IP (Internet Protocol) address. Internet Protocol is a set of rules for routing and addressing data on the internet. The IP addresses are used to identify the devices on a network and allow the devices to connect and transfer data on a network.</p>

<h4>Step 1: Configure the PC.</h4>
<p>Configure the PC for the wired network in this step.</p>
<ul>a. Click the PC. In the Desktop tab, navigate to IP Configuration to verify that DHCP is enabled and the PC has received an IP address.</ul>
<h6>Select DHCP for the IP Configuration heading if you do not see an IP address for the IPv4 Address field. Observe the process as the PC is receiving an IP address from the DHCP server.</h6>
<p>DHCP stands for dynamic host configuration protocol. This protocol assigns IP addresses to devices dynamically. In this simple network, the Wireless Router is configured to assign IP addresses to devices that request IP addresses. If DHCP is disabled, you will need to assign an IP address and configure all the necessary information to communicate with other devices on the network and the internet.</p>
<ul>b. Close IP Configuration. In the Desktop tab, click Command Prompt.</ul>
<ul>c. At the prompt, enter ipconfig /all to review the IPv4 addressing information from the DHCP server. The PC should have received an IPv4 address in the 192.168.0.x range.</ul>
<h6>Note: There are two types of IP addresses: IPv4 and IPv6. An IPv4 (internet protocol version 4) address is a string of numbers in the form of x.x.x.x as you have been using in this lab. As the internet grew, the need for more IP addresses became necessary. So IPv6 (internet protocol version 6) was introduced in the late 1990s to address the limitations of IPv4. The details of IPv6 addressing are beyond the scope of this activity.</h6>
<ul>d. Test connectivity to the cisco.srv from the PC. From the command prompt, issue the command ping cisco.srv. It may take a few seconds for the ping to return. Four replies should be received.</ul>

![PC Configure](https://github.com/Kolapo72/configure_endusers_connectivity/assets/147263584/a951b934-7192-4873-9aa0-aecffdd509d5)


<h4>Step 2: Configure the Laptop.</h4>
<p>Configure the Laptop to access the wireless network.</p>
<ul>a. Click Laptop, and select the Physical tab.</ul>
<ul>b. In the Physical tab, you will need to remove the Ethernet copper module and replace it with the Wireless WPC300N module.</ul>
      <li>Power off Laptop by clicking the power button on the side of the laptop.</li>
      <li>Remove the currently installed Ethernet copper module by clicking on the module on the side of the laptop and dragging it to the MODULES pane on the left of the laptop window.</li>
      <li>Install the wireless WPC300N module by clicking it in the MODULES pane and dragging it to the empty module port on the side of the Laptop.</li>
      <li>Power on the Laptop by clicking the Laptop power button again.</li>
<ul>c. With the wireless module installed, connect the Laptop to the wireless network. Click the Desktop tab and select the PC Wireless.</ul>
<ul>d. Select the Connect tab. After a slight delay, the wireless network HomeNetwork will be visible in the list of wireless networks. Click Refresh if necessary to see the list of available networks. Select the HomeNetwork. Click Connect.</ul>



<ul>e. Close PC Wireless. Select Web Browser in the Desktop tab.</ul>

![COnnectivity real](https://github.com/Kolapo72/configure_endusers_connectivity/assets/147263584/3adc8112-9e80-4c02-977a-727ac33077e9)

<ul>f. In the Web Browser, navigate to cisco.srv.</ul>

![Verify Connectivity](https://github.com/Kolapo72/configure_endusers_connectivity/assets/147263584/d3ca355f-9feb-46aa-9a01-c06b539a9645)
