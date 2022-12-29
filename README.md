# Qyint-Community / keys
- - -

# Collection of PGP Public Keys from our Members

## What are PGP Public Keys and why do we use them?
(We will not go into Detail here, if you want to learn more, your Search Engine of Choice is your best Friend.)
You can generate a digital Pair of Keys.

You can use your Private Key to encrypt a Message or File.
Now other People can use your Public Key to decrypt it, so they can read it.
This verifies that you are, in fact, the real you - otherwise the decryption with the Public Key would not have worked.

Other People can also encrypt a Message with your Public Key.
Now only you with your Private Key can decrypt and read it.

You can also encrypt a Message with your Private Key and someone elses Public Key.
Now other People need both your Public Key and the other Persons Private Key to decrypt it.
Of course, only the other Person has this Private Key, so you can communicate with eachother and noone can see what you are saying.

Administrators are required to provide a PGP Public Key, so they can verify that they are actually themselves.

## How do I find someones Key in this Repository?
`[name]-pgp-public-key` - [name]s Public Key,
Example: `mish-pgp-public-key` → [mishs](https://qyint-community.github.io/mish) Public Key

## How do I add my Public Key here to benefit from this?
Simply start an Issue or a Pull Request that adds your Public Key.
Alternatively you could send your Public Key to an Administrator to let them add it for you.
