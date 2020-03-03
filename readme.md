# MySQL Cluster setup example with Docker-Compose

Sets up a MySQL cluster with two datanodes, an application node and a management node.

## Notes

The order of creation is important; the management node must be created last.

The setup in the very basic `mysql-cluster.cnf` shows the minimum info the cluster needs.
