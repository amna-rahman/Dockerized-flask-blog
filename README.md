# Dockerized Blog made in flask


"Programming isn't about what you know; it's about what you can figure out.” 

- Chris Pine


## Milestones

https://github.com/amna-rahman/Dockerized-flask-blog




## Installation & Start


1.Inside flask_folder,run the following command

```bash
nerdctl build -t flask-blog:v1 .
```


2. After the image is created, Run the following comand

```bash
nerdctl run -p 5000:5000 flask-blog:v1
```

open browser, http://localhost:5000


##Docker Image 

https://hub.docker.com/r/amnarahman/flask-blog


```bash
nerdctl pull amnarahman/flask-blog
```

## License

MIT
