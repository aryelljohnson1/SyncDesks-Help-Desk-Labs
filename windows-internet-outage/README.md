# Windows Internet Outage — Simulated Help Desk Case

**Issue:** A user could not access the internet on a Windows workstation.

**Investigation:** I found that the workstation had a 169.254.x.x address, indicating it had not received an address from DHCP.

**Resolution:** I renewed the DHCP lease, then checked the assigned IP address, default gateway, and DNS settings.

**Verification:** I tested ping and browser access and confirmed with the user that the connection worked.

**Skills demonstrated:** Windows network troubleshooting, DHCP, DNS, connectivity testing, ticket documentation, and user confirmation.
