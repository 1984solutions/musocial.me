# Running

The easiest way to run **musocial** if you have Docker installed is the following:

1. Create an "instance" directory which will store your database and config file

   `mkdir musocial-instance`
1. Run a pre-built Docker image, forwarding port 8448 (you can change that to anything you want) and mounting the above-created directory

   `docker run -d -p 8448:5000 -v $(pwd)/musocial-instance:/instance --name musocial --rm -t ghcr.io/ibz/musocial:master-buster`
1. Access musocial using your web browser

   [localhost:8448](http://localhost:8448)
