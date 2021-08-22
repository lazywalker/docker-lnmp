APT="mirrors.ustc.edu.cn"
TAG=mine
VER=mine

all:
	docker pull mlocati/php-extension-installer
	docker build --build-arg APT="${APT}" -t lazywalker/php7-fpm-alpine:${VER} -f Dockerfile.${TAG} .

push:
	docker push lazywalker/php7-fpm-alpine:${VER}