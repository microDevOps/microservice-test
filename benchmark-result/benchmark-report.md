#RPC性能报告
> 生成时间: 2018-04-03T02:09:39.474467<br>
> 运行环境: Linux, Java HotSpot(TM) 64-Bit Server VM 9.0.4+11<br>
> 启动参数: java -server -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC<br>


##existUser
| framework | thrpt (ops/ms) | avgt (ms) | p90 (ms) | p99 (ms) | p999 (ms) |
| :--- | :---: | :---: | :---: | :---: | :---: |
|dubbo|26.774|1.186|1.427|1.919|7.096|
|springboot|9.352|2.179|2.855|21.555|59.528|


##createUser
| framework | thrpt (ops/ms) | avgt (ms) | p90 (ms) | p99 (ms) | p999 (ms) |
| :--- | :---: | :---: | :---: | :---: | :---: |
|dubbo|14.762|2.205|2.576|4.088|14.34|
|springboot|6.298|2.184|3.572|19.988|49.82|


##getUser
| framework | thrpt (ops/ms) | avgt (ms) | p90 (ms) | p99 (ms) | p999 (ms) |
| :--- | :---: | :---: | :---: | :---: | :---: |
|dubbo|14.805|2.464|2.863|4.309|14.964|
|springboot|10.571|2.251|3.166|21.842|49.48|


##listUser
| framework | thrpt (ops/ms) | avgt (ms) | p90 (ms) | p99 (ms) | p999 (ms) |
| :--- | :---: | :---: | :---: | :---: | :---: |
|springboot|12.051|2.574|3.903|23.171|49.582|
|dubbo|3.089|10.593|13.287|17.673|34.117|

