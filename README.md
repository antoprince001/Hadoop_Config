# Hadoop_Config
Configuration files for Hadoop Single Node Cluster Setup in Linux

ssh-keygen -t rsa -P '' -f ~/.ssh/id_rsa

cat ~/.ssh/id_rsa.pub >> ~/.ssh/authorized_keys

chmod 0600 ~/.ssh/authorized_keys

Download : <b>wget https://downloads.apache.org/hadoop/common/hadoop-3.2.2/hadoop-3.2.2.tar.gz</b>

A Hadoop environment is configured by editing a set of configuration files:
* bashrc
* hadoop-env.sh
* core-site.xml
* hdfs-site.xml
* mapred-site-xml
* yarn-site.xml


## bashrc

nano .bashrc

source ~/.bashrc

## hadoop-env.sh

nano $HADOOP_HOME/etc/hadoop/hadoop-env.sh

## core-site.xml

nano $HADOOP_HOME/etc/hadoop/core-site.xml

## hdfs-site.xml

nano $HADOOP_HOME/etc/hadoop/hdfs-site.xml

## mapred-site.xml

nano $HADOOP_HOME/etc/hadoop/mapred-site.xml

## yarn-site.xml

nano $HADOOP_HOME/etc/hadoop/yarn-site.xml



