## Elasticsearch Service for Ambari

The Elasticsearch Service for Ambariis a custom service for Ambari that allows you to install and manage Elasticsearch via Ambari.  This service is not supported by Hortonworks.  Futhermore, this service is intended for testing and development and should not be used in a production environment.

## Compatibility

This service has been tested with the following:

- CentOS 7.x
- Ambari 2.4.1.0
- HDP 2.5.0.0-1245
- At least 3 data nodes are required*

## Required property
``` zen_discovery_ping_unicast_hosts - FQDN of master and data nodes. seperated by comma eg. master.internal,data1.internal,data2.internal
```

## Contributors
More than welcome!

## License
This project is based on Elasticsearch Ambari Service of <https://github.com/apache/incubator-metron/tree/master/metron-deployment/packaging/ambari/metron-mpack/src/main/resources/common-services/ELASTICSEARCH>
