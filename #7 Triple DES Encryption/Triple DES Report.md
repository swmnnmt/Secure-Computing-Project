## Triple DES Encryption

Triple DES (3DES or TDES), officially the Triple Data Encryption Algorithm (TDEA or Triple DEA), is a symmetric-key block cipher, which applies the DES cipher algorithm three times to each data block. The Data Encryption Standard's (DES) 56-bit key is no longer considered adequate in the face of modern cryptanalytic techniques and supercomputing power. However, an adapted version of DES, Triple DES (3DES), uses the same algorithm to produce a more secure encryption.

While the government and industry standards abbreviate the algorithm's name as TDES (Triple DES) and TDEA (Triple Data Encryption Algorithm), RFC 1851 referred to it as 3DES from the time it first promulgated the idea, and this namesake has since come into wide use by most vendors, users, and cryptographers.

### Algorithm
The original DES cipher's key size of 56 bits was generally sufficient when that algorithm was designed, but the availability of increasing computational power made brute-force attacks feasible. Triple DES provides a relatively simple method of increasing the key size of DES to protect against such attacks, without the need to design a completely new block cipher algorithm.

A naive approach to increase strength of a block encryption algorithm with short key length (like DES) would be to use two keys (K1,K2) instead of one, and encrypt each block twice.

If the original key length is n bits, one would hope this scheme provides security equivalent to using key 2n bits long. Unfortunately, this approach is vulnerable to meet-in-the-middle attack: given a known plaintext pair (x,y), such that y=E_K2 E_K1(x)), one can recover the key pair (K1,K2) in 2^n+1 steps, instead of the 2^2n steps one would expect from an ideally secure algorithm with 2n bits of key.

We will perform DES Encryption in EBC mode with padding mode set to Zeros and use two of them in Triple DES algorith,

* Templates > Triple DES Cipher.
* Enter a Plain text such as `Secure Computing Procject, Triple DES algorithm implemention.` to perform encryption, and click on start.
* Define Encryption Key as `110000000000000000000000000000000000000000000011`

![image](https://github.com/swmnnmt/Secure-Computing-Project/blob/main/%237%20Triple%20DES%20Encryption/TripleDES.png)

### DES Encryption Blocks

![image](https://github.com/swmnnmt/Secure-Computing-Project/blob/main/%237%20Triple%20DES%20Encryption/DES%20Enc%20Block.png)

So, when we press the start button, we will get the Plain text  – `03 F1 B6 FA 74 BC 2E D1 0D 37 D0 7F 84 4B F2 DE C2 B8 FE 3B 91 C8 F9 A4 FB B1 51 27 75 F2 62 9B 23 14 B2 01 C3 CA C8 46 D8 81 2A 4E 92 9E BD E3 88 6D B6 6A 47 54 F2 17 97 FF 4D C4 16 1E 3D 02`
