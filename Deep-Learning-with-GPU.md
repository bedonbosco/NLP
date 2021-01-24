# Deep Learning with GPU

Dependencies table

<table>
<tr>
  <th rowspan="2" colspan="2">Library</th>
  <th>CUDA</th>
</tr>
<tr>
  <th>11.0</th>
</tr>
<tr>
<th>Tensorflow</th>
<td>2.4.1</td>
<td>Driver>=450.36</td>
</tr>
</table>

## Tested Recipes

<table>
<tr>
  <th>ID</th>
  <th>Ubuntu</th>
  <th>Card</th>
  <th>Tensorflow</th>
  <th>NVIDIA Driver</th>
  <th>CUDA</th>
  <th>cuDNN</th>
</tr>
<tr>
  <td>1</td>
  <td>18.04</td>
  <td>GTX 1080Ti</td>
  <td>2.4.1</td>
  <td></td>
  <td></td>
  <td></td>
</tr>
</table>

## Recipe 1

TBD

## Appendix

**NVIDIA Driver**: NVIDIA Driver is the software driver for NVIDIA Graphics GPU installed on the PC. It is a program used to communicate from the Operating System to the device. This software is required in most cases for the hardware device to function properly

**CUDA**: CUDA® is a parallel computing platform and programming model developed by NVIDIA for general computing on graphical processing units (GPUs). With CUDA, developers are able to dramatically speed up computing applications by harnessing the power of GPUs.

**cuDNN**: The NVIDIA CUDA® Deep Neural Network library (cuDNN) is a GPU-accelerated library of primitives for deep neural networks. cuDNN provides highly tuned implementations for standard routines such as forward and backward convolution, pooling, normalization, and activation layers.

## References

* https://www.tensorflow.org/install/gpu#ubuntu_1804_cuda_110
* https://docs.nvidia.com/cuda/cuda-toolkit-release-notes/index.html#title-new-features

**Known Issue**

* [Documentation instructions on installing tensorflow with CUDA support doesn't work](https://github.com/tensorflow/tensorflow/issues/40278)
