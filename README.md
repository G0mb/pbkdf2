# PBKDF2 Key Derivation Function

This is fork of [pbkdf2_dart](https://github.com/sunkeunchoi/pbkdf2/tree/null-safety-support), as defined in [RFC 2898](http://tools.ietf.org/html/rfc2898).

## Usage

    // Create PBKDF2NS instance using the SHA256 hash. The default is to use SHA1
    PBKDF2NS gen = PBKDF2NS(hash: sha256);

    // Generate a 32 byte key using the given password and salt, with 1000 iterations
    List<int> = gen.generateKey(_password, salt, i, 32);

## Credits
Thanks you [Sunkeun Choi](https://github.com/sunkeunchoi) for addding support to 💪🏼 null safety 💪🏼