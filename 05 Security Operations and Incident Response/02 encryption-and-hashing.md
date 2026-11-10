# Encryption and Hashing

## 1. Cryptography

Cryptography uses mathematical techniques to protect information.

Its purposes include:
- Confidentiality
- Integrity
- Authentication
- Non-repudiation

## 2. Symmetric Encryption

Symmetric encryption uses the same secret key to encrypt and decrypt information.

Example:
- A sender encrypts a file with a secret key.
- The receiver uses the same key to decrypt it.

Advantages:
- Generally fast
- Efficient for large amounts of data

Challenges:
- The secret key must be shared securely.
- Anyone who obtains the key may be able to decrypt the data.

Example algorithm: AES (Advanced Encryption Standard).

## 3. Asymmetric Encryption

Asymmetric encryption uses a mathematically related key pair:

- **Public key:** Can be shared with others.
- **Private key:** Must be kept secret by its owner.

In a common confidentiality example:
1. A sender encrypts information using the recipient's public key.
2. The recipient decrypts it using their private key.

Asymmetric cryptography can also support digital signatures.

Example algorithm: RSA.

## 4. Symmetric vs. Asymmetric Encryption

| Symmetric | Asymmetric |
|---|---|
| One shared secret key | Public and private key pair |
| Generally faster | Generally slower |
| Useful for large data transfers | Useful for key exchange and digital signatures |
| Key sharing must be protected | Public key can be distributed |

Secure communication systems often use both methods together.

## 5. Hashing

Hashing converts data into a fixed-length output called a hash or digest.

Important characteristics:
- The same input produces the same hash when the algorithm is unchanged.
- A small input change should produce a significantly different digest.
- A secure cryptographic hash is designed to make it impractical to recover the original input.
- Hashing is not encryption and is not designed to be reversed.

Example algorithms:
- SHA-256
- SHA-3

MD5 and SHA-1 are considered unsuitable for many security-sensitive uses because of known weaknesses.

## 6. Encryption vs. Hashing

| Encryption | Hashing |
|---|---|
| Protects confidentiality | Commonly supports integrity verification |
| Uses keys | Standard hash functions do not use a decryption key |
| Designed to be reversible with the proper key | Designed to be one-way |
| Produces ciphertext | Produces a digest |

## 7. Digital Signatures

Digital signatures help verify:
- **Authenticity:** Who signed the information?
- **Integrity:** Has the information changed?
- **Non-repudiation:** Provides evidence that can help prevent a signer from credibly denying a signature, depending on the system and circumstances.

A simplified signing process:
1. The sender creates a hash of the message.
2. The sender signs the hash using their private key.
3. The recipient uses the sender's public key to verify the signature.
4. The recipient checks the message's hash.

## 8. Digital Certificates and PKI

A digital certificate connects an identity to a public key.

Public Key Infrastructure (PKI) is the system of technologies, policies, and processes used to manage digital certificates and public keys.

Important terms:
- **Certificate Authority (CA):** Issues and signs certificates.
- **Certificate:** Binds an identity to a public key.
- **Public key:** Can be shared.
- **Private key:** Must be protected.
- **Certificate revocation:** Marks a certificate as no longer trusted before its expiration.

## 9. Encryption in Everyday Use

Examples:
- HTTPS protects web communications.
- Full-disk encryption protects stored information.
- VPNs use encryption to protect network traffic.
- Encrypted messaging protects message contents.

Encryption does not automatically protect a device from malware or an authorized user misusing information.

## 10. Quantum-Resistant Cryptography

Quantum computers could eventually threaten some widely used public-key cryptographic systems.

Post-quantum cryptography refers to cryptographic algorithms designed to resist attacks from both classical and sufficiently capable quantum computers.

Organizations need to consider:
- Which cryptographic systems they use
- Where vulnerable algorithms are deployed
- How they will transition to newer standards
- How long sensitive information must remain protected

## Key Takeaways

- Symmetric encryption uses one shared secret key.
- Asymmetric encryption uses public and private keys.
- Hashing is one-way and is not encryption.
- Digital signatures help establish authenticity and integrity.
- PKI manages certificates and public-key trust.
- Post-quantum cryptography addresses potential future quantum threats.