# CUDA Samples Bazel Build
This is CUDA Samples with Bazel Build

# Reference source code is following as
```bash
https://github.com/NVIDIA/cuda-samples
https://github.com/bazel-contrib/rules_cuda
```

# Update the CUDA rules for [Bazel](https://bazel.build)

This repository contains [Starlark](https://github.com/bazelbuild/starlark) implementation of CUDA rules in Bazel.

These rules provide some macros and rules that make it easier to build CUDA with Bazel.

## Getting Started
You can open the directory demos to test some UT for fun

```bash
$ cd ./demos
$ bazel build //0_practice/basic/...
$ bazel build //0_practice/basic_macros/...
$ bazel build //0_practice/cublas/...
$ bazel build //0_practice/if_cuda/...
$ bazel build //0_practice/nccl/...
$ bazel build //0_practice/rdc/...
$ bazel build //0_practice/thrust/...
$ bazel build //1_introduction/UnifiedMemoryStreams/...
```

And you can get the binary file in the folder
```bash
$ ./bazel-bin/0_practice/basic/main
$ ./bazel-bin/0_practice/basic_macros/main
$ ./bazel-bin/0_practice/cublas/main
$ ./bazel-bin/0_practice/if_cuda/main
$ ./bazel-bin/0_practice/nccl/main
$ ./bazel-bin/0_practice/rdc/main
$ ./bazel-bin/0_practice/thrust/main
$ ./bazel-bin/1_introduction/UnifiedMemoryStreams/main
```
