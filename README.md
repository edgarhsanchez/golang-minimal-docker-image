## build
`CGO_ENABLED=0 GOOS=linux go build -a -installsuffix cgo -o main .`

`docker build -t example-scratch -f Dockerfile.scratch .`

## run
`docker run -it example-scratch`