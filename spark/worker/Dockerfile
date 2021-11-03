FROM spark-base

CMD /bin/spark-class org.apache.spark.deploy.worker.Worker://${SPARK_MASTER_HOST}:${SPARK_MASTER_PORT} >> logs/spark-worker.log