Runs a spark master in a docker container

## Exposed ports

* TCP   7077    Spark Mater
* TCP   8080	Spark Master WebUI HTTP connector

## Example

```bash
docker run -d --name namenode -p 8080:8080 -p 7077:7077 hauptmedia/spark-master
```

