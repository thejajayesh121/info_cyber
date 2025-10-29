# Encryption Techniques
## Learning Objectives
-Understand cryptography basics
-Differentiate between symmetric and asymmetric encryption
-Learn hashing and digital signature concepts
## Cryptography
Cryptography is a technique of securing information and communications using codes to ensure confidentility,integrity and authentication.
   ## Cryptography
   Cryptography is a technique of securing information and communications using codes to ensure confidentiality,intergrity and authentication
  ## Symmetric Ecryption
  -Uses one key for both encryption and descryption.
  -Fast,suitable for bulk data encryption.
  ## Asymmetric Encryption
  -Uses two keys: public key (for encryption)&private key (for decryption).
  -Uses for secure key exchange and digital communication.
  ## Hashing
  - Converts data into a fixed-length string.
  - One-way process -cannot be reversed.
  - Used for password storage and integrity checking.
  - Common Algorithms:SHA-256,MD5(deprecated)
    ## Digital signatures and Certificates
   - Ensure authenticity and non-non-repudiation.
   - A digital signature uses privet key to sign data and public key to verify.
   - Certificates (X.509) are issued by certificate Authorities (CAs) for trust verification (used in HTTPS).
    ## Example
    when visiting https://google.com
    -Browser verifies certificate signed by CA to ensure Authenticity.
