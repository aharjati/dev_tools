# create curl container
- Run `docker build --platform linux/amd64 -t curl-test:0.1 .`
- Run `docker run -it  --platform linux/amd64 curl-test:0.1`
