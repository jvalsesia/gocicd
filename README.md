# gocicd
Golang CI/CD Harness

docker buildx build --platform=linux/arm64 --platform=linux/amd64 -t docker.io/<docker hub username>/<image name>:<tag> --push -f ./Dockerfile .

docker buildx build --platform=linux/amd64 -t docker.io/jvalsesia/gocicd:latest --push -f ./Dockerfile .
