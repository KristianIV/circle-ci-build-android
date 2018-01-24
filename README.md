# Circle CI Android Build image with NDK
This repository is for building of a Docker image which can be used to perform builds in Circle CI
for Android projects which are using NDK

It is possible to specify the ndk_version as a build param.

```
docker build --build-arg ndk_version=r16b -t ashtonron/circle-ci-build-android .
```