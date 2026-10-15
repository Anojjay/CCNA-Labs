# Static NAT Lab

Configured static NAT on R1 to translate the private IP addresses of PC1, PC2, and PC3 from the 172.16.0.0/24 network into public addresses in the 100.0.0.0/24 range. Configured the inside and outside interfaces and verified NAT translations using `show ip nat translations` and `show ip nat statistics`.

Tested connectivity to 8.8.8.8 and google.com before and after configuring NAT.

**Key Concepts:** Static NAT, inside local and inside global addresses, NAT translations, inside/outside interfaces.

**Tools:** Cisco Packet Tracer, Cisco IOS CLI
