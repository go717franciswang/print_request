### Summary
Spin up a docker container that print out the request header and variables

### Run
```
docker build -t print_request .
docker run -p 8080:80 print_request
```
