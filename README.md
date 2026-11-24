# CC Vault public passkey test association

Public metadata only. The GitHub Pages origin is `https://k96732.github.io`.

The association authorizes only `com.ccvault.passkeyprobe` with the explicitly listed development signing-certificate fingerprint. It does not authorize the production vault package. No private keys, credentials, card data, vault files, analytics or scripts belong in this repository.

Serve `.well-known/assetlinks.json` unchanged over HTTPS with HTTP 200 and JSON content type. `.nojekyll` preserves the well-known directory. Pages source: branch `public-passkey-identity`, repository root.

This enables a compatibility experiment; it is not a claim of working passkey recovery or production readiness.
