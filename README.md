# PgBDRMSresourceAgent
A postgres with BDR replication Master/Slave resource agent for pacemaker

This is modified from pgsql that from pacemaker ocf resource agent.
bdrpgsql is use for postgres BDR replication.Because the pgsql is for master/slave replication, but BDR is multimaster replication, so the bdrpgsql is used to simulate the master/slave for multi nodes in master state.that make is easy to use a vip to access the BDR cluster.
