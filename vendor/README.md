# Vendored libraries

Unmodified files from two MIT-licensed, dependency-free packages. The status
page uses them to decrypt its data, because the browser's built-in Web Crypto
is unavailable when a page is served over plain HTTP.

| Directory | Package | Version | Files |
|---|---|---|---|
| `noble-ciphers/` | `@noble/ciphers` | 2.4.0 | `aes.js`, `_polyval.js`, `utils.js` |
| `noble-hashes/` | `@noble/hashes` | 2.4.0 | `pbkdf2.js`, `hmac.js`, `sha2.js`, `_md.js`, `_u64.js`, `utils.js` |

To update: `npm pack @noble/ciphers @noble/hashes`, then copy the same files.
