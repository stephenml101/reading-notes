# HTTP

[Review: High-level HTTP](https://dev.to/dangolant/things-i-brushed-up-on-this-week-the-http-request-lifecycle-)

1. What are the five steps in the HTTP Request Lifecycle?

- Local Processing
- Resolve an IP
- Establish a TCP Connection
- Send an HTTP Request
- Tearing Down and Cleaning Up


2. What are the two things the client needs before it can make an HTTP Request?

- IP Address and TCP Connection


3. Explain the four way handshake and what it does.

- The client sends a FIN packet at the TCP level, to which the server responds with an ACK, and then generally sends a FIN of its own, which the client responds to with its own ACK signal. The client then waits for a brief timeout, during which it cannot accept new connections, to prevent delayed packets from previous connections arriving during subsequent activities on the port.

- Signals the end of the TCP connection.

[Java HTTP Request example](https://www.baeldung.com/java-http-request)

1. True or False: When making an HTTP request, you MUST follow any redirect returned by the request. Back up your answer.

- True, it has to take you to the correct source.

2. Which built-in Java class can be used to perform an HTTP request?

- HttpUrlConnection


3. What HTTP status codes represent a successful response? A redirect? A client error?

- Success - 200
- Redirect - 301 or 302
- Error - 299