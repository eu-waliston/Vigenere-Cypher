![Vigenere](https://github.com/eu-waliston/Vigenere-Cypher/assets/82295321/e37ea883-8efb-44e4-92fa-829a6885e5e2)


# Vigenere Cypher Program in Java

### Introduction:

The text can be encrypted and decrypted using the Vigenere cypher algorithm. Caesar cyphers are related to the Vigenere cipher. It is a technique for encrypting alphabetic text. The letter structure of a keyword serves as its basis. Polyalphabetic characters are used in this substitution cypher. It is easy to comprehend and apply this algorithm. This algorithm was first introduced in 1553 by Giovan Battista Bellaso.

### Algorithm:

1. Enter the term and the plaintext.
2. To make the keyword the length of the plaintext, repeat it.
3. Implement modular addition of the repeated keyword and the plaintext when encrypting data.

    Ci = Pi + Ki(mod m)

    Where Ci is the cipher text,

    Pi is the plaintext,

    Ki is the repeating keyword, and 'm' is the length of the alphabet.

4. Decryption: Perform modular subtraction of key phrases from the cipher text.

    Pi = Ci - Ki

    (mod m)

5. Display the encrypted and decrypted message as well.
