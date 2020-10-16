# Android-criu
To use criu on android platform.



By using docker-arm64/alpine image to build criu,and using patchelf to patch the criu.



### How to use

```bash
adb shell
cp -r criu /
chmod -R 777 criu
cd criu
./criu check
```

