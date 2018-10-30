# [DRAFT!] check_vxlan_mesh

1. copy to /etc/check_vxlan_mesh.ini on control and compute nodes
2. create suitable mysql- and rabbitmq-users in your env
3. set correct openstack release (tested with pike only) in .ini
4. run _deamon on your control nodes
5. run check-script on hv (f.e. via nrpe)

debug() function may help debugging issues.

