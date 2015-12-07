docker build -t modelcv:latest .
docker create -l modelcv --name=modelcv -p=8081:80 modelcv:latest
docker start modelcv
