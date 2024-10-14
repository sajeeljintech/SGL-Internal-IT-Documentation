# Setting up Reverse Proxy

Setting up an APP01 Proxy

1. Access the NGINX Proxy Manager Web Interface. This can be done by opening a web browser to http://proxy.showgrounds.work:81
2. Log in to the NGINX Proxy Manager Web Interface using your credentials.
3. Click on the "Proxies" tab in the left-hand menu.
4. Click the "Add Proxy Host" button in the top-right corner of the screen.
5. In the "Domain Names" field, enter the domain name for the new endpoint (e.g. "clientname.4d.showgroundslive.com").
6. In the "Scheme" dropdown, select "http".
7. In the "Forward Host" field, enter the IP address of the server where the endpoint is hosted (e.g. "10.0.20.XXX").
8. In the "Forward Port" field, enter the port number where the endpoint is listening (e.g. "8080").
9. Enable WebSocket support by toggling the "Support WebSockets" switch to the "On" position.
10. Click the "Save" button to create the new endpoint. Setting up an SRN01 Proxy
11. Access the NGINX Proxy Manager Web Interface. This can be done by opening a web browser to http://proxy.showgrounds.work:81
12. Log in to the NGINX Proxy Manager Web Interface using your credentials.
13. Click on the "Proxies" tab in the left-hand menu.
14. Click the "Add Proxy Host" button in the top-right corner of the screen.
15. In the "Domain Names" field, enter the domain name for the new endpoint (e.g. "clientname.srn.showgroundslive.com").
16. In the "Scheme" dropdown, select "http".
17. In the "Forward Host" field, enter the IP address of the server where the endpoint is hosted (e.g. "10.0.20.XXX").
18. In the "Forward Port" field, enter the port number where the endpoint is listening (e.g. "1880").
19. Enable WebSocket support by toggling the "Support WebSockets" switch to the "On" position.
20. Click the "Save" button to create the new endpoint.
