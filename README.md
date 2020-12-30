# Java 6 with ant 1.9.15

JDK version 6 with ant builder 1.9.15

## How to Run

git clone https://github.com/ralexsander/docker-java-6.git
cd docker-java-6
docker build --tag ralexsander/java:6 .
docker run --rm -ti --volume ~/workspace:/workspace ralexsander/java:6
