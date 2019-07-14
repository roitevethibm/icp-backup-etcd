# ICP ETCD Backup Helm Chart

The ETCD backup helm chart deploys  etcd backup cronJob to an ICP cluster.


# ETCD Backup cronJob

The ETCD backup cronjob, takes a backup of the ICP ETCD object store.  
The backup schedule is set using `.Values.backupParameters.backupSchedule` value. 
The backup retention is set using `.Values.backupParameters.backupRetention` value. 
