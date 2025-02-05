# Bitcoin Crypto Proofs

A library to prove all hash functions used in [Bitcoin (Script)](https://en.bitcoin.it/wiki/Script#Crypto) as well as ECDSA and Schnorr signatures.

## Bitcoin Hashes

- OP_RIPEMD160: The input is hashed using RIPEMD-160.
- OP_SHA1: The input is hashed using SHA-1.
- OP_SHA256: The input is hashed using SHA-256.
- OP_HASH160: The input is hashed twice: first with SHA-256 and then with RIPEMD-160.
- OP_HASH256: The input is hashed two times with SHA-256.

## Bitcoin Signatures

STARK proofs for ECDSA and Schnorr signatures over the secp256k1 curve. ECDSA signatures are DER encoded.