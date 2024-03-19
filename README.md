# llama_cpp_python_android_whl
llama_cpp_python-0.2.56-0-cp312-cp312-android_23_arm64_v8a.whl built with chaquo/chaquopy build-wheel.py

### The entire process during the help thread can be found here, thanks mhsmith for the help.
https://github.com/chaquo/chaquopy/issues/1094

### Visit this link for full instructions
https://github.com/chaquo/chaquopy/tree/master/server/pypi

### Use the following command to build in the future
```./build-wheel.py --python 3.12 --abi arm64-v8a --api-level 23 packages/llama-cpp-python```

### Use this meta.yaml file
```
package:
  name: llama_cpp_python
  version: "0.2.56"

requirements:
  build:
    - cmake 3.21
  host:
    - python
```
