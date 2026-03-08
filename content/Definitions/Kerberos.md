a security protocol designed for authenticating trusted hosts even through untrusted networks.

three main elements
- [[Kerberos primary]]
- [[Kerberos instance]]
- [[Kerberos realm]]

the main workflow to grant access to a service for a client from the server is
1. client requests an [[authentication ticket]] or [[Ticket-Granting-Ticket THT]] with it's credentials
2. the authentication service checks the credentials
3. whichever ticket is encrypting use the [[Ticket Granting Service TGS]]
4. the client uses the TGT to ask the TGS (usually also the KDC) for access to a particular service
5. the TGS sends back a session key for the requested service
6. The client uses the session key with the service