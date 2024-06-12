Special docker image with spark files.
Needed for clusters without internet access

curl "https://archive.apache.org/dist/spark/spark-3.2.2/spark-3.2.2-bin-hadoop3.2.tgz" > spark-3.2.2-bin-hadoop3.2.tgz
`docker build --platform linux/amd64 -f ./Dockerfile_with_spark ../`
