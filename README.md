# ansible-role-ood-client

This ansible role installs needed tools for Open On Demand (https://openondemand.org/) 
compute node. Originally this has been written for CentOS 7, but can be easily extended 
to other operating systems.

Key tasks for compute node is to
- install websockify and turbovnc
- place symlinks to default bin location for easy integration with OOD apps
- fix udev permission issues with DRI
- Install Xfce packages if requested
- install additional small tools to be used with minimal Xfce4 desktop env
