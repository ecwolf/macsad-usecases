# Description

This folder contains P4 programs using version 16. In this folder we solve the following use cases:

- l2_fwd: One of the most simple tests in P4, it considers a simple switch connected to hosts. The objective of this test is to test a simple layer two connection.

<p align="center">
  <img src="../images/macsad_l2.png">
</p>


- l3_fwd_ipv4: Considering a layer higher than the usecase described before, this program simulates a layer three connection, using lpm implementation. Furthermore, it should be highlighted that this  was specifically made for IPv4 implementation.

<p align="center">
  <img src="../images/macsad_ipv4.png">
</p>


- BNG: The Broadband Network Gateway (BNG) is the access point for subscribers. It is capable of establish user sessions, managing all traffic of them and routes it to public network.

<p align="center">
  <img src="../images/macsad_bng.png">
</p>

- vEPG: virtual Evolved Packet Gateway (vEPG) is the user-plane node of LTE core network which merges the function of serving gateway (SGW) and packet gateway (PGW). The current supported functions are VxLAN (de)encapsulation of GTP flows, IP routing towards the Internet and eNodeB nodes, Management of Tunnel Endpoint Identifier (TEID) for flow multiplexing in GTP sessions, stateless firewall and Eth/IP forwarding to/from datacenter gateways. 

<p align="center">
  <img src="../images/macsad_vepg.png">
</p>
