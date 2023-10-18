#### Dynamic VMMQ
- increases performance
- does not require any setup
- uses queue packing
- manages processing of VM network traffic
#### RDMA for virtual switches
- provides high throughput
- low latency
- minimizes CPU usage
#### SET
- integrates NIC teaming functionality into hyper v virtual switch
- doesn't expose individual team interfaces
- requires all NICs to have the same vendor
#### Smart Paging
- helps when there is not enough physical memory when booting a VM
- supplies memory for the VM via local disk of the host
- kind of like swap on linux
#### Discrete Device Assignment
- provides VMs with direct access to PCIe devices
#### Hot add
- memory and NIC
- allows you to change the memory and NIC while the VM is running