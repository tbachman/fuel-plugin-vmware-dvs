fuel-plugin-vmware-dvs
============

There is the Fuel plugin which provides Neutron for networking on
VMware-related MOS 8.0 environments.

Installation
============

There is only one difference from normal plugin installation way. Before
building the plugin you have to patch plugin_rpm.spec.mako file which is a part
of the fuel plugin builder.

Just do
$ cd /path/to/fuel-plugin-vmware-dvs; sudo patch /path/to/plugin_rpm.spec.mako hack.diff