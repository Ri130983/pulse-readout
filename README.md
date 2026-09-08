# Protected readout

One encrypted page, served by GitHub Pages at `docs/index.html`.

The file is AES-256-GCM ciphertext under a key stretched from a passphrase through
600,000 rounds of PBKDF2-HMAC-SHA256. Decryption happens in the reader's browser.
There is no server, no account, and nothing here to send a passphrase to.

Nothing readable is committed to this repo. The source and the underlying data live
in a separate private repo.

Ask the owner for the passphrase.
