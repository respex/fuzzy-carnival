# OCI 

prereq
ansible-galaxy collection install oracle.oci

And that your ansible.cfg includes:

[inventory]
enable_plugins = oci


Usage: 
ansible-playbook launch_cluster.yml

Inventory
ansible-inventory -i inventory/oci/oci_inventory.yaml --list
To get a JSON output of all instances in the specified compartment and region, grouped by OCID or tags.

