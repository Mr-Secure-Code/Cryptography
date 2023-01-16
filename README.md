# Cryptography.
## Introduction.	

-	**Introduction to Cryptography?**

	Cryptography is the practice of securing communications by transforming plaintext into ciphertext, in order to prevent unauthorized access. The process of transforming plaintext into ciphertext is called encryption, and the reverse process of converting ciphertext back into plaintext is called decryption. Cryptography can be used to protect a wide variety of information, including financial transactions, email messages, and computer files.cryptography  are use many different encryption algorithms that have been developed for different purposes, and modern cryptographic systems often use a combination of different techniques to achieve a high level of security.

## Objective.
	
-   **Objective of Cryptography.**

	-	*Confidentiality* :- Cryptography can be used to protect the confidentiality of sensitive information by encrypting it so that it can only be read by authorized individuals.

	-	*Integrity* :- Cryptography can be used to ensure the integrity of a message or other data by detecting any changes or tampering that may occur during transmission.

	-	*Access control* :- Cryptography can be used to control access to a resource or system by providing a secure means of authentication.

	-	*Secure key-exchange* :- Cryptography can be used to securely exchange keys between parties, allowing them to communicate in a secure way.

	-	*Digital Signatures* :- Cryptography can be used to prove authenticity of the signed document and also the identity of the signer.
	
	-	*Data protection* :- Cryptography can be used to protect data stored on a computer or in transit over a network, ensuring that it is only accessible to authorized individuals.

	-	*Authentication* :- Verifying the identity of individuals or systems seeking access to information.

	-	*Non-repudiation* :- Cryptography can be used to prevent a sender or receiver from denying that they sent or received a message or other data.

-   **Types of Attack.**

	-	*Confidentiality* :- An attacker may attempt to read or steal sensitive information that is protected by encryption, by breaking the encryption key or using other cryptographic attacks.

	-	*Integrity* :- An attacker may attempt to modify or tamper with data without detection, by breaking or manipulating the cryptographic methods used to ensure integrity.

	-	*Access control* :- An attacker may attempt to gain unauthorized access to a resource or system, by breaking or manipulating the cryptographic methods used for access control.

	-	*Secure key-exchange* :- An attacker may attempt to gain access to the cryptographic keys used to encrypt and decrypt data, by breaking or manipulating the 

	-	*Digital Signature* :- An attacker may create a fake digital signature by using a stolen or otherwise obtained private key.

	-	*Data protection* :- An attacker may attempt to bypass the data protection measures in place, in order to access unauthorized data.
	
	-	*Authentication* :- An attacker may attempt to impersonate a legitimate user or system, by breaking or manipulating the cryptographic methods used for authentication.

	-	*Non-repudiation* :- An attacker may attempt to forge or falsify digital signature, to make it appear as if a message or other data came from a legitimate sender.

## Cryptography Communication.

-   **Basic Communication Model.**

	*1. Key agreement* :- This is the first stage of the cryptography communication model, where the sender and the receiver agree on a specific encryption algorithm and key exchange method.

	*2. Encryption* :- The sender creates the message and then encrypts it using the agreed encryption algorithm and the recipient's public key (in case of asymmetric encryption) or a shared secret key (in case of symmetric encryption).

	*3. Transmission* :- The sender sends the encrypted message through the channel.

	*4. Decryption*:- The receiver receives the encrypted message and decrypts it using the appropriate key (i.e private key in case of asymmetric encryption or the shared secret key in case of symmetric encryption)

	*5. Message verification* :- The receiver verifies the authenticity of the message by checking the integrity of the message, either by using a digital signature or a message authentication code (MAC).

	*6. Interpretation* :- The receiver then interprets the decrypted message to understand its meaning.

##	Types of Cryptography.

-	**Symmetric-key Cryptography** :- Symmetric-key Cryptography use the  same key for both encryption and decryption. 

-	**Asymmetric-key Cryptography** :- Asymmetric-key Cryptography use a pair of keys, one for encryption and one for decryption.

