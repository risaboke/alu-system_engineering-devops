# Load balancer
This project adds a second web server (web-02) and a load balancer (lb-01) to my web stack.

- 0-custom_http_response_header: installs nginx and adds an X-Served-By header with the server hostname
- 1-install_load_balancer: installs HAproxy on lb-01 and sends traffic to web-01 and web-02 using roundrobin
