- Install Zeppelin
- Copy tez jars in $ZEPPELIN/interpreter/spark/
- Place the json in $ZEPPELIN/notebook/2AVFWC4HV folder as "note.json"
- In $ZEPPELIN/conf/zeppelin-env.sh add 
	- export ZEPPELIN_JAVA_OPTS="-Djava.util.Arrays.useLegacyMergeSort=true"
- Start zeppelin (https://zeppelin.incubator.apache.org/docs/install/install.html)
- Access via http://localhost:8080/#/notebook/2AVFWC4HV

