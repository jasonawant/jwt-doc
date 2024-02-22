# Key (JWK) and Key Set (JWKSet)

To perform cryptographic operations (signature/verification and encryption/decryption), you will need cryptographic keys.

## JWK

A JWK object represents a key. It contains all parameters needed by the algorithm and may also provide information parameters.

This framework is able to create private and public keys easily. It can also generate those keys from external resources such as binary key files or certificates.

## JWKSet

The keys can be grouped in key sets. A `JWKSet` object represents a key set. It can contain as many keys as you need.

{% hint style="warning" %}
We strongly recommend you to avoid mixing public, private or shared keys in the same key set.
{% endhint %}
