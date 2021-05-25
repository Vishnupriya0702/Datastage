# Datastage


Lookup:
Join condiiton not met : Fail, drop
Lookup has different  Lookup failure conditions: 1. Fail, 2. continue. 3. Reject 4. Drop
Drop acts as Inner Join
Continue acts as Left join
Also, we can add the filter condition


Range lookup - Between conditions also can be performed.

Aggregator :

Copy stage - same as Replicate

Aggregator - Partitioning - Hash

All the Aggrgator & Join- should be partitioned by sorted by Hash.

Enable Partitioning reads : Read the data parallely from teh system
           Modulus - Partition by round robin
           Maximum and minimum range - Partition by range
           
  Record count - count after record count paritions
  Run before & after Sql Statementes: To drop Index and add the Index
  
  Metadata - Metadata connections.
  
  Filter operation- 2 filters can be given. Data can be filtered. Null vlaues can be handled.

