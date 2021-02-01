## RSA Decryption

In cryptography, RSA (which stands for Rivest, Shamir and Adleman who first publicly described it) is an algorithm for public-key cryptography. It is the first algorithm known to be suitable for signing as well as encryption, and was one of the first great advances in public key cryptography. RSA is widely used in electronic commerce protocols, and is believed to be sufficiently secure given sufficiently long keys and the use of up-to-date implementations.

in this report we will decrypt the following text using the RSA cipher built in CT2:

`88 9D D8 2A 7A 14 8C 06 79 BA AC EF BB 85 1E C1 4A AF 84 85 FE A5 0B 1D C3 C6 D9 8D 4C 01 74
57 3F 9A 2D BE CB 14 77 24 24 E1 B6 E9 D6 03 D0 F7 C5 39 5F 72 EF 5E 96 10 A5 21 AB 65 D0 FE
E9 B2 6C 02 EB 61 15 AD E1 70 76 19 C0 0A D4 F2 CD D9 AB 86 54 1A 4D BC 25 7E 0A EC 42 30 FC
17 50 7E F6 D4 B9 7D 58 A1 1D 12 F8 5D E6 63 77 14 16 3B 87 C9 8B B2 EC 02 65 E4 42 71 60 6B
3F E8 7E 64 4B 0D 31 22 8F B7 05 2B C0 36 76 C8 D6 49 94 99 66 26 AD E4 73 18 ED 33 3D 10 C4
77 29 F3 B4 C3 F3 CC 9C 64 B2 2D D9 58 6D 6A 22 11 EF 2F D3 96 EE 33 6B 2B 87 67 01 F2 04 93
FE F0 2C FE E7 3C B1 70 42 3A DD CE 43 5A EE 94 AB 65 78 F7 49 E9 33 AA BB 8C E3 FA 0D A0 B7
85 B4 42 B0 CF C6 9F 15 E9 F8 B0 1B 65 86 8F 6E 07 F9 9E 73 35 36 6A E2 A2 18`

**Keys: public key = (e, N); private key = (d, N)**

N =
`97837973726418359868516951718991281325771149750958732944765111213631
32802749392574002300093727799031589158811983556294019011356333461547
11470896455639414844598988543772530316799684342260008657372442996653
93453851802313775580309976978804698982229486068546397607971083305570
968358870209409102684170827187712579`

e = `11`

d =
`53366167487137287201009246392177062541329718045977490697144606116526
17892408759585819436414760617653594086624718303433101278921636433571
15347761703076044352756218828909257224867912166639117664812409274736
04083681494108652553529557950472379863877351129463207267185120618342
084129306558631987155442108022251891`

so in Template > RSA Decryption :

![image](https://github.com/swmnnmt/Secure-Computing-Project/blob/main/%238%20RSA%20Decryption/RSA_Decryption.png)

So, when we press the start button, we will get the Plain text – `Plaintext: RSA (Rivest–Shamir–Adleman) is one of the first public-key cryptosystems and is widely used for secure data transmission.`
