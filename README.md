# Backup from Cisco HyperFlex (HX)

This vSphere Installation Bundle (VIB) is to be used for optimizing and load balacing the Cisco HyperFlex data network, when used in combination with Backup from Storage Snapshots in Veeam Backup and Replication.

For usage instructions, please see the following knowledge base article > [Usage of a predefined VMware ESXi extension for Veeams Backup from Storage Snapshot with Cisco HyperFlex IOvisor processing](https://www.veeam.com/kb2298)

## Versions

* For Cisco HyperFlex OS version < 2.5, please use: `VeeamCiscoHXFirewall_HX_2_0.vib`
  * This profile will open for all TCP ports in the range 0-65535 for associated Veeam backup proxy servers
* For Cisco HyperFlex OS version >= 2.5, please use: `VeeamCiscoHXFirewall_HX_2_5.vib`
  * This profile will open TCP ports 111, 2049 and 2449 for associated Veeam backup proxy servers

## Distributed under MIT license
Copyright (c) 2019 VeeamHub

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
