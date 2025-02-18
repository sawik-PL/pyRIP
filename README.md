# pyRIP
![Platform](https://img.shields.io/badge/Platform-Windows-lightgrey.svg) ![Python](https://img.shields.io/badge/Python-3.5.1-blue.svg) ![Status](https://img.shields.io/badge/Status-Under_Development-ff5533.svg)

[pyRIP](https://github.com/hankofficer/pyRIP) is a personal Routing Information Protocol Implementation on Python. In order to get familiar with implementing a routing protocol, I opened this project on GitHub for the practice.

Currently, pyRIP is capable of originating routes and redistribute them to neighbor RIP router. This could be an easy tool to test or debug a RIP router.

## Available functions
1. Regular update packets
2. Routing Information Base
3. JSON configuration file
4. Handling incoming packets

## GOAL
Implement RFC2453(RIPv2) and compatible with RFC1058(RIPv1)

## TODO
1. Split-Horizon and Poison Reverse
2. Trigger update
3. Compatible with v1
4. RIPv2 Authentication

## Reference
* **RIPv2** [RFC 2453](http://tools.ietf.org/html/rfc2453)
* **RIPv1** [RFC 1058](http://tools.ietf.org/html/rfc1058)
