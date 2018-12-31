# manufacturing_iot_demo
Manufacturing IoT Demo

Assumptions: 

HDP with HDF

You already have access to a Hortonworks Connected Data Platform environment (HDP and HDF). This can be accomplished in an automated fashion following this excellent article: https://community.hortonworks.com/articles/218863/automate-deployment-of-hdp30hdf32-or-hdf32-standal.html  If you want to deploy your cluster from scratch, goto https://docs.hortonworks.com/ and following the instructions to install first, Ambari, and then HDP with HDF.

KEPServerEX

You can download KEPServerEX v6 and run for free for two hours at https://www.kepware.com/en-us/kepserverex-6-6-release/ 


Whats in This Repository?  

It contains a pre-build Nifi Flow (fans_demo_v7.xml), a tar file containing a dump of individual fan events (fans.tar.gz), a Hive Create Table query (create_table_fans_demo7.sql), a Druid Kafka Indexer spec (supervisor-spec.json) and CURL start command (start_druid_kafka_indexer.sh).  In addition, other helpful sample commands and references are provided.  Follow the steps in this HCC article (xxxxxx) to build out the demo.  

Latest Versions Tested:   

KEPServerEX v6 (Demo License - Free)
Ambari 2.7.1.0
HDP-3.0.1.0 w HDF 3.2
