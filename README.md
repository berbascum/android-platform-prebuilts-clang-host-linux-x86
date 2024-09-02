# Toolchain LLVM - Clang prebuilts for host-x86 target-aarch64 

# Versions:

## Clang 11.0.2 r383902
- Branch: android11-qpr3-s1-release
## Clang 14 r450784
- Branch: llvm-r450784
## Clang 15 r458507 r468909b
- Branch: llvm-r487747 # Has no branch, found in clang-17 branch
## Clang 16 r475365b
- Branch: llvm-r487747 # Has no branch, found in clang-17 branch
## Clang 17 r487747
- Branch: llvm-r487747

# Clone the branch
- git clone [-b BRANCH_NAME]  https://android.googlesource.com/platform/prebuilts/clang/host/linux-x86
- cd linux-x86
- git checkout BRANCH_NAME
- Get the stable version clang-xxxxxxx dir from the llvm-binutils-stable dir symbolic links
- If want to push to github:
- Create a tar of any wanted clang-xxxxxxx dir

NOTE: For droidian, rename the dir to llvm-android-11.0-xxxxxxx before creating the archived file

## Configuration:
- PATH=/clang-xxxxxxx/bin:$PATH	



