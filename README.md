# checklist.js

Following the below best practices of Security for a Node.js Application

- [ ] Infra
    - [ ] Enable http(s)
    - [ ] nginx
      - [ ] Rate Limiting (cloud based / in-house)
      - [ ] Load Balancing
    - [ ] Run Node.js applications in non-root user mode

- [ ] Application
    - [ ] Authentication ( username/password or jwt validation )
    - [ ] Authorization ( permissions )
    - [ ] Cross-Origin Resource Sharing (cors)
    - [ ] Cross-Site Scripting (xss)
    - [ ] input header validation ( helmet )
    - [ ] input body validation ( class-validator and class-transformer )
    - [ ] jwt invalidation ( cache and invalidate to stop attacks against compromised jwts )
    - [ ] handle basic status codes ( 4xx and 5xx )

- [ ] Database
    - [ ] Encrypting passwords (bcrypt)

* More to come
