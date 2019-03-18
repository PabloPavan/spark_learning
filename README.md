# spark_learning

## Install Apache Spark on Ubuntu 

### Install Java

```shell
sudo apt-get update
sudo apt-get install default-jdk
```

### Install Scala

```shell
sudo apt-get install scala
```

### Install Spark 

Download latest Spark  *https://spark.apache.org/downloads.html*

Create a spark folder in /usr/local/ after untar the tgz:

```shell
sudo tar xvf spark-2.X.X-bin-hadoop2.7.tgz -C /usr/local/spark
```

Add Spark path to bash file:

```shell
vim ~/.bashrc
```

Add below code snippet to the bash file:

> SPARK_HOME=/usr/local/spark

> export PATH=$SPARK_HOME/bin:$PATH

```shell
source ~/.bashrc
```



