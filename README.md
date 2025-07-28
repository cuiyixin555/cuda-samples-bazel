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
$ bazel build //basic/...
$ bazel build //basic_macros/...
$ bazel build //cublas/...
$ bazel build //if_cuda/...
$ bazel build //nccl/...
$ bazel build //rdc/...
$ bazel build //thrust/...
$ bazel build //UnifiedMemoryStreams/...
```

And you can get the binary file in the folder
```bash
$ ./bazel-bin/basic/main
$ ./bazel-bin/basic_macros/main
$ ./bazel-bin/cublas/main
$ ./bazel-bin/if_cuda/main
$ ./bazel-bin/nccl/main
$ ./bazel-bin/rdc/main
$ ./bazel-bin/thrust/main
$ ./bazel-bin/UnifiedMemoryStreams/main
```
