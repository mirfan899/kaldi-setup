### Kaldi-setup
Necessary package required for Kaldi ASR setup.

### Install CUDA 9.0
run the script `install_cudnn_9.0` and then edit your `.bashrc` file and add the following lines
```textmate
export PATH=/usr/local/cuda-9.0/bin${PATH:+:${PATH}}
export LD_LIBRARY_PATH=/usr/local/cuda-9.0/lib64${LD_LIBRARY_PATH:+:${LD_LIBRARY_PATH}}
```
Now check the `CUDNN` version by following command
```shell
cat /usr/include/cudnn.h | grep CUDNN_MAJOR -A 2
```