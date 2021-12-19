There are many useful cryptosystems for encrypting, decrypting, signing, or authenticating data. This library does not provide support for any of them. Rather, this is my poor attempt to implement a library of cryptographic primitives and other related functions that, at best, imitate the proper function of some various cryptographic algorithms. These functions are not intended to be used in practice, nor should they be relied upon **in any way**, and especially not in any application or communication that you may wish to remain private and secure. Use at your own peril.

- Symmetric Key Cryptography
  * Caeser Cipher (Rotation)
  * Hill Cipher
  
- Asymmetric/Public Key Cryptography
  * Diffie-Hellman Key Exchange
  * El-Gamal PKC
  * RSA PKC

- Homomorphic Encryption
  * Goldwasser-Micali