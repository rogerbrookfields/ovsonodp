# ovsonodp
Open VSwitch (OVS) on Open Data Plane (ODP) with uio acceleration.

For SDN platform base, numbers of chip vendors provide DPDK or ODP as their uio interface.
Although, SDN application developers tend to write their code using OpenFlow API.
There seemed to exists a gap of requirements and it is now a barrier of SDN system delivery.

There slightly exist ODP support in git repository of OVS, though, it's a bit hard to build
and configure correctly odp-ovs on target, especially for non-Intel platform.

This project aims to provide a light layer to cover this gap: providingg some portable, stable
and instant patches are our goal of development.

Nov. 29, 2017
Roger Brookfields
