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

inet-vpn: AFI=1 SAFI=128  
route-target: AFI=1 SAFI=132
inet-label-unicast: AFI=1 SAFI=4
