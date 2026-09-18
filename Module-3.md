# WEEK 2 | NETWORK SCANNING WITH ZENMAP

# NETWORK DISCOVERY AND TOPOLOGY MAPPING USING ZENMAP

## Description

Zenmap is the graphical user interface (GUI) for Nmap and is used for network discovery, host identification, port scanning, and network topology visualization.

In this practical, Zenmap was used to perform network discovery on a local network. The practical involved identifying the local IP address and subnet, discovering live hosts, identifying their IP and MAC addresses, and generating a network topology.

---

## Objective

The objective of this practical is to understand how Zenmap can be used to:

- Identify the local IP address and subnet.
- Discover active hosts on a local network.
- Identify the IP addresses of live hosts.
- Identify MAC addresses of discovered hosts.
- Generate and visualize a network topology.
- Save the network topology in PDF format.

---

# Task 1 | Identify Local IP Address and Subnet

### Objective

To identify the local IP address and LAN subnet using the Windows `ipconfig` command.

### Tool Used

**Windows Command Prompt**

### Command

    ipconfig

### Procedure

1. Open Windows Command Prompt.
2. Run the `ipconfig` command.
3. Identify the active network adapter.
4. Note the IPv4 address.
5. Identify the subnet information from the network configuration.
6. Use the identified subnet as the target network for the Zenmap scan.

### Result

The local IPv4 address and LAN subnet were identified using the `ipconfig` command.

The identified subnet was then used as the target network in Zenmap for host discovery.

---

# Task 2 | Discover Live Hosts Using Zenmap

### Objective

To discover active hosts on the local network using Zenmap.

### Tool Used

**Zenmap**

### Scan Type

**Ping Scan**

### Procedure

1. Open Zenmap.
2. Enter the identified local network subnet in the **Target** field.
3. Select **Ping Scan (or any suitable scan)** from the **Profile** option.
4. Start the scan.
5. Wait for Zenmap to complete the network discovery process.
6. Observe the hosts that respond to the scan.
7. Record the IP addresses of the live hosts.

### Result

The Zenmap scan was used to identify active hosts on the local network.

The practical example identified the following live hosts:

- `10.0.0.1`
- `10.0.0.4`
- `10.0.0.19`
- `10.0.0.5`

The actual IP addresses and number of live hosts should be replaced with the results obtained from the local network during the practical.

---

# Task 3 | Identify IP and MAC Addresses

### Objective

To identify the IP addresses and corresponding MAC addresses of the discovered live hosts.

### Tool Used

**Zenmap**

### Procedure

1. Review the hosts discovered during the scan.
2. Select the required host in Zenmap.
3. Examine the host information displayed by Zenmap.
4. Identify the IP address and MAC address of each discovered host.
5. Record the information for the report.

### Result

Zenmap displayed information about the discovered hosts, including their IP addresses and MAC addresses where available.

The practical example contained four live hosts and their corresponding MAC address information.

The actual IP and MAC addresses should be replaced with the results obtained from the user's own local network.

---

# Task 4 | Generate Network Topology

### Objective

To generate a visual network topology showing the relationship between the discovered hosts.

### Tool Used

**Zenmap**

### Procedure

1. Complete the network discovery scan in Zenmap.
2. Open the **Topology** section.
3. View the discovered network devices and their relationships.
4. Enable the **Legend** option to display the topology information clearly.
5. Arrange or view the topology as required.
6. Save the generated network topology in PDF format as required by the practical task.

### Result

The Zenmap Topology section was used to visualize the discovered network.

The network topology displayed the discovered hosts and their relationship within the scanned network. The topology was saved in PDF format as required.

---

# Conclusion

This practical demonstrated the use of Zenmap for network discovery and topology mapping on a local network.

The local IP address and subnet were first identified using the Windows `ipconfig` command. The subnet was then entered into Zenmap and a suitable scan was performed to identify active hosts.

The discovered hosts were examined to identify their IP and MAC addresses. Finally, the **Topology** section in Zenmap was used to generate a visual representation of the network, with the legend enabled, and the topology was saved in PDF format.

This practical provided hands-on experience with basic network discovery, host identification, and network topology visualization.

---
#Screenshots

<img width="1162" height="552" alt="Screenshot 2026-09-18 170352" src="https://github.com/user-attachments/assets/11cb8e4d-fca5-49ff-a89e-ca9f6149ef50" />

<img width="1347" height="790" alt="Screenshot 2026-09-18 170503" src="https://github.com/user-attachments/assets/447ed7b7-a7d0-43db-82e1-64f183a60431" />
