# auth-learning-path
A learning plan to understand protocols and standards in industry that used for identification, authentication, access-control 
This is compilation of research on implementing authentication in applications(Covering authentication using JWT for now, more approaches will follow soon)

## Fundamentals

### Cryptography

* [Assymetric Cryptography](https://en.wikipedia.org/wiki/Public-key_cryptography)
* [Digital Signatures : Verifying authenticity of message](https://en.wikipedia.org/wiki/Digital_signature)
* [Forward Secrecy :  A way to protect against future compromises of private key](https://en.wikipedia.org/wiki/Forward_secrecy)
* [Encryption vs Signing](https://stackoverflow.com/questions/454048/what-is-the-difference-between-encrypting-and-signing-in-asymmetric-encryption)
* [Encryption vs Encoding](https://stackoverflow.com/questions/4657416/difference-between-encoding-and-encryption)
* [Hashing vs Encoding cs Encryption vs Obfuscation](https://danielmiessler.com/study/encoding-encryption-hashing-obfuscation/)

## Authorization

* [Oauth 2.0 RFC](https://datatracker.ietf.org/doc/html/rfc6749)
* [OpenID Connect specification](https://openid.net/specs/openid-connect-core-1_0.html)
* [Oauth and OpenID Connect in plain English](https://www.youtube.com/watch?v=996OiexHze0)

## Authentication

* [TOTP](https://en.wikipedia.org/wiki/Time-based_one-time_password)
* [FIDO2](https://fidoalliance.org/fido2/)
* [WebAuthn](https://webauthn.io/)

### Secure Key Exchange In Public

* [Diffie Hellman Key Exchange](https://en.wikipedia.org/wiki/Diffie%E2%80%93Hellman_key_exchange)
* [An SO answer to build more understanding around DH algo, signatures, forward secrecy, etc.](https://security.stackexchange.com/a/73132/229503)
* [Diffie-Hellman key exchange implementation in node.js](https://medium.com/@moghiny/diffie-hellman-key-exchange-theory-and-practice-with-node-js-ab2575e14e8)

### Maintaining Forward Secrecy

* [Double Rachet Algo](https://signal.org/docs/specifications/doubleratchet/)
* [Signal protocol specs](https://signal.org/docs/) & [implemtation lib in js](https://github.com/signalapp/libsignal-protocol-javascript)

## Securtity Risks and Criticism of JWT

* [JWT attack - signature as MAC](https://snikt.net/blog/2019/05/16/jwt-signature-vs-mac-attacks/)
* [Recreating JWT validation bypass](https://insomniasec.com/cdn-assets/Insomnia_Security_-_JWT_Validation_Bypass_in_Auth0_Authentication_API.pdf)
* [3 JWT design flaws](https://rodarmer.squarespace.com/security-blog/2019/7/21/jwt-security-vulnerabilities)
- [Stop using JWT for sessions](http://cryto.net/~joepie91/blog/2016/06/13/stop-using-jwt-for-sessions/) and [part 2: Why your solution doesn't work](http://cryto.net/%7Ejoepie91/blog/2016/06/19/stop-using-jwt-for-sessions-part-2-why-your-solution-doesnt-work/)
- [Why JWTs Suck as Session Tokens](https://developer.okta.com/blog/2017/08/17/why-jwts-suck-as-session-tokens)
- [No Way, JOSE! Javascript Object Signing and Encryption is a Bad Standard That Everyone Should Avoid](https://paragonie.com/blog/2017/03/jwt-json-web-tokens-is-bad-standard-that-everyone-should-avoid) (including JWT, JWE and JWS)
- https://github.com/shieldfy/API-Security-Checklist/issues/6 with more resources
- [Things to Use Instead of JWT](https://kevin.burke.dev/kevin/things-to-use-instead-of-jwt/)
- [Branca as an Alternative to JWT?](https://appelsiini.net/2017/branca-alternative-to-jwt/)
- [Paseto is a Secure Alternative to the JOSE Standards (JWT, etc.)](https://paragonie.com/blog/2018/03/paseto-platform-agnostic-security-tokens-is-secure-alternative-jose-standards-jwt-etc)

## Useful Tools

* [Encode or Decode JWTs](https://www.jsonwebtoken.io/)
* [Learn JWT by reverse engineering](https://github.com/gitcommitshow/auth-jwt)
