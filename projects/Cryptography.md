---
layout: project
type: project
image: img/IMG_3553.jpeg
title: "Crypto"
date: 2022
published: true
labels:
  - Crytography
  - Decoding
  - Encoding
  - GitHub
summary: "Cryptography is the practice and study of securing information and communication through techniques that prevent unauthorized access, tampering, or interception.."
---

<img class="img-fluid" src="../img/IMG_3553.jpeg">

Implementing a Caesar Cipher for Encryption and Decryption
For this assignment, I implemented a Caesar cipher, a fundamental cryptographic technique used for encryption and decryption. The Caesar cipher is a substitution cipher that shifts each letter in the plaintext forward by a fixed number of positions in the alphabet. To decrypt the message, the shift is simply reversed. This project allowed me to explore basic cryptographic principles, particularly character manipulation and modular arithmetic, while reinforcing my understanding of programming in C.

Encryption Process

To encrypt a message, I designed a function that iterates through each character in the input string. If the character is a letter, it is shifted forward in the alphabet by the specified shift value. To ensure that the transformation is case-sensitive, I determined whether the character was uppercase or lowercase and adjusted the shift accordingly. Additionally, I used modular arithmetic to wrap around the alphabet so that letters beyond 'Z' or 'z' would correctly cycle back to 'A' or 'a'. The implementation is as follows:

#include <stdio.h>
#include <ctype.h>

void encrypt(char *message, int shift) {
    for (int i = 0; message[i] != '\0'; i++) {
        if (isalpha(message[i])) {
            char base = isupper(message[i]) ? 'A' : 'a';
            message[i] = (message[i] - base + shift) % 26 + base;
        }
    }
}
Decryption Process

For decryption, I implemented a similar function that shifts each letter backward by the same shift value. To prevent negative values during the shift, I added 26 before applying the modulo operation, ensuring correct wrap-around behavior. The decryption function is as follows:

void decrypt(char *message, int shift) {
    for (int i = 0; message[i] != '\0'; i++) {
        if (isalpha(message[i])) {
            char base = isupper(message[i]) ? 'A' : 'a';
            message[i] = (message[i] - base - shift + 26) % 26 + base;
        }
    }
}
User Interaction and Execution

To allow user input and demonstrate the encryption and decryption process, I implemented a main() function. This function prompts the user to enter a message and a shift value, then displays both the encrypted and decrypted versions of the message.

int main() {
    char message[100];
    int shift;

    printf("Enter a message to encrypt: ");
    fgets(message, sizeof(message), stdin);

    printf("Enter shift value: ");
    scanf("%d", &shift);

    encrypt(message, shift);
    printf("Encrypted message: %s\n", message);

    decrypt(message, shift);
    printf("Decrypted message: %s\n", message);

    return 0;
}
In this implementation, I used isalpha() to ensure that only alphabetic characters were modified while leaving spaces and punctuation unchanged. The use of modular arithmetic allowed for seamless letter shifting without exceeding the boundaries of the alphabet. By handling uppercase and lowercase letters separately, I preserved the integrity of the original message.

Conclusion

Through this assignment, I gained a deeper understanding of encryption techniques and their practical applications. While the Caesar cipher is relatively easy to break due to its limited key space, implementing it helped reinforce the importance of modular arithmetic, character manipulation, and secure communication principles. This project also highlighted the necessity of more advanced encryption methods, such as AES or RSA, for real-world cryptographic security. Overall, this exercise provided a strong foundation in cryptographic programming and algorithmic thinking.
 
Source: <a href="https://github.com/theVacay/vacay">theVacay/vacay</a>
