## Prebuilt OpenSSL static & dynamic libraries for Android
- Created with build script by [xdien](https://github.com/xdien/build_openssl_android_clang)
- Built with NDK-r21e using configuration 
  ```
  ./Configure -D__ANDROID_API__=21 shared threads no-asm no-sse2 no-ssl2 no-ssl3 no-comp no-hw no-engine
  ```
- `armeabi-v7a`, `arm64-v8a`, `x86` and `x86_64` builds

Respective include (header) files are available on official OpenSSL [web](https://www.openssl.org/source) and [archive] (https://www.openssl.org/source/old/).

_This software is provided as is and with no warranty. Please test thoroughly before using in production._
