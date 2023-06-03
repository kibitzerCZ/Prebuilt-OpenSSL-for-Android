## Prebuilt OpenSSL 1.1.1 for Android
- Created with build script by [xdien](https://github.com/xdien/build_openssl_android_clang)
- Built with NDK-r21e using configuration 
  ```
  ./Configure -D__ANDROID_API__=21 shared threads no-asm no-sse2 no-ssl2 no-ssl3 no-comp no-hw no-engine
  ```
- `armeabi-v7a`, `arm64-v8a`, `x86` and `x86_64` builds
