# Java Cryptographic Extension (JCE)
Encryption and decryption are fundamental requirements of every secure-aware application, therefore the Java platform provides strong support for encryption and decryption through its Java Cryptographiv Extension (JCE) framework which implements the standard cryptographic algorithms such as AES, DES, DESede and RSA.

# Example Tutorial : How to basically encrypt and decrypt using AES algorithm

Advanced Encryption Standard (AES) - is a symmetric-key algorithm that uses the same key for both encryption and decryption of data

## Basic Steps
Here are the geenral steps to encrypt/decrypt a file in Java: 
1. Create a Key from a given byte array for a given algorithm.
2. Get an instance of Cipher class for a given algorithm transformation. See document
of the Cipher class for more information regarding supported algorithms and
transformations.
3. Initialize the Cipher with an appropriate mode (encrypt or decrypt) and the given
Key.
4. Invoke doFinal(input_bytes) method of the Cipher class to perform encryption
or decryption on the input_bytes, which returns an encrypted or decrypted byte
array.
5. Read an input file to a byte array and write the encrypted/decrypted byte array to an
output file accordingly
