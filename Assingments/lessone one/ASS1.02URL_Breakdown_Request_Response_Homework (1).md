# URL Breakdown

## Example URL

``` text
https://www.example.com/products/laptops?brand=hp&sort=price#reviews
```

  ----------------------------------------------------------------------------
  Component               Example                  Description
  ----------------------- ------------------------ ---------------------------
  Protocol                `https://`               Secure communication
                                                   between the browser and the
                                                   web server.

  Subdomain               `www`                    Identifies a specific
                                                   section of the website.

  Domain Name             `example`                The website's unique name.

  Top-Level Domain (TLD)  `.com`                   Indicates the type of
                                                   domain.

  Path                    `/products/laptops`      Specifies the requested
                                                   resource.

  Query String            `?brand=hp&sort=price`   Sends additional
                                                   information to the server.

  Fragment                `#reviews`               Jumps to a specific section
                                                   of the page.
  ----------------------------------------------------------------------------

# Role-Play the Request-Response Cycle

  Role         Responsibility
  ------------ ------------------------------------------------
  User         Types the URL into the browser.
  Browser      Sends requests and displays the webpage.
  DNS Server   Translates the domain name into an IP address.
  Web Server   Processes the request and returns the webpage.

## Steps

1.  User enters a URL.
2.  Browser asks the DNS server for the IP address.
3.  DNS server returns the IP address.
4.  Browser connects to the web server.
5.  Browser sends an HTTP GET request.
6.  Web server returns HTML, CSS, JavaScript, and images.
7.  Browser renders the webpage.

# Homework

## Journey of a URL from Browser to Webpage

When I type a URL such as **https://www.example.com** into my browser
and press Enter, the browser first checks its cache for the website's IP
address. If it is not available, the browser contacts a **DNS server**,
which translates the domain name into an IP address.

Using the IP address, the browser establishes a secure **HTTPS**
connection with the web server. The browser then sends an **HTTP GET**
request for the webpage.

The web server processes the request and returns an **HTTP response**
containing HTML, CSS, JavaScript, images, and other required files.

The browser reads the HTML to build the page structure, applies CSS for
styling, executes JavaScript for interactivity, downloads images and
other resources, and finally renders the complete webpage for the user.

This entire process takes only a few seconds and allows users to view
web pages quickly and securely.
