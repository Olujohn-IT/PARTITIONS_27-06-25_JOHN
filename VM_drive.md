# Steps to adding additional drive to a virtual machine on Hyper-V


## Prerequisites
Before starting this task, ensure that the virtual machine is switched off especially if it's a generation 1 virtual machine.

## Steps
1. Open the Hyper-V Manager.
2. In the middle pane, right-click on the virtual machine you need to edit and select Settings. The Settings dialog box for the virtual machine opens.
3. In the left pane, under Hardware, select any IDE Controller item. The Hard Drive settings open in the right pane.
4. Select the Hard Drive option in the right panel and click Add.
5. In the Hard Drive section, select “IDE Controller 1” as the Controller and “1 (in use)” as the location.
6. Click New. The New Virtual Hard Disk wizard opens.
7. Select VHDX as the Disk Format type and click Next.
8. In the Choose Disk Type section, select one of Fixed Size/dynamically expanding/differencing option and click Next.
9. Specify a Name and Location for the virtual hard drive, and click Next.
10. Set the Disk Size based on the license you have acquired and then click Next.
11. Click Finish to create the hard drive. This can take a few minutes.
12. When the Hard Drive settings page for the newly created drive opens, click OK.
13. Start the virtual machine. When the VM starts, it will automatically recognize the new drive, but the new storage must be manually added the virtual appliance.

[Exinda Network Orchestrator](https://manuals.gfi.com/en/exinda/help/content/exos/virtual-appliances/hyper-v/hyperv-locate-vhd.htm)

![VHD](https://github.com/user-attachments/assets/4824c334-c1b7-4945-b2df-f67d17a25c9c)
`20Gb additional drive added to Module4 virtual machine`
