Support
=======

NOTE: ***This cookbook is not currently working***


Issues have been disabled for this repository.  
Any issues with this cookbook should be raised here:

[https://github.com/rcbops/chef-cookbooks/issues](https://github.com/rcbops/chef-cookbooks/issues)

Please title the issue as follows:

[corosync]: \<short description of problem\>

In the issue description, please include a longer description of the issue, along with any relevant log/command/error output.  
If logfiles are extremely long, please place the relevant portion into the issue description, and link to a gist containing the entire logfile


Description
===========

This recipe provides a bare bones framework for corosync.  To use assign the corosync::master recipe to a single server and the corosync::client recipe to the cluster members.

The master node will generate the authkey for the cluster and store it as a node attribute.  Clients will search for this attribute and use it for cluster communication.
