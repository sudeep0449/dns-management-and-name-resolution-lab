# DNS Management and Name Resolution Lab

## Lab Overview

A hands-on Windows Server 2022 lab focused on configuring and managing DNS services within an Active Directory environment (`sudeep.local`). The lab covered Host (A) record creation, Reverse Lookup Zone configuration, PTR record creation, and DNS name resolution testing using command-line tools.

## Environment

- **Platform:** Windows Server 2022 (`WINSERVER2022`), running in Oracle VirtualBox
- **Domain:** Active Directory-integrated (`sudeep.local`)
- **Forward Lookup Zone:** `sudeep.local`
- **Host (A) Record:** `fileserver.sudeep.local` → `192.168.1.10`
- **Reverse Lookup Zone:** configured with secure dynamic updates only (Active Directory-integrated)

## Topics Covered

- DNS Manager administration
- Forward Lookup Zone management
- DNS Host (A) record creation
- File server host record configuration
- DNS resolution testing with `nslookup` and `ping`
- Reverse Lookup Zone configuration
- PTR record creation
- Reverse DNS resolution
- Active Directory integrated DNS
- DNS troubleshooting and verification

## Conclusion

Successfully demonstrated DNS administration in a Windows Server 2022 environment. Practical experience was gained in managing DNS records, configuring forward and reverse lookup zones, implementing PTR records, and validating DNS functionality through testing and troubleshooting — resolving `fileserver.sudeep.local` to `192.168.1.10` and confirming reverse resolution back to the hostname.

## Repository Contents

- [`DNS Management and Name Resolution Configuration in ADDS.pdf`](<./DNS Management and Name Resolution Configuration in ADDS.pdf>) — full step-by-step write-up
- [`DNS screenshot/`](<./DNS screenshot>) — implementation evidence (DNS record creation, zone configuration, and resolution testing)

## Author

**Sudeep Kumar Chaurasiya**

Bachelor of Information Technology (Networking / Cyber Security)
Melbourne Institute of Technology, Sydney

GitHub: [github.com/sudeep0449](https://github.com/sudeep0449)
