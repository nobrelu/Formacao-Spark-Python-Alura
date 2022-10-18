# Formacao-Spark-Python-Alura
Alura: Formação Apache Spark com Python


O curso é realizado no Google Colab, porém optei por utilizar minha máquina local com SO Windows.


1. SPARK SQL - Fundamentos
2. SPARK STREAMING


Versão do Python instalada: Python 3.10.8

## Configuração do ambiente virtual 

### Em Windows:

https://towardsdatascience.com/installing-apache-pyspark-on-windows-10-f5f0c506bea1


pip install virtualenv 


**Criação**


$ python -m venv .venv

ou (?)
virtualenv venv
source venv/bin/activate


**Ativação**

$ .\.venv\Scripts\Activate.ps1


**Saída** 

 $ deactivate


 ## Pacotes instalados: 

 $ pip list 

 $ pip install findspark 
 $ pip install wheel
 $ pip install pandas 




## Links Uteis

Apache Spark:  https://spark.apache.org 
Quem está usando Spark: https://spark.apache.org/powered-by.html
Documentação PySpark: https://spark.apache.org/powered-by.html

#PySpark SQL: pyspark.sql.SparkSession  https://spark.apache.org/docs/latest/api/python/reference/pyspark.sql/api/pyspark.sql.SparkSession.html

Data Types: https://spark.apache.org/docs/latest/api/python/reference/pyspark.sql/data_types.html

Functions: https://spark.apache.org/docs/3.1.2/api/python/reference/pyspark.sql.html#functions
withColumn: https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.DataFrame.withColumn.html

Datetime Patterns: https://spark.apache.org/docs/3.1.2/sql-ref-datetime-pattern.html

DataFrame.select(*cols): https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.DataFrame.select.html
DataFrame.orderBy(*cols, **kwargs): https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.DataFrame.orderBy.html 
DataFrame.where(condition): https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.DataFrame.where.html
DataFrame.filter(condition): https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.DataFrame.filter.html
Contains: https://sparkbyexamples.com/spark/spark-filter-contains-like-rlike-examples/ 
Column.like: https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.Column.like.html 

DataFrame.groupBy: https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.DataFrame.groupBy.html
DataFrame.agg: https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.DataFrame.agg.html
DataFrame.summary: https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.DataFrame.summary.html

> Funções:
[approx_count_distinct](https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.functions.approx_count_distinct.html) | 
[avg](https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.functions.avg.html) | 
[collect_list](https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.functions.collect_list.html) | 
[collect_set](https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.functions.collect_set.html) | 
[countDistinct](https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.functions.countDistinct.html) | 
[count](https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.functions.count.html) | 
[grouping](https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.functions.grouping.html) | 
[first](https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.functions.first.html) | 
[last](https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.functions.last.html) | 
[kurtosis](https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.functions.kurtosis.html) | 
[max](https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.functions.max.html) | 
[min](https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.functions.min.html) | 
[mean](https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.functions.mean.html) | 
[skewness](https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.functions.skewness.html) | 
[stddev ou stddev_samp](https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.functions.stddev.html) | 
[stddev_pop](https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.functions.stddev_pop.html) | 
[sum](https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.functions.sum.html) | 
[sumDistinct](https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.functions.sumDistinct.html) | 
[variance ou var_samp](https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.functions.variance.html) | 
[var_pop](https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.functions.var_pop.html)

pyspark.sql.functions.when: https://spark.apache.org/docs/latest/api/python/reference/pyspark.sql/api/pyspark.sql.functions.when.html
Column.otherwise: https://spark.apache.org/docs/latest/api/python/reference/pyspark.sql/api/pyspark.sql.Column.otherwise.html


DataFrame.join: https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.DataFrame.join.html

SparkSession.sql: https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.SparkSession.sql.html

Para saber mais sobre performance: [Artigo - Spark RDDs vs DataFrames vs SparkSQL](https://community.cloudera.com/t5/Community-Articles/Spark-RDDs-vs-DataFrames-vs-SparkSQL/ta-p/246547)

DataFrame.write: https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.DataFrame.write.html

DataFrameWriter.csv: https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.DataFrameWriter.csv.html


Apache Parquet: https://parquet.apache.org
https://www.alura.com.br/artigos/arquivos-parquet

DataFrameWriter.parquet: https://spark.apache.org/docs/latest/api/python/reference/pyspark.sql/api/pyspark.sql.DataFrameWriter.parquet.html

DataFrameWriter.partitionBy: https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.DataFrameWriter.partitionBy.html


ORC: https://orc.apache.org/specification/ e https://orc.apache.org
DataFrameWriter.orc: https://spark.apache.org/docs/latest/api/python/reference/pyspark.sql/api/pyspark.sql.DataFrameWriter.orc.html

RDD: https://spark.apache.org/docs/latest/rdd-programming-guide.html 



https://www.alura.com.br/artigos/spark-streaming
https://www.alura.com.br/artigos/machine-learning-com-apache-spark


https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.SparkSession.read.html
https://spark.apache.org/docs/3.1.2/api/python/reference/api/pyspark.sql.DataFrameReader.csv.html

Livros: 
https://www.oreilly.com/library/view/pyspark-cookbook/9781788835367/
https://www.oreilly.com/library/view/learning-pyspark/9781786463708/
https://www.oreilly.com/library/view/applied-data-science/9781484265000/

baixar
https://pt.b-ok.lat/book/3642064/66a58a?dsource=recommend


spark = SparkSession.builder \
    .master('local[*]') \
    .appName("Iniciando com Spark") \
    .config('spark.ui.port','4050') \
    .getOrCreate()




# ERROS:


## write csv in windows

File C:\spark\spark-3.3.0-bin-hadoop27\python\pyspark\sql\readwriter.py:1240, in DataFrameWriter.csv(self, path, mode, compression, sep, quote, escape, header, nullValue, escapeQuotes, quoteAll, dateFormat, timestampFormat, ignoreLeadingWhiteSpace, ignoreTrailingWhiteSpace, charToEscapeQuoteEscaping, encoding, emptyValue, lineSep)

Solução:

1.Em https://github.com/steveloughran/winutils/tree/master/hadoop-3.0.0/bin. baixar hadoop.dll e winutils.exe e colocar no diretório ./spark/hadoop/bin
2. Possuir variavel e path com $HADOOP_HOME/bin
3. Colocar o hadoop.dll em C:\Windows\System32 
4. Reiniciei o pc
5. executou


como instalar completo: https://towardsdatascience.com/installing-apache-pyspark-on-windows-10-f5f0c506bea1 bom site, parece que usa anaconda
ver tbm rapidao https://denisecase.github.io/starting-spark/




https://github.com/s911415/apache-hadoop-3.1.0-winutils/tree/master/bin
https://stackoverflow.com/questions/41851066/exception-in-thread-main-java-lang-unsatisfiedlinkerror-org-apache-hadoop-io/51821790#51821790
https://stackoverflow.com/questions/41851066/exception-in-thread-main-java-lang-unsatisfiedlinkerror-org-apache-hadoop-io



2. SPARK STREAMING 

Spark Streaming Programming Guide: https://spark.apache.org/docs/latest/streaming-programming-guide.html 