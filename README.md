glusterfs-hadoop-examples
=========================

A set of mapreduce workloads that support advanced configurations such as multiple-namespaced filesystems. 

We have added in alot of hadoop exampels here, which we slightly customize for more advanced use cases and debugging.  One example is the MultiVolume mapreduce... For hadoop 2x, build off of master:

```
mvn clean package
And the jar is in target/ 
```

Note that we have different branches:  You can scan through them to pick the branch which is compatible with your distro.   
