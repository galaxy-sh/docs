# Locations
**Galaxy.sh** runs your instances on servers around the world. Here, you can find a current list of data centers and locations that we use, along with their capabilities and direct URLs.

## Location List
| ID    | Location           | LXC Capable[^1]  | VM Capable[^2]   | Notes |
| :---- | :----------------- | :--------------- | :--------------- | :---- |
| `ASH` | :us: Ashburn, VA   | :material-check: | :octicons-x-16:  |       |
| `HIL` | :us: Hillsboro, OR | :material-check: | :octicons-x-16:  |       |
| `LAS` | :us: Las Vegas, NV | :material-check: | :material-check: | :octicons-clock-24: Delayed deployment[^3] |
| `MIA` | :us: Miami, FL     | :material-check: | :material-check: | :octicons-clock-24: Delayed deployment[^3] |
| `FSN` | :de: Falkenstein   | :material-check: | :octicons-x-16:  |       |
| `NBG` | :de: Nuremberg     | :material-check: | :octicons-x-16:  |       |
| `HEL` | :fi: Helsinki      | :material-check: | :octicons-x-16:  |       |
| `LUX` | :lu: Luxembourg    | :material-check: | :material-check: | :octicons-clock-24: Delayed deployment[^3] |

## Direct URLs List
Instances can be referenced by direct URLs, which are based on the instance name and location. They can be referenced as follows:

| ID    | Direct URL        |
| :---- | :---------------- |
| `ASH` | `*.ash.galaxy.sh` |
| `HIL` | `*.hil.galaxy.sh` |
| `LAS` | `*.las.galaxy.sh` |
| `MIA` | `*.mia.galaxy.sh` |
| `FSN` | `*.fsn.galaxy.sh` |
| `NBG` | `*.nbg.galaxy.sh` |
| `HEL` | `*.hel.galaxy.sh` |
| `LUX` | `*.lux.galaxy.sh` |

!!! example "Coming soon"
    Direct URL to your instance is (at this time) not automatically set up. A guide to set up direct URL access to your instance is **coming soon**.

[^1]: 
    LXC: A system container, which uses the kernel of the underlying server. More efficient than a VM.  
    ([:material-arrow-right:See comparison](containers-vs-vms.md))
[^2]:
    VM: A virtual machine, which is fully virtualized hardware. Less efficient than a container, but more flexible.  
    ([:material-arrow-right:See comparison](containers-vs-vms.md))
[^3]:
    Some locations are not yet setup for immediate deployment and require human intervention. Once you have at least one project/instance set up in this location, you will be able to immediately deploy additional projects and instances.