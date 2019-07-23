# Bluetooth-Low-Energy
This git contains analysis made with the software sodera on the operation of a Bluetooth mesh network.
Download the software at http://www.fte.com/products/sodera-CPAS.aspx
Make the modifications to the MeshOptions.ini file and add the device keys, network key and app key used by the network

-	Network key: nrfMeshLightProvisioning = c9d02f346cae37c02501d67ff0c482ee
-	App key: 4a0e176838a2c8361ca27953c98ac30f
-	Switch key: a3829b81148e75b7e7c32ad1a43e7e3c
-	Light key: 192cc5f1a284dbb2a5430be0c370944f

To help understand the works of the network, here are the Address ID of the nodes in this network.
The client node has the address: 0xFDF6F1D45795 
The server node has the address: 0xFEF797927C77

It can be observed the provisioning phase made with the App NrfMesh on android
And then the working phase by setting the state on or off on the server's led.
