build:
	docker build -t icersong/pypiserver .
run:
	docker run -d -p 8080:80 -P -h pypiserver --name pypiserver icersong/pypiserver
clean:
	docker rm -f pypiserver
log:
	docker logs -f pypiserver
port:
	docker port pypiserver 80
enter:
	docker exec -it pypiserver /bin/bash
