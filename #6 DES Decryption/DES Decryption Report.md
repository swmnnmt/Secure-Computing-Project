## DES Decryption

Data Encryption Standard (DES): DES is the archetypal block cipher — an algorithm that takes a fixed-length string of plaintext bits and transforms it through a series of complicated operations into another ciphertext bitstring of the same length. In the case of DES, the block size is 64 bits. DES also uses a key to customize the transformation, so that decryption can supposedly only be performed by those who know the particular key used to encrypt. The key ostensibly consists of 64 bits; however, only 56 of these are actually used by the algorithm. Eight bits are used solely for checking parity, and are thereafter discarded. Hence the effective key length is 56 bits, and it is always quoted as such.

We will perform DES decryption in EBC mode with padding mode set to Zeros

* Templates > DES Cipher.
* Enter a text inputCipher text such as `F0 28 F0 A3 F0 19 32 EF 6C F1 0C 23 93 B1 B5 22 08 9D 0D ED 64 64 68 1A 90 76 69 D0 D7 F5 DB 10 73 36 36 33 4F D2 E1 1C 3D F2 52 8E D9 9D A5 72` (as same as the output of [Encryption Algorithm](https://github.com/swmnnmt/Secure-Computing-Project/tree/main/%235%20DES%20Encryption)) to perform decryption, and click on start.
* Define Encryption Key as `00 00 01 00 11 01 01 00` (as same as encryption key used in [Encryption Algorithm](https://github.com/swmnnmt/Secure-Computing-Project/tree/main/%235%20DES%20Encryption))

![image](https://github.com/swmnnmt/Secure-Computing-Project/blob/main/%236%20DES%20Decryption/DES%20Dec.png)

So, when we press the start button, we will get the Plain text  – `The secure computing project, DES algorithm.`
