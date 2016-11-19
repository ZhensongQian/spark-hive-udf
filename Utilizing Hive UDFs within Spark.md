# Utilizing Hive User Defined Functions (UDFs) within Spark
## Built-in UDFs
You can call built-in Hive UDFs, UDAFs, and UDTFs from Spark SQL applications, as long as the functions are available in the standard Hive .jar file. 

When using Hive UDFs, use **HiveContext** (not SQLContext).

## Custom UDF
You can **register** custom functions in Python, Java, or Scala, and use them within SQL statements.

When using a custom UDF, make sure that the jar file for your UDF is included with your application, 
or use the --jars command-line option to specify the file.

## Examples 
[define our own UDFs](https://www.linkedin.com/pulse/hive-functions-udfudaf-udtf-examples-gaurav-singh)

## Reference

[Calling Hive User-Defined Functions](http://docs.hortonworks.com/HDPDocuments/HDP2/HDP-2.4.2/bk_spark-guide/content/calling-udfs.html)

