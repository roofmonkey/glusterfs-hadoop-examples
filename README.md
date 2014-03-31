glusterfs-hadoop-examples
=========================

A set of mapreduce workfloads that support advanced configurations such as multiple-namespaced filesystems. 

2x
===

We have added in alot of hadoop 2x exampels here, which we slightly customize for more advanced use cases and debugging.  One example is the MultiVolume mapreduce... For hadoop 2x, build off of master:

```
mvn clean package
And the jar is in target/ 
```


1x
===

Hadoop examples for 1x actually built with ant, so to make it easy for folks wanting to customize 1x hadoop examples and still build the jar using maven, we have made them available in this examples jar in a branch.

We also have a branch called "1x" .  Over time we will put hadoop examples into this branch.  Ideally we'd use a mvn classifier to distinguish 1x vs 2x.  But for now we just have a branch.  

Thus, to build a 1x compatible hadoop-exampels jar, just do :

```

git branch 1x
mvn clean package

```

Note that right now this branch really only does WordCount and TeraGen.  We can add more of the 1x features into it over time, its just a matter of copying code from 1x hadoop-examples into this package.  
