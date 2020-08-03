# Table of Contents

1. [Introduction](#intro)



# Introduction<a name="intro"></a>

* allows traffic to be directed to specific network *applications*

- Multiplexing - nodes direct traffic to multiple services
- De-multiplexing - traffic meant for a node delivery at proper receiving service
- handled through ports = 16 bit , used to direct traffic to specific services running on a networked computer
- service = program running on a node, that awaits data request.
- different services run while listening on specific ports for incoming requests
  - traditional port for HTTP(un-encrypted) = 80
  - if a service requested, such that an instance of it runs on a computer with ip = 10.1.0.0, then this service is listening at the port 80, and the traffic for such requests is directed to this port.
- ip:port, hence 10.1.0.0:80 = socket-address/socket-number
- if the same device is running an FTP service
  - traditionally listens on port 21
  - hence traffic redirected to 10.1.0.0:80









