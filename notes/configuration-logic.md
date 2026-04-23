# Configuration Logic

- VLANs were used to separate departments and reduce unnecessary broadcast scope.
- Access ports were assigned according to endpoint role and departmental structure.
- Trunk links were configured to transport multiple VLANs between switches.
- EtherChannel was used to create a more robust and structured backbone between switching devices.
- Port security was applied to access ports to reduce the risk of unauthorized device connections.
- Unused interfaces were administratively disabled to reduce exposure.
- IP addressing was configured on end devices for validation and simulation purposes, even though switching logic remains based on MAC addressing.
- Validation was based on expected communication success within the same VLAN and communication failure across distinct VLANs without inter-VLAN routing.
