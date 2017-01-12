# InvOcc website 
Based on http://www.free-css.com/free-css-templates/page206/ruma

### Usage with Nginx based Dockerfile

#### Build
```bash
docker build -t invocc_site .
```

#### Run
```bash
docker run -p 80:80 -d invocc_site
```