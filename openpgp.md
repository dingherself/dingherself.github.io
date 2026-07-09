---
layout: default
title: OpenPGP
sitemap: true
---

# OpenPGP

**2026-07-05: New keys for PQC cipher**

For email encryption/signing (note that the private key for this one is <a href="https://proton.me/support/how-is-the-private-key-stored" target="_blank" rel="noopener noreferrer">managed by Proton</a>, even if they claim not to have access to the password that protects it):

- [305B 290E FB24 357D 5825  DF27 D483 38D6 680C 1B21](https://openpgpkey.dingthemself.com/.well-known/openpgpkey/dingthemself.com/hu/8n7kp7z3z33ssxk5e5zcya58g4o9y9az)

If better security is needed, encrypt your message to this key (which I keep offline) and send it over directly in plain text:

- [5F753 E2979 BB902 23C81 0FE80 DE5A4 30CD4 E9C98 D9160 725EF](https://openpgpkey.dingthemself.com/.well-known/openpgpkey/dingthemself.com/hu/8g1e4z8b7aju56yjyd9ufqsyhndkytsr)

You can also fetch the keys via WKD. Or,

``` 
curl -s https://openpgpkey.dingthemself.com/.well-known/openpgpkey/dingthemself.com/hu/8n7kp7z3z33ssxk5e5zcya58g4o9y9az https://openpgpkey.dingthemself.com/.well-known/openpgpkey/dingthemself.com/hu/8g1e4z8b7aju56yjyd9ufqsyhndkytsr | gpg --import
```

