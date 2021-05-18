# ITI_Final_Project

Deploy two applications based on LAMP and LEMP stacks on two
identical servers and load balance the traffic between the servers

Tools used:
- Docker to deploy Wordpress container and connect it to MySQL
container, Drupal container and connect it to MariaDB container on
each server.
- Ansible to install Docker on the servers, copy Docker Files from the
local machine to the servers, build the Docker Images and deploy the
needed containers
- HA-Proxy and Keepalived to perform load balancing and failover
between the load balancers
- Rsync to synchronize files and directories between servers.
- Master – Master MySQL Replication.
