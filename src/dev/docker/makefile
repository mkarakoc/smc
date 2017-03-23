build:
	docker -dns 10.0.128.100 build -t smc .

build-full:
	docker -dns 10.0.128.100 build --no-cache -t smc .

run:
	mkdir -p ../../data/projects && docker run -v `pwd`/../../data/projects:/projects -P smc

