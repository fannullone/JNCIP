# ISIS
*RemainingLiftime* is the field of LSP PDU that holds the aging mechanism in IS-IS. Initially this is set to 1200 seconds.  
Junos by default does not leak external IP reachability information from L1 to L2

# MSDP
rfc3618
MSDP peer with highest IP address listen on TCP port 639

# L3vpn
rfc4364: BGP/MPLS IP Virtual Private Networks (VPNs)  
rfc2858: Multiprotocol Extensions for BGP-4  
rfc4577: OSPF as the Provider/Customer Edge Protocol for BGP/MPLS IP Virtual Private Networks (VPNs)  
rfc2918; Route Refresh Capability for BGP-4  
rfc3107: Carrying Label Information in BGP-4  
rfc6514: BGP Encodings and Procedures for Multicast in MPLS/BGP IP VPNs  

# L2vpn
rfc4447: Pseudowire Setup and Maintenance Using the Label Distribution Protocol (LDP)  
rfc4761: Virtual Private LAN Service (VPLS) Using BGP for Auto-Discovery and Signaling  
rfc4762: Virtual Private LAN Service (VPLS) Using Label Distribution Protocol (LDP) Signaling  
rfc6074: Provisioning, Auto-Discovery, and Signaling in Layer 2 Virtual Private Networks (L2VPNs)  


inet-vpn: AFI=1 SAFI=128  
route-target: AFI=1 SAFI=132  
inet-label-unicast: AFI=1 SAFI=4  
inet-mvpn: AFI=1 SAFI=5  

l2vpn: AFI=25 SAFI=65

