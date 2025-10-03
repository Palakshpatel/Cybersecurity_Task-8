# Cyber Security Internship - Task 8: Working with VPNs

Objective:Understand the role of Virtual Private Networks (VPNs) in protecting privacy and securing communication.

Tool Used: ProtonVPN Free Tier (or specify the VPN client you used) 

## 1. VPN Setup and Verification Steps

This section details the hands-on process of setting up and verifying the VPN connection:

1.  Selection and Account Creation: Chose a reputable free VPN service, ProtonVPN (or your chosen service), and completed the sign-up process.
2.  Client Installation: Downloaded and installed the official ProtonVPN client application.
3.  Connection: Launched the application, logged in, and connected to a free VPN server (e.g., Netherlands).
4.  IP Verification:
    * *Prior to connection*, the public IP address was noted.
    * *After connection*, visited `whatismyipaddress.com` to verify the IP change. The IP address successfully changed from the original ISP-assigned address to the VPN server's IP address, confirming the secure tunnel (See `vpn_connection_status.png`).
5.  Traffic Confirmation:Browsed several websites to confirm that traffic was routed through the VPN and encrypted.
6.  Disconnection and Comparison: Disconnected the VPN.Verified that the IP address reverted to the original one and compared browsing speed, noting a slight decrease while the VPN was active.

## 2. Evidence of Successful Connection

A screenshot of the successful VPN connection showing the new, masked IP address and the protocol used is attached as `vpn_connection_status.png`.

* **VPN IP:** 185.107.80.87
* **Protocol Used:** WireGuard (UDP)

## 3. Research Summary: VPN Benefits and Limitations

Based on research on VPN encryption and privacy features, here is a summary of the benefits and limitations :

### Benefits of a VPN
* Data Encryption: A VPN encrypts all internet traffic between the user's device and the VPN server, protecting data from eavesdropping, especially on public Wi-Fi networks].
* Privacy Protection: It masks the user's original IP address with the server's IP, making it harder to track online activities and protecting personal location/identity from websites and third parties.
* Bypassing Geo-restrictions: By connecting to a server in a different country, a user can access region-locked content.
* Secure Tunneling: VPNs create a secure tunnel using protocols like WireGuard, OpenVPN, or IKEv2/IPsec to ensure data integrity and confidentiality.

### Limitations of a VPN 
* Speed Reduction: Encrypting and routing data through an intermediary server can often decrease network speed and increase latency.
* Not Complete Anonymity: A VPN does not guarantee *complete* anonymity. A user's activities can still be logged by the VPN provider itself (if they have a poor logging policy), or be compromised by browser fingerprinting or malware.
* Cost and Trust: Quality, reliable VPN services often require a paid subscription. Users must also place a high degree of trust in the VPN provider's commitment to their privacy (e.g., their no-logging policy).
* Blocking: Some services and websites actively detect and block traffic originating from known VPN IP ranges.---
