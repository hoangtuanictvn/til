# Diffie Hellman (1976)
- First published method of public-key cryptography
- Secret sharing of an encryption key

## Examples:
1. p = 23 (modulus), g = 5 (base)
2. Alice select private a = 4 --(A=g^a mod(p))--> Bob: A = 5^4 mod(23) = 4
3. Bob select private a = 3 --(B=g^b mod(p))--> Alice: B = 5^3 mode(23) = 10
4. Alice compute: s = B^a mod(p) = g^ba mod(p) = 10^4 mod(23) = 18
5. Bob compute: s = A^b mod(p) = g^ab mod(p) = 4^3 mod (23) = 18