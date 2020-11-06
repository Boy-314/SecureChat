# SecureChat
A simplified Signal protocol in Go. Developed by Willie Yee, William Brower, and Joseph Bonneau. Implements the cryptographic logic for a secure messaging client. The security goals are to achieve integrity and confidentiality of all messages transmitted, deniable session authentication, forward secrecy at the level of individual messages, and recovery from compromise. Also recovers gracefully from errors and handles messages delivered out-of-order.

### Security warning
Please do not use this for security-critical applications.
