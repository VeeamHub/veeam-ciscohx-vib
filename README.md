# Backup from Cisco HyperFlex (HX)

This vSphere Installation Bundle (VIB) is to be used for optimizing and load balacing the Cisco HyperFlex data network, when used in combination with Backup from Storage Snapshots in Veeam Backup and Replication.

## 📗 Documentation

For usage instructions, please see the following knowledge base article > [Usage of a predefined VMware ESXi extension for Veeams Backup from Storage Snapshot with Cisco HyperFlex IOvisor processing](https://www.veeam.com/kb2298)

### Versions

* For Cisco HyperFlex OS version < 2.5, please use: `VeeamCiscoHXFirewall_HX_2_0.vib`
  * This profile will open for all TCP ports in the range 0-65535 for associated Veeam backup proxy servers
* For Cisco HyperFlex OS version >= 2.5, please use: `VeeamCiscoHXFirewall_HX_2_5.vib`
  * This profile will open TCP ports 111, 2049 and 2449 for associated Veeam backup proxy servers

## ✍ Contributions

We welcome contributions from the community! We encourage you to create [issues](https://github.com/VeeamHub/veeam-ciscohx-vib/issues/new/choose) for Bugs & Feature Requests and submit Pull Requests. For more detailed information, refer to our [Contributing Guide](CONTRIBUTING.md).

## 🤝🏾 License

* [MIT License](LICENSE)

## 🤔 Questions

If you have any questions or something is unclear, please don't hesitate to [create an issue](https://github.com/VeeamHub/veeam-ciscohx-vib/issues/new/choose) and let us know!
