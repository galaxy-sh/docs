# Containers vs VMs

**Galaxy.sh** allows you to run your instances as either a *system container (LXC)* or a *virtual machine (VM)*. No matter which option you choose, your instances are isolated and restricted so that only you can access it.

## Comparison
A high-level comparison between the options of a container and a VM:

| System Containers (LXC) | Virtual Machines (VM) |
| :---: | :---: |
| Uses the kernel of the host | Uses a dedicated (virtualized) kernel |
| Can only host Linux | Can host different types of OS |
| Uses fewer resources per instance | Uses greater resources per instance |
| Software-only virtualization | Hardware-based virtualization |
| Can host multiple applications in an instance | Can host multiple applications in an instance |
| Available in all **Galaxy.sh** locations[^1] | Only available in *some* **Galaxy.sh** locations[^1] |

!!! quote
    *Virtual machines create a virtual version of a physical machine, using hardware features of the host system. The boundaries between the host system and virtual machines is enforced by those hardware features. System containers, on the other hand, use the already running OS kernel of the host system instead of launching their own kernel. If you run several system containers, they all share the same kernel, which makes them faster and more lightweight than virtual machines.*

    *With Incus, you can create both system containers and virtual machines. You should use a system container to leverage the smaller size and increased performance if all functionality you require is compatible with the kernel of your host operating system. If you need functionality that is not supported by the OS kernel of your host system or you want to run a completely different OS, use a virtual machine.*

    -- *[About containers and VMs - linuxcontainer.org](https://linuxcontainers.org/incus/docs/main/explanation/containers_and_vms/#virtual-machines-vs-system-containers)* *(**Galaxy.sh** uses Incus (previously LXD) to power its infrastructure.)*

## Location Availability
While we are always working to expand our capacity and capabilities, currently only some of our locations support running virtual machines. By comparison, **all** of our locations have full support for system containers.

Please see the [:material-arrow-right:location list](locations.md/#location-list) for a breakdown of which locations support VMs.

[^1]:
    At this time, not all locations support hosting virtual machines. Please see the [:material-arrow-right:location list](locations.md/#location-list) for a full breakdown.