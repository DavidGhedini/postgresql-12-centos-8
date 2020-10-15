# PostgreSQL 13 on CentOS 8

This script will install PostgreSQL 13 on CentOS 8.

We’ll be using a bash script below, which is commented so you can see the steps.

We’ll install PostgreSQL using the PostgreSQL repository, configure the pg_hba.conf file to secure the instance, and update the postgresql.conf file to allow remote connections and enable SSL.

We will also create a self-signed SSL certificate for the cluster.

For post information, see:  

https://davidghedini.com/pg/entry/install-postgresql-13-on-centos-8/
