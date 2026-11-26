# Faculty of Computer Science: Top Secret

Three student files walked into a repo. Four cryptography tools made sure
nobody could peek.


## The cast

- `*.enc`: the three secret files, locked with AES. They look like gibberish,
  and that is the point.
- `aes.key.enc`: the key to that lock, locked with RSA. A key inside a locked box.
- `hashes.sha256`: fingerprints. If you only change one letter, the whole print changes.
- `hashes.sig`: my digital signature.                          
- `Public_key.perm`: the public key. Share it with everyone, that is its job.

## Where is the private key?

Asleep on my laptop, where it belongs.
