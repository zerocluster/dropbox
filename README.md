# Resources

Ports:

-   17500 - communication port, TCP;

Volumes:

-   /root/Dropbox - default share folder location;
-   /root/.dropbox - cache;

# Check dropbox status

```sh
docker exec dropbox dropbox status
```

# Install

```sh
mkdir /var/local/dropbox

cd /var/local/dropbox

curl -fsSLO https://bitbucket.org/softvisio/dropbox/raw/master/dropbox.sh && chmod +x dropbox.sh

/var/local/dropbox/dropbox.sh
```
