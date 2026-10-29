# Snappers water pump sensor

A password-protected bench-test page for the pump pressure sensor, served as a single static file via GitHub Pages.

`index.html` is AES-256-GCM encrypted; the browser derives the key from a shared passphrase (PBKDF2-SHA256, 600k iterations) and decrypts locally.
