# Polifante1.0
This is a virtual machine with Ubuntu, Hadoop, Spark, Hive, MongoDB, and Jupyter
Polifante version 1.0.0
«Copyright 2022»      
This virtual machine was created exclusively for academic and test purposes.
This is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.
    This is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.
    You should have received a copy of the GNU General Public License along with this program. If not, see <https://www.gnu.org/licenses/>. 

Instructions
1. This VM was installed with Ubuntu Server 22.04.1 LT release and the following packages:
•	Anaconda 3
•	Apache Hadoop 3.3.1
•	Apache Hive 3.1.3
•	Java 1.8.0_352
•	Mongo 5.0.14
•	Spark 3.3.1 (Scala version 2.12.15)
A single datanode is configured, but there are no constraints on adding additional nodes.
2. Primary login user/password:
	polifante/polifante
3. By default, you will launch into the polifante session, so you need to switch to hadoop:
	sudo - hadoop
4. Once you are logged in as a hadoop user, you are able to:
•	Automatic use of any command for hdfs, for example:
	hdfs dfs -ls /
•	Use the hive command interface by opening the/home/hadoop/apache-hive-3.1.3-bin/bin directory and run:
	./hive
•	Use the spark scala interface with the command:
	spark-shell
•	Use the mongo database with the command:
	mongosh
•	Use the jupyter notebook with the command:
	jupyter notebook
	Next, open the URL in the browser, such as:
	http://127.0.0.1:8888
Note:
Drag & Drop, Copy & Paste is available after activation in the hypervisor.
 


