SecretsBox
==========

An HTML/JS App that stores and retrieves secrets using dropbox

The app stores secrets encrypted using AES (CryptoJS) within dropbox.

Usage
=====
Use put.html to encrypt and then write that encrypted string to dropbox

Use get.html to list all secrets. Fill out the Passphrase and click the secret name to decrypt. 

Info
====
All encryption/decryption happens locally on the client, and dropbox is sent the passphrase or raw secret.
