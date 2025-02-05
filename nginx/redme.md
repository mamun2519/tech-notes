# Deep Drive Nginx

## What is nginx

⇒ NGINX is open-source web server software used for reverse proxy, load balancing, and caching. It provides HTTPS server capabilities and is mainly designed for maximum performance and stability. It also functions as a proxy server for email communications protocols, such as IMAP, POP3, and SMTP.

## How NGINX works

- **Master process**: Reads configuration files, manages worker processes, and binds ports
- **Worker processes**: Handle requests, read and write disk content, and communicate with other servers
- **Cache loader process**: Loads the disk-based cache into memory at startup
- **Cache manager process**: Removes entries from the disk cache to keep it within the configured size

## what is nginx reverse proxy

An Nginx reverse proxy is a server configuration where Nginx acts as an intermediary, receiving client requests and then forwarding them to one or more backend servers to process, before returning the response back to the client, effectively hiding the identity and location of the actual backend servers while managing traffic efficiently; essentially acting as a "middleman" between the user and the web application server.
