cert:
    docker build . -f Dockerfile.cert -t cert && \
    docker run -v $(CURDIR):/etc/letsencrypt cert \
    certbot --nginx -d example.com -d www.example.com