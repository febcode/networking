# 1. What happens when you type a URL in a browser?
Answer:
- When you type https://www.example.com in a browser, the following steps occur:
- DNS Lookup: The domain name (example.com) is resolved to an IP address.
- TCP Handshake: The browser establishes a connection with the web server (via TCP 3-way handshake).
- TLS Handshake (if HTTPS): The browser and server exchange security keys for encrypted communication.
- HTTP Request: The browser sends an HTTP GET request to fetch the web page.
- Server Response: The server returns an HTML page (with CSS, JS, images, etc.).
- Rendering: The browser processes and displays the page.
- Caching & Optimization: The browser may cache files and apply compression (e.g., gzip).
