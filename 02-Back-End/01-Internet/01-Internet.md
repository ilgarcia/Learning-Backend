# Internet

## How does the internet work

<p>
  <img src="./img-md/Cap-01-Layers.png" alt="Layers" style="width:250px;" />
</p>

Client > Modem > Servidor

- Modem (Gateway) --> Makes the modulation/demodulation of the information.

IP identify the client (point "A") and server (point "B"), and the TCP from point "B" encrypts the file and breaks the info  in small packages and send those packages to point "A" in different order and different routes, TCP also takes this packages and reverts to the original info at point "A".

- TCP --> Transfer Control Protocol
- IP --> Internet Protocol

## What is HTTP/HTTPS and APIs

### HTTP - Hypertext Transfer Protocol

HTTP is a client-server protocol, which through a user-agent (or a proxy on behalf of the user) sends requests, each individual request is sent to a server, which will handle it and provide a result, called a response.

Features controlled with HTTP:
- Cache
- Relaxation of constraints at the origin
- Authentication
- Proxy and tunneling
- Sessões

### HTTPS - Hypertext Transfer Protocol Secure

Is an implementation of the HTTP protocol over an additional layer of security that uses the SSL/TLS protocol. This additional layer allows data to be transmitted over an encrypted connection and to verify server and client authenticity through digital certificates.

### APIs - Application Programming Interface

API is nothing more than a form of communication between systems. They allow the integration between two systems, where one of them provides information and services that can be used by the other, without the need for the system that consumes the API to know the implementation details of the software.

## Browser and how they work

The browser or web browser is responsible for communicating with the servers allowing web browsing, it is the one that processes the data received in response by the Internet servers, capable of processing different languages such as HTML, ASP, PHP. Its interface will vary depending on the brand, where the user chooses.

## DNS and how it works
*DNS - Domain name system*

converts human-readable domain names (e.g. www.amazon.com) to machine-readable IP addresses (e.g. 192.0.2.44)

## What is Domain Name

`https://www.subdomain.domain.TLD/path`

The name that identifies your site
- Uniq name
- Paid annually
- You have to chose a TLD (Top Level Domais)
*TLD - .com, .net, .io,  ...* 

- GTLD (Generic) - .com, .edu, .net, .io,  ...
- CCTLD (Country Code) - .br, .us, ...

## What is hosting

Server where you are using for hosting a site
- Space to store files
- Paid monthly
- You chose your hosting by space, memory, recurses
