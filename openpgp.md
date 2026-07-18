---
layout: default
title: OpenPGP
sitemap: true
---

# OpenPGP

*Last updated: July 15, 2026*

## Email encryption/signing

### Work email

- [DCF1 CF10 361E 2A40 0564 8800 1032 5838 99AC 0FCD](https://dingherself.com/.well-known/openpgpkey/hu/DCF1CF10361E2A40056488001032583899AC0FCD)

### Personal email

N.B. The private key for this one is <a href="https://proton.me/support/how-is-the-private-key-stored" target="_blank" rel="noopener noreferrer">managed by Proton</a>, even if they claim not to have access to the password that protects it.

- [305B 290E FB24 357D 5825  DF27 D483 38D6 680C 1B21](https://dingherself.com/.well-known/openpgpkey/hu/305B290EFB24357D5825DF27D48338D6680C1B21)

## If more security is needed...

Encrypt your message to this dedicated key and send it over directly in plain text.

- [5F753 E2979 BB902 23C81 0FE80 DE5A4 30CD4 E9C98 D9160 725EF](https://dingherself.com/.well-known/openpgpkey/hu/5F753E2979BB90223C810FE80DE5A430CD4E9C98D9160725EF7C012A208B4D36)

You can also fetch the keys via WKD. Or,

``` 
curl -s https://dingherself.com/.well-known/openpgpkey/hu/DCF1CF10361E2A40056488001032583899AC0FCD https://dingherself.com/.well-known/openpgpkey/hu/305B290EFB24357D5825DF27D48338D6680C1B21 https://dingherself.com/.well-known/openpgpkey/hu/5F753E2979BB90223C810FE80DE5A430CD4E9C98D9160725EF7C012A208B4D36 | gpg --import
```
