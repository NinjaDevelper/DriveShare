DriveShare
==========

Farming software for the Storj network, which allows users to earn money by sharing their extra hard drive space. 

#### Scope
- [heartbeat](https://github.com/storj/heartbeat) is a Python library for verifying existence of a file on a remote computer.
- [randomio](https://github.com/storj/randomio) generates random bytes and files from a seed. Allows us to quickly create test files without having to transfer data over a network.
- [downstream-node](https://github.com/Storj/downstream-node) is a verification node for the files. Typically runs on a [MetaDisk](https://github.com/Storj/MetaDisk/) server. 
- [downstream-farmer](https://github.com/Storj/downstream-farmer) is a library and command line for utility for framers to complete challenges from the verifications nodes.
- [driveshare-gui](https://github.com/Storj/driveshare-gui) is the GUI of the DriveShare application, written with [Kivy](http://kivy.org/).

#### Installation
DriveShare is currently under active development, and consists of many component parts. You can currently run a verfication node and farmer client software(no payments yet). Installation instructions are in the READMEs for [downstream-node](https://github.com/Storj/downstream-node) and [downstream-farmer](https://github.com/Storj/downstream-farmer).