-	**Hash functions** :- Hash functions are used for data integrity and digital signature.


## Symmetric key Cryptography.

-	**Introduction Symmetric key Cryptography.**

	**Symmetric key cryptography**, also known as **secret key cryptography**, is a method of encrypting and decrypting information using the same secret key. This key is used to both encrypt and decrypt the data, and it must be kept secret from anyone who should not have access to the original information. The sender and the receiver must both have a copy of the secret key and use it to encrypt and decrypt the message. This method is relatively fast and efficient but the major drawback is that the secret key must be securely distributed and kept secret. 
	
	Examples of symmetric key algorithms include **AES**,**DES** And **Blowfish**.

-	**AES (Advanced Encryption Standard)**

-	**DES (Data Encryption Standard)**

-	**Twofish**

## Asymmetric key Cryptography.

-	**Introduction Asymmetric key Cryptography.**

	**Asymmetric key cryptography**, also known as **public key cryptography**, is a method of encrypting and decrypting data using a pair of keys: a public key and a private key. The two keys are mathematically related, but it is computationally infeasible to deduce one key from the other.
	
	A sender can use the recipient's public key to encrypt a message, and the recipient can then use their own private key to decrypt it. This ensures that only the intended recipient can read the message, as the encryption is performed using the recipient's public key, which is available to anyone.

	Example of Asymmetric key Cryptography algorithm are **RSA**,**DSA** and **ECC**.

-	**RSA (Rivest-Shamir-Adleman)**

-	**DSA (Digital Signature Algorithm)**

-	**ECC (Elliptic Curve Cryptography0**


## Hash functions.

-	**Introduction Hash Functions.**

	Hash functions are an important tool in cryptography, used to ensure the security and integrity of digital communications. They are mathematical functions that take an input, or 'message', and produce a fixed-size string of characters, known as a 'digest' or 'hash value'. The digest is unique to the input, and even a small change in the input results in a completely different digest. This makes hash functions particularly useful in cryptography as they can be used for a variety of purposes such as message integrity, password storage, digital signatures, key derivation and data indexing.

	Example of Hash functions algorithm are **MD5**, **SHA-1**, **SHA-2** And **SHA-3.**

-	**MD5**
-	**SHA-1** 
-	**SHA-2** 
-	**SHA-3**

## Cryptographic Protocols.
	
Cryptographic protocols are a set of rules and procedures that are used to secure communications and transactions. These protocols use various encryption techniques to protect the confidentiality, integrity, and authenticity of the data being transmitted. Examples of cryptographic protocols include **SSL/TLS**, **SSH**, **IPSec**, **PGP**, **VPN** and **HTTPS**.

-	**SSL/TLS** :- used for secure communication over the internet
-	**SSH** :- used for secure remote login and file transfer
-	**IPSec** :- used for secure communication between network devices
-	**PGP** :- used for secure email communication
-	**VPN** :- used to create a secure connection between remote networks
-	**HTTPS** :- used to secure communication over the internet
SSL/TLS is widely used to secure the communication on the internet.

## Cryptographic Attack.
	
-   **Types of Cryptographic Attacks**

	-	**Brute force attack** :- This type of attack involves trying every possible key or combination of keys until the correct one is found. It can be used to attack symmetric key encryption systems, such as AES or DES.

	-	**Dictionary attack** :- This type of attack involves trying a pre-computed list of words or phrases as a potential key. It can be used to attack systems that use weak passwords or passphrases as the encryption key.

	-	**Man-in-the-middle attack** :- This type of attack involves intercepting and modifying the communication between two parties without their knowledge. It can be used to attack systems that use digital certificates or public key infrastructure for authentication.

	-	**Replay attack** :- This type of attack involves intercepting and replaying a legitimate message to gain unauthorized access or perform unauthorized actions. It can be used to attack systems that rely on session keys or nonces for authentication.

	-	**Quantum Computing attack** :- This type of attack involves using the power of quantum computing to break encryption algorithms and cryptosystems that are currently considered secure.
