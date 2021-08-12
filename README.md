# node-docker
把一个node项目docker化


# build a image
`docker build . -t colaliu/node-web-app`

# run
`docker run -p 49161:8080 -d colaliu/node-web-app`              


# test
`curl -i localhost:49161`