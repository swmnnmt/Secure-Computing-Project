## AES Encryption

The modern cipher the NSA recommends people use for most purposes is AES (Advanced Encryption Standard). It is called a “symmetric” cipher because the same key is used for encryption as for decryption.

![image](https://github.com/swmnnmt/Secure-Computing-Project/blob/main/%232%20AES/AES%20Enc.png)

There are multiple parameters and a key required for AES. The Message Encoder and Message Decoder boxes convert to formats necessary for the next stages. The parameters are:

  * Cryptographic algorithm: this is the mode in which AES is to operate
  * Action: will be Encrypt or Decrypt
  * Keysize: the number of bits in the key. 256 would be a better choice in real life
  * Chaining mode: How encrypted data from one block are used in the next?
  * Padding mode: I chose to pad blocks less than AES’s blocksize with zeroes, but there are other options
