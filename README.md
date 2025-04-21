This is an attempt to try to let EA get randomized hardinfo.
RandomNumberGenerator yields 128 cryptographically‑random bits; probability of a repeat is low
CreateNonce() is called inside GetPcSign(), a new nonce is baked into the JWT‑style token every time you instantiate it (each program run)
---
You can build your own by source code, just use VS and rename the executable to EADesktop.exe
