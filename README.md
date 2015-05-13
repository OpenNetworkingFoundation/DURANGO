# DURANGO
Support files for OVS support of OF Config

Log-in as root, no password is set.

Virtual machine contains installed OF-CONFIG server with Open vSwitch.
All dependencies are installed.
To be able to connect to OF-CONFIG server, ofc-server must be executed,
it will run as daemon. ofc-server listens on TCP port 830.

To connect to the OF-CONFIG server, netopeer-cli or Netopeer-GUI can
be used. netopeer-cli is a console application, Netopeer-GUI is a graphical
web application that listens on TCP port 80
(and 8080 for notifications).

There is sshd enabled and listening on TCP port 22.
