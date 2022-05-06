﻿# crypterapp
Crypter is a web app that provides secure local file encryption in the browser. It's fast, secure, and uses modern cryptographic algorithms with chunked AEAD stream encryption/decryption.

Crypter introduced memory efficient in-browser large file chunked encryption using streams with libsodium.

#Features
    Security
        XChaCha20-Poly1305 - for symmetric encryption.
        Argon2id - for password-based key derivation.
        X25519 - for key exchange.
        The libsodium library is used for all cryptographic algorithms.

#Privacy
#    The app runs locally in your browser.
#    No data is ever collected or sent to anyone.​
#Functionality
#    Secure multiple file encryption/decryption with passwords or keys.
#    Secure random password generation.
#    Asymmetric key pair generation.
#    Authenticated key exchange.
#    Password strength estimation.
