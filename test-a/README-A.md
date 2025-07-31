# Readme

docker build --tag test-a:0.0.1 .

docker run --rm -d --name test-a -p 5001:80 test-a:0.0.1

curl http://localhost:5001/greeting.json