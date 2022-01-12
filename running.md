# Running

The easiest way to run **musocial** if you have Docker installed is the following:

1. Create an "instance" directory which will store your database and config file.

   `mkdir musocial-instance`
2. Run the pre-built Docker container, forwarding port 8448 (you can change that to anything you want) and mounting the above-created directory.

   `docker run -p 8448:80 -v $(pwd)/musocial-instance:/instance --name musocial --rm -t ghcr.io/ibz/musocial:v0.1.1-buster`
3. Access musocial using your web browser.

   http://localhost:8448
