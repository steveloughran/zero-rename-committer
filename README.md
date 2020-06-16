# A Zero-Rename Committer: Object-storage as a destination for Apache Hadoop and Spark

This is a LaTeX formatted paper on the new S3A committers [shipped in Hadoop 3.1.](https://hadoop.apache.org/docs/r3.1.1/hadoop-aws/tools/hadoop-aws/committers.html)



## Building

`mvn package` should do all but the image rendering. For that, `plantuml` is
doing the rendering, set up to monitor the directory `tex/`. 
As usual, you need to run `bibtex` sporadically.
