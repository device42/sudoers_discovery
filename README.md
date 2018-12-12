# sudoers_discovery
sudoers file for auto-discovery using Device42


This file has been tested with Ubuntu 16.04 only. Your mileage may vary for different OS flavors and versions. Please adjust accordingly.

File has 2 parts:

1. Defining command aliases for various commands that need sudo

2. Adding permissions for the comamnd aliases.

Not all the defined command aliases have been added to the 2nd part. For example, DEVICE42_CONTAINERS is not added. If you need to run containers discovery, you need to add that alias to the permissions list as well.

Add the options that are relevent in sudoers file to your /etc/sudoers or to a file under /etc/sudoers.d/ directory.

Replace device42 with the group that the user running the discovery belongs to.
