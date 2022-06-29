# OpenSSL-Universal

This is a simplification of the original
[OpenSSL-Universal](https://github.com/krzyzanowskim/OpenSSL.git)
project. It focuses on usability for iOS (native and simulator). It
does not sign the library and minimizes dependencies.

### Support

Please sponsor the original project, see
[Sponsorship](https://github.com/users/krzyzanowskim/sponsorship) to
fulfill your duty.

### Architectures

- iOS with architectures: armv7, armv7s, arm64 + simulator (x86_64, arm64)

#### Output Formats

- [OpenSSL.xcframework](Frameworks/)

### Why?

[Apple says](https://developer.apple.com/library/mac/documentation/security/Conceptual/cryptoservices/GeneralPurposeCrypto/GeneralPurposeCrypto.html):  
"Although OpenSSL is commonly used in the open source community,
OpenSSL does not provide a stable API from version to version. For
this reason, although OS X provides OpenSSL libraries, the OpenSSL
libraries in OS X are deprecated, and OpenSSL has never been provided
as part of iOS."

### Installation

#### Build

This project can be built locally:

```
$ cd OpenSSL
$ make
```

The result of a build process is put inside [Frameworks](Frameworks/)
directory.

### Authors

[Marcin Krzyżanowski](https://twitter.com/krzyzanowskim)
[Andreas Wörner (BSH)](https://github.com/awBSH/OpenSSL)
[Dr. Wolfram Schroers](https://nua-schroers.de)

