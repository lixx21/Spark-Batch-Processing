# Spark

Spark can be used when your data is in the data lake (S3/GCS) and you have bunch of packet files there, then spark will pull this data from the data lake and do some processing and then put this data back to the data lake. Or in simple way, we can use this spark to do transformation in our data lake and save the transformation's output back to the data lake again. If you want to use SQL to transform your data lake, we can transform it using Athena, etc. But, if you want to transform something complex, we can use spark for it.

When you running the spark's session in python, then we can use **localhost:4040** to see the Spark Master UI that we can see the process in spark that we run.

# Dataset
Download the dataset [HERE](https://github.com/DataTalksClub/nyc-tlc-data/releases/tag/fhvhv)