### Step #20

Dockerizing our app.

### To build the image
```
docker build -t helloapp .
```

### Run the container with volume
```
docker run -d -p 5000:5000 -v /Users/Abbscomp/desktop/helloapp:/desktop/helloapp --name web helloapp
```
