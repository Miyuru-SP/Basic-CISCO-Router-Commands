# Cisco Router Basic Commands

This guide provides a summary of essential commands for configuring and managing Cisco routers. These commands are commonly used by network administrators and engineers.

---

## 1. Basic Configuration Commands

- `enable`: Enters privileged EXEC mode (enables admin privileges).
- `configure terminal`: Enters global configuration mode.
- `hostname <name>`: Sets the hostname of the router.
- `banner motd <message>`: Configures a message-of-the-day (MOTD) banner.
- `enable secret <password>`: Sets an encrypted password for privileged EXEC mode.

---

## 2. Interface Configuration Commands

- `interface <interface_type> <interface_number>`: Enters interface configuration mode (e.g., `interface GigabitEthernet0/0`).
- `ip address <ip_address> <subnet_mask>`: Assigns an IP address to the interface.
- `no shutdown`: Activates the interface.

---

## 3. Show Commands (Troubleshooting and Monitoring)

- `show running-config`: Displays the current configuration.
- `show interfaces`: Shows detailed information about all interfaces.
- `show ip route`: Displays the routing table.

---

# 4. Saving and Resetting Configuration

- `copy running-config startup-config`: Saves the current configuration to NVRAM.
- `erase startup-config`: Deletes the saved configuration.
- `reload`: Reboots the router.

---

## 5. Why This Guide is Useful

This guide is a handy reference for anyone working with Cisco routers, whether for setting up a new network, troubleshooting, or preparing for Cisco certifications like CCNA.

---

> Source: [GeeksforGeeks - Cisco Router Basic Commands](https://www.geeksforgeeks.org/cisco-router-basic-commands/)
