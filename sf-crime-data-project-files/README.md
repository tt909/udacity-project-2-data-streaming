How did changing values on the SparkSession property parameters affect the throughput and latency of the data?
processedRowsPerSecond : rate at which spark is processing data
memorynumInpuRecords : count of records processed in trigger
inputRowsPerSecond : Rate of arriving data
spark.executor.memory : executor memory
spark.execuot.cores : setting executor cores
impact on processedRowsperSecond

What were the 2-3 most efficient SparkSession property key/value pairs? Through testing multiple variations on values, how can you tell these were the most optimal?
spark.default.parellelism : in this case 100 was better than 10000 for processedRowsPerSecond
spark.sql.shuffle.partitions : 2 was better than 200 for processedRowsperSecond


Please look into screenshot folder for all the screenshots



