# Cascade-Ciphering
TL;DR Cascade Ciphering GUI Program that utilizes OTP &amp; AES encryption methods and MD5 hashing function to encrypt AND decrypt messages.

## Description
- Programming Language: Python
- Cryptographic System: Cascade Ciphering(Vigenère + AES)
- AES Operation Mode: ECB(Electronic CodeBook)
- AE(Authentication Encryption): EtM(Encrypt-then-MAC)
- MAC(Message Authentication Code): MD5 Hash

## Limitations
- Plaintext is limited to 128 bits(16 characters), larger bits will not generate any ciphertext.
- OTP Key MUST consist of 128 bits(16 characters), smaller OR larger bits will lead to failure in OTP encryption.
- Only English Alphabet characters are eligible to be used(special characters are excluded).
- AES Encryption is processed once(1-Round).

## How To Use
1) Save the source code `Cascade_Ciphering.py` to your machine.
2) Run CMD and execute `py Cascade_Ciphering.py`

> [!NOTE]
> Python must be installed beforehand to be able to run the code.
