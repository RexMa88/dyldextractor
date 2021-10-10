# dyldextractor
dyld的extractor(提取器)，可以提取dyld_shared_cache_arm*中的各种库

## 用法

建议先了解一下[动态共享缓存](https://www.jianshu.com/p/18c8d02e41dd)

获取到dyld_shared_cache之后，就可以用dyld_extractor提取缓存中的各种库了，用法和脚本语言一样