@@ -0,0 +1,8 @@
# Hello Netcat

[![Run on Google Cloud](https://storage.googleapis.com/cloudrun/button.png)](https://deploy.cloud.run)

Run Locally:

- `docker build -t hello-netcat .`
- `docker run -p 8080:8080 -e PORT=8080 -it hello-netcat`
