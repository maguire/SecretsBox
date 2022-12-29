SecretsBox
==========

An HTML/JS App that stores and retrieves secrets using dropbox

The app stores secrets encrypted using AES (CryptoJS) within AWS.

Usage
=====
Use index.html to list all secrets. Fill out the Passphrase and click the secret name to decrypt. 

Passphrase, label, secret are required fields to add a new secret

Info
====
All encryption/decryption happens locally on the client, and remote storage is NEVER sent the passphrase or raw secret.
