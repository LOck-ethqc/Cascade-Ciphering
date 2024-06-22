# Cascade Ciphering
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

## Proof-of-Concept
![4](https://github.com/LOck-ethqc/Cascade-Ciphering/assets/90512716/ae8866b7-3192-4fbd-b887-8565358149a9)
![1](https://github.com/LOck-ethqc/Cascade-Ciphering/assets/90512716/459aeb43-ce90-49cb-a14d-87afd92dcf6c) ![2](https://github.com/LOck-ethqc/Cascade-Ciphering/assets/90512716/60c275e3-083f-4901-8a16-a18591633619)
![3](https://github.com/LOck-ethqc/Cascade-Ciphering/assets/90512716/93ce366c-30b6-4603-a386-e20e8131cb18)




