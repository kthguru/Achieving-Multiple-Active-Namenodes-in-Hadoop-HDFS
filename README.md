# Acheving Multiple Active Namenodes in Hadoop HDFS
Acheving Multiple Active Namenodes in Hadoop HDFS

## Step 1. Download the Apache Hadoop Source Code
`git clone https://github.com/apache/hadoop`

```bash
git clone https://github.com/apache/hadoop
cd hadoop
git checkout rel/release-3.2.1
```
*Need to check if head hash as prefix is as follows*
```
b3cbbb4
```

## Step 2. Apply the Patch and Re-build it
*Number of files to be modified: 30, Number of lines of Java code to be added: 7,000
```bash

```

## Step 3. Prepare the Node (minimal option)
```bash
2 Active Namenodes
1 Datanode
```
*The followings are not needed more: QJM, Journal Nodes (2k+1), Zookeeper, Standby Namenode, Observer Namenode, etc.


## Step 4. Deploy the Hadoop (one-touch installation without human-intervention)
```bash

```

## Step 5. Launch the Hadoop (one-touch launching using only-one script without complex scripts)
```bash

```

## Step 6. Upload the files (via HDFS API like Hive/Presto does)
```bash
Using HDFS API is recommended. WebGUI or CLI can be also used.
```

## Step 7. Check the files replicated over all Namenodes
```bash

```


## Publications
2021 IEEE International IOT, Electronics and Mechatronics Conference
```
https://ieeexplore.ieee.org/Xplore/home.jsp
```
