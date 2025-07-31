# Readme B


docker build --tag test-b:0.0.1 .

docker run --rm -d --name test-b -p 5002:80 test-b:0.0.1

http://localhost:5002