# Encrypted Tokens (JWE)

To use the encrypted tokens (JWE), you have to install the [`web-token/jwt-encryption` component](https://github.com/web-token/jwt-encryption).

```bash
composer require web-token/jwt-encryption
```

This component provides lot of encryption algorithms and classes to load and create encrypted tokens.

Please refer to [this encryption algorithm table](encryption-algorithms.md) to know what algorithms are available.

Then, you will find an [example to create an encrypted token here](jwe-creation.md) and another [example to load and decrypt](jwe-loading.md) incoming tokens.
