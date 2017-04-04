# JWT

To help prepare for API authentication tomorrow, research [JSON Web Tokens](https://jwt.io) (known as JWTs). This should take about 30 minutes. Answer the following questions and submit this README as your homework:

1. What are the 3 parts of a JWT?
    A header, payload and signature.

2. What information does each part contain?
    Header consists of the type and the algorithm used for encrypting the JWT.
    Payload has user-defined attritubes or public claims and reserved attributes that are part of the standard.
    The signature the encoded header and payload signed with a secret that is kept on the sender and the receiver.

3. Why do people use JWTs for authentication? A great resource to read would be https://jwt.io/introduction/.
  Because in comparison to XML, it is compact, easy to sign and easy to parse.
