Prebuilts for Clang/LLVM-based tools used in Android
====================================================

For the latest version of this doc, please make sure to visit:
[Android Clang/LLVM-based Tools Readme Doc](https://android.googlesource.com/platform/prebuilts/clang-tools/+/mirror-goog-main-prebuilts/README.md)

Build Instructions
------------------

For Googlers, check out go/repo-init/main-clang-tools and run:

```
$ OUT_DIR=out prebuilts/clang-tools/build-prebuilts.sh
```

Update Prebuilts
----------------

From a `main` tree or a `main-clang-tools` tree run:

```
$ prebuilts/clang-tools/update-prebuilts.sh \
    <build-id from go/ab/git_main-clang-tools>
```
