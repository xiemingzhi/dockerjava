# What does it do?

Build an image with oracle java 8 jdk.
Run container execute Compile example.
Run container execute program

# Instructions

Install docker, windows install docker toolbox.
Open quickstart terminal. 

```
cd to-where-you-cloned-project
docker build -f Dockerfile -t demo/oracle-java:8 .
docker run --rm -v $PWD:/app -w /app demo/oracle-java:8 javac Main.java
docker run --rm -v $PWD:/app -w /app demo/oracle-java:8 java Main
```

