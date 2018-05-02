

Scala Sbt Environment setup
------------------------------
- Scala / Sbt Setup Steps
	- **topics**
		- check your java version
			- the version of sbt and scala should be compatible with your java version
		- download scala
			- <http://www.scala-lang.org/download/>
				- at the very bottom there's a link labeled "Download the Scala binaries for osx "
					- below that there's a link labeled "previous releases"
						- use this if you need an older version of scala to match your java version
		- download sbt
			- I use the link in <http://www.scala-lang.org/download/> or the page for the previous release for the version of scala you want to use
		- unpack the binary packages for both and add the bin paths to your PATH env variable
			- I typically just keep them in the path where they are and manually call them.. i think it makes system setup easier, especially if you need to work on multiple projects.
				- scala:  ./scala-2.10.1/bin/scala
				- sbt: ./sbt/bin/sbt
	- **links**
		- [Getting Started in Scala (dev blog)](http://blog.mikiobraun.de/2011/04/getting-started-in-scala.html)
		- [Scala - Environment Setup (tutorials point)](http://www.tutorialspoint.com/scala/scala_environment_setup.htm)
		- [Download, Install Scala on Linux, Unix, Windows (journal dev)](https://www.journaldev.com/7456/download-install-scala-linux-unix-windows)

		- [How to compile, run, and package a Scala project with SBT (alvin alexander)](https://alvinalexander.com/scala/sbt-how-to-compile-run-package-scala-project)
		- [GETTING STARTED WITH SCALA AND SBT ON THE COMMAND LINE (scala docs)](https://www.scala-lang.org/documentation/getting-started-sbt-track/getting-started-with-scala-and-sbt-on-the-command-line.html)
		- [SBT 0.13 Docs](http://www.scala-sbt.org/0.13/docs/index.html)
		- [How to create an SBT project directory structure (alvin alexander)](https://alvinalexander.com/scala/how-to-create-sbt-project-directory-structure-scala)
	- **code**



Sbt stuff
---------------
- "No sbt.version set in project/build.properties" issue
	- **topics**
		- create a build.properties in the project dir
		- add sbt.version=0.13.16 in build.properties file
	- **links**
		- ["No sbt.version set in project/build.properties" issue](https://stackoverflow.com/questions/28429030/is-there-a-way-to-define-the-required-sbt-version-in-build-sbt)
	- **code**


- Specifying particular class to run with sbt
	- **topics**
		- use ../sbt/bin/sbt "runMain package.path.to.main.class param1 param2"
	- **links**
		- [How to Run a Specific Main Class with Parameters through SBT](http://blog.ssanj.net/posts/2016-03-02-how-to-run-a-specific-main-class-with-parameters-through-sbt.html)
		- [Scala/SBT: How to specify a main method/class to run (alvinalexander.com)](https://alvinalexander.com/scala/sbt-how-specify-main-method-class-to-run-in-project)
	- **code**

- "object runtime is not a member of package reflect" issue
	- **topics**
	- **links**
		- [Unable to add scala-reflect as a dependency (stack overflow)](https://stackoverflow.com/questions/22226874/unable-to-add-scala-reflect-as-a-dependency)
	- **code**



Scala language stuff
------------------------------
- [TOUR OF SCALA (scala docs)](http://docs.scala-lang.org/tour/tour-of-scala.html)
- [Scala types (scala docs)](http://docs.scala-lang.org/tour/unified-types.html)
- [GUIDES AND OVERVIEWS (scala docs)](http://docs.scala-lang.org/overviews/?_ga=2.226055646.55390166.1510870573-400468962.1510784243)
- [scala-exercises.org](https://www.scala-exercises.org/)
- [Scala School! (twitter)](https://twitter.github.io/scala_school/)
- [10 Scala One Liners to Impress Your Friends](https://gist.github.com/mkaz/d11f8f08719d6d27bab5)
- [Scala Cheat Sheet (scala-lang)](http://docs.scala-lang.org/cheatsheets/)
- [Scala Cheat Sheet (alvin alexander)](https://alvinalexander.com/downloads/scala/Scala-Cheat-Sheet-devdaily.pdf)
- [Scala Cheat Sheet (tutorials point)](http://www.tutorialspoint.com/scala/scala_quick_guide.htm)
- [Scala Cheat Sheet (dzone)](https://dzone.com/refcardz/scala)
- [Java developer's Scala cheatsheet](http://mbonaci.github.io/scala/)
- [The Neophyte’s Guide to Scala (Daniel Westheide)](http://danielwestheide.com/scala/neophytes.html)
- [Learning Scala Series (joel abrahamsson)](http://joelabrahamsson.com/learning-scala/)
- [Programming in Scala Book – Code Samples (book)](http://booksites.artima.com/programming_in_scala_2ed/examples/)
- [Scala-lang.org Examples and Code Samples (Scala-lang.org)](http://www.scala-lang.org/old/node/219)



Spark general stuff
----------------------------
- [UC Berkeley AMPLab](http://ampcamp.berkeley.edu/)
- [Mastering Apache Spark by Jacek Laskowski (GitBook)](https://www.gitbook.com/book/jaceklaskowski/mastering-apache-spark/details)
- [Spark Tutorials and Examples (back to bazics)](http://backtobazics.com/category/big-data/spark/)
- [Spark Components](http://apachesparkbook.blogspot.com/search/label/a12%7C%20Driver%20Program)
- [Scala Unified Types Diagram](http://docs.scala-lang.org/tutorials/tour/unified-types)
- [Scala Api](http://www.scala-lang.org/api/2.10.3/)
- [Java Api](https://docs.oracle.com/javase/7/docs/api/)
- [Spark Api](https://spark.apache.org/docs/1.1.1/api/)
- [Scala Operator Cheat Sheet](http://jim-mcbeath.blogspot.com/2008/12/scala-operator-cheat-sheet.html)
- [datastax/spark-cassandra-connector](https://github.com/datastax/spark-cassandra-connector/tree/master/doc)
- [mysql/mysql-connector-j](https://github.com/mysql/mysql-connector-j/tree/5.1.38/src/testsuite)
- [WHAT IS APACHE SPARK? DECONSTRUCTING THE BUILDING BLOCKS PART 1](https://www.supergloo.com/fieldnotes/what-is-apache-spark-deconstructing-the-building-blocks-part-1/)
- [Spark SQL with JSON from SUPERGLOO](http://www.supergloo.com/fieldnotes/spark-sql-json-examples/)
- [Quick Tips & Tricks I Learned Working With Spark](http://arjon.es/2014/09/04/quick-tips-tricks-i-learned-working-with-spark/)




Spark RDDs stuff
----------------------------
- [Resilient Distributed Datasets (RDDs) (Spark Docs)](https://spark.apache.org/docs/latest/rdd-programming-guide.html#resilient-distributed-datasets-rdds)
- [The RDD API By Example (Zhen He)](http://homepage.cs.latrobe.edu.au/zhe/ZhenHeSparkRDDAPIExamples.html)
- [Spark Programming Guide v1.1.0 - RDD's (spark docs)](https://spark.apache.org/docs/1.1.0/programming-guide.html)
- Back to Bazics tutorials
	- [Spark Tutorials and Examples (back to bazics)](http://backtobazics.com/category/big-data/spark/)
- [Spark RDD Operations in Scala (acad guild)](https://acadgild.com/blog/spark-rdds-scala/)
- SUPERGLOO Tutorials
	- [Spark RDD Transformations Examples (SUPERGLOO)](https://www.supergloo.com/fieldnotes/apache-spark-examples-of-transformations/)
	- [Spark RDD Actions (SUPERGLOO)](https://www.supergloo.com/fieldnotes/apache-spark-examples-of-actions/)
- Time Pass Techies Tutorials
	- [Spark rdd api transformations and actions tutorial with examples – tutorial 1 (time pass techies)](http://timepasstechies.com/spark-rdd-api-transformations-actions-tutorial-examples-part-1/)
	- [Spark pair rdd and transformations in scala and java – tutorial 2 (time pass techies)](http://timepasstechies.com/spark-pair-rdd-transformations-scala-java/)
	- [Spark pair rdd reduceByKey, foldByKey and flatMap aggregation function example in scala and java – tutorial 3 (time pass techies)](http://timepasstechies.com/spark-pair-rdd-reducebykey-foldbykey-flatmap-aggregation-function-example-scala-java/)
	- [spark combinebykey example in scala and java – tutorial 4 (time pass techies)](http://timepasstechies.com/spark-combinebykey-example-scala-java/)
	- [spark group by,groupbykey,cogroup and groupwith example in java and scala – tutorial 5 (time pass techies)](http://timepasstechies.com/spark-group-bygroupbykeycogroup-groupwith-example-java-scala/)
	- [spark inner join and outer joins example in java and scala – tutorial 6 (time pass techies)](http://timepasstechies.com/spark-inner-join-outer-joins-example-java-scala/)
	- [spark sortby and sortbykey example in java and scala – tutorial 7 (time pass techies)](http://timepasstechies.com/spark-sortby-sortbykey-example-java-scala/)
	- [spark custom comparator example for sortbykey in java and scala – tutorial 8 (time pass techies)](http://timepasstechies.com/spark-custom-comparator-example-sortbykey-java-scala-tutorial-8/)




