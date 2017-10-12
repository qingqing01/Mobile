# Mobile

Here mainly describes how to deploy PaddlePaddle to the mobile end, as well as some deployment optimization methods and some benchmark.

## How to build PaddlePaddle for mobile
- [Build PaddlePaddle for Android](https://github.com/PaddlePaddle/Paddle/blob/develop/doc/howto/cross_compiling/cross_compiling_for_android_cn.md)
- Build PaddlePaddle for IOS
- [Build PaddlePaddle for Raspberry Pi3](https://github.com/PaddlePaddle/Paddle/blob/develop/doc/howto/cross_compiling/cross_compiling_for_raspberry_cn.md)
- Build PaddlePaddle for PX2

## Deployment optimization methods
- [Merge batch normalization before deploying the model to the mobile.](./tool/merge_batch_normalization/README.md)
- [Compress the model before deploying the model to the mobile.](./tool/rounding/README.md)
- Merge multiple model parameter files into one file.

## Model compression
- [Pruning](./model_compression/flowers102/README.md)

## PaddlePaddle mobile benchmark
- [Mobilenet](./benchmark/README.md)
- ENet
