Advanced Encryption Standard (AES)

  Advanced Encryption Standard (AES), as a symmetric block cipher is implemented in C++. 
AES is a symmetric block cipher, i.e., the same key is used for both encryption and decryption of the plaintext. 
The message is a 128-bit length bitstream and the key can be of length 128, 192, and 256-bit. 
For the case, that the message is longer or shorter than 128-bit, zero bits are padded to fit it into 128-bit blocks. 
In order to improve the resilience of the cipher against the cryptoanalysis different modes of operation 
such as electronic code book or cipher block chaining (CBC) mode can be used. In this implementation, ECB is used 
to demonstrate the efficiency of the AES on messages with any length greater than 128-bit. 
However, extending the underlying AES to different modes of operation is straight forward. 
