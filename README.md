# ambari-grafana

Install Grafana
---------------

You can install Grafana on any host.  It does not need to be co-located with Ambari Server.

Run the following command for CentOS/Red Hat:

```
$ sudo yum install https://grafanarel.s3.amazonaws.com/builds/grafana-2.5.0-1.x86_64.rpm
```

For other OS's, please follow the instructions at: http://docs.grafana.org/installation/

Deploy ambari-grafana
```
wget ...
```

Start Grafana
```
service grafana-server start
```

Access Grafana Web UI at http://grafana-host:3000 and log in as admin / admin.

Create an Ambari datasource


