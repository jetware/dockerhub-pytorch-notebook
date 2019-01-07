# PyTorch Notebook

A pre-configured and fully integrated minimal runtime environment with PyTorch, an open source software library for machine learning, Jupyter Notebook, a browser-based interactive notebook for programming, mathematics, and data science, and the Python programming language.

The stack is built in several variations with different hardware optimization features: OpenBLAS and Intel MKL for x86 CPU, and CUDA for NVidia GPU.

### Tagging policy

Tag format:

```
pytorch-notebook:<pytorch_version>-python<python_version>-<optimization>-<operating_system>
```

Versions available:

* PyTorch versions: **1.0.0**, 0.4.1, 0.3.1
* Python versions: **3.6.3**, 2.7.14
* Optimizations: **cpu**, cpu_mkl, cuda9, cuda10
* Operating systems: **alpine3.8**, ubuntu18.04, debian9, centos7

### Actual tags

#### `latest`

* Full tag alias: `1.0.0-python3.6.3-cpu-alpine3.8`
* Software: PyTorch 1.0.0, Python 3.6.3, Jupyter Notebook 1.0.0, Development preset 1 on Alpine 3.8
* Jetware appliance: [aise/pytorch1_python36_notebook-190103](https://jetware.io/appliances/aise/pytorch1_python36_notebook-190103?us=dockerhub)

#### `latest-ubuntu18.04`

* Full tag alias: `1.0.0-python3.6.3-cpu-ubuntu18.04`
* Software: PyTorch 1.0.0, Python 3.6.3, Jupyter Notebook 1.0.0, Development preset 1 on Ubuntu 18.04 LTS
* Jetware appliance: [aise/pytorch1_python36_notebook-190103](https://jetware.io/appliances/aise/pytorch1_python36_notebook-190103?us=dockerhub)

#### `latest-debian9`

* Full tag alias: `1.0.0-python3.6.3-cpu-debian9`
* Software: PyTorch 1.0.0, Python 3.6.3, Jupyter Notebook 1.0.0, Development preset 1 on Debian 9
* Jetware appliance: [aise/pytorch1_python36_notebook-190103](https://jetware.io/appliances/aise/pytorch1_python36_notebook-190103?us=dockerhub)

#### `latest-centos7`

* Full tag alias: `1.0.0-python3.6.3-cpu-centos7`
* Software: PyTorch 1.0.0, Python 3.6.3, Jupyter Notebook 1.0.0, Development preset 1 on CentOS 7
* Jetware appliance: [aise/pytorch1_python36_notebook-190103](https://jetware.io/appliances/aise/pytorch1_python36_notebook-190103?us=dockerhub)

#### `latest-cpu_mkl`

* Full tag alias: `1.0.0-python3.6.3-cpu_mkl2018.2.199-alpine3.8`
* Software: PyTorch 1.0.0, Python 3.6.3, Jupyter Notebook 1.0.0, Development preset 1 on Alpine 3.8
* Jetware appliance: [aise/pytorch1_python36_mkl_notebook-190103](https://jetware.io/appliances/aise/pytorch1_python36_mkl_notebook-190103?us=dockerhub)

#### `latest-cpu_mkl-ubuntu18.04`

* Full tag alias: `1.0.0-python3.6.3-cpu_mkl2018.2.199-ubuntu18.04`
* Software: PyTorch 1.0.0, Python 3.6.3, Jupyter Notebook 1.0.0, Development preset 1 on Ubuntu 18.04 LTS
* Jetware appliance: [aise/pytorch1_python36_mkl_notebook-190103](https://jetware.io/appliances/aise/pytorch1_python36_mkl_notebook-190103?us=dockerhub)

#### `latest-cpu_mkl-debian9`

* Full tag alias: `1.0.0-python3.6.3-cpu_mkl2018.2.199-debian9`
* Software: PyTorch 1.0.0, Python 3.6.3, Jupyter Notebook 1.0.0, Development preset 1 on Debian 9
* Jetware appliance: [aise/pytorch1_python36_mkl_notebook-190103](https://jetware.io/appliances/aise/pytorch1_python36_mkl_notebook-190103?us=dockerhub)

#### `latest-cpu_mkl-centos7`

* Full tag alias: `1.0.0-python3.6.3-cpu_mkl2018.2.199-centos7`
* Software: PyTorch 1.0.0, Python 3.6.3, Jupyter Notebook 1.0.0, Development preset 1 on CentOS 7
* Jetware appliance: [aise/pytorch1_python36_mkl_notebook-190103](https://jetware.io/appliances/aise/pytorch1_python36_mkl_notebook-190103?us=dockerhub)

#### `latest-python2`

* Full tag alias: `1.0.0-python2.7.14-cpu-alpine3.8`
* Software: PyTorch 1.0.0, Python 2.7.14, Jupyter Notebook 1.0.0, Development preset 1 on Alpine 3.8
* Jetware appliance: [aise/pytorch1_python27_notebook-190102](https://jetware.io/appliances/aise/pytorch1_python27_notebook-190102?us=dockerhub)

#### `latest-python2-ubuntu18.04`

* Full tag alias: `1.0.0-python2.7.14-cpu-ubuntu18.04`
* Software: PyTorch 1.0.0, Python 2.7.14, Jupyter Notebook 1.0.0, Development preset 1 on Ubuntu 18.04 LTS
* Jetware appliance: [aise/pytorch1_python27_notebook-190102](https://jetware.io/appliances/aise/pytorch1_python27_notebook-190102?us=dockerhub)

#### `latest-python2-debian9`

* Full tag alias: `1.0.0-python2.7.14-cpu-debian9`
* Software: PyTorch 1.0.0, Python 2.7.14, Jupyter Notebook 1.0.0, Development preset 1 on Debian 9
* Jetware appliance: [aise/pytorch1_python27_notebook-190102](https://jetware.io/appliances/aise/pytorch1_python27_notebook-190102?us=dockerhub)

#### `latest-python2-centos7`

* Full tag alias: `1.0.0-python2.7.14-cpu-centos7`
* Software: PyTorch 1.0.0, Python 2.7.14, Jupyter Notebook 1.0.0, Development preset 1 on CentOS 7
* Jetware appliance: [aise/pytorch1_python27_notebook-190102](https://jetware.io/appliances/aise/pytorch1_python27_notebook-190102?us=dockerhub)

#### `latest-python2-cpu_mkl`

* Full tag alias: `1.0.0-python2.7.14-cpu_mkl2018.2.199-alpine3.8`
* Software: PyTorch 1.0.0, Python 2.7.14, Jupyter Notebook 1.0.0, Development preset 1 on Alpine 3.8
* Jetware appliance: [aise/pytorch1_python27_mkl_notebook-190102](https://jetware.io/appliances/aise/pytorch1_python27_mkl_notebook-190102?us=dockerhub)

#### `latest-python2-cpu_mkl-ubuntu18.04`

* Full tag alias: `1.0.0-python2.7.14-cpu_mkl2018.2.199-ubuntu18.04`
* Software: PyTorch 1.0.0, Python 2.7.14, Jupyter Notebook 1.0.0, Development preset 1 on Ubuntu 18.04 LTS
* Jetware appliance: [aise/pytorch1_python27_mkl_notebook-190102](https://jetware.io/appliances/aise/pytorch1_python27_mkl_notebook-190102?us=dockerhub)

#### `latest-python2-cpu_mkl-debian9`

* Full tag alias: `1.0.0-python2.7.14-cpu_mkl2018.2.199-debian9`
* Software: PyTorch 1.0.0, Python 2.7.14, Jupyter Notebook 1.0.0, Development preset 1 on Debian 9
* Jetware appliance: [aise/pytorch1_python27_mkl_notebook-190102](https://jetware.io/appliances/aise/pytorch1_python27_mkl_notebook-190102?us=dockerhub)

#### `latest-python2-cpu_mkl-centos7`

* Full tag alias: `1.0.0-python2.7.14-cpu_mkl2018.2.199-centos7`
* Software: PyTorch 1.0.0, Python 2.7.14, Jupyter Notebook 1.0.0, Development preset 1 on CentOS 7
* Jetware appliance: [aise/pytorch1_python27_mkl_notebook-190102](https://jetware.io/appliances/aise/pytorch1_python27_mkl_notebook-190102?us=dockerhub)

#### `0-ubuntu18.04`

* Full tag alias: `0.4.1-python3.6.3-cpu-ubuntu18.04`
* Software: PyTorch 0.4.1, Python 3.6.3, Jupyter Notebook 1.0.0, Development preset 1 on Ubuntu 18.04 LTS
* Jetware appliance: [aise/pytorch04_python36_notebook-190103](https://jetware.io/appliances/aise/pytorch04_python36_notebook-190103?us=dockerhub)

#### `0-debian9`

* Full tag alias: `0.4.1-python3.6.3-cpu-debian9`
* Software: PyTorch 0.4.1, Python 3.6.3, Jupyter Notebook 1.0.0, Development preset 1 on Debian 9
* Jetware appliance: [aise/pytorch04_python36_notebook-190103](https://jetware.io/appliances/aise/pytorch04_python36_notebook-190103?us=dockerhub)

#### `0-centos7`

* Full tag alias: `0.4.1-python3.6.3-cpu-centos7`
* Software: PyTorch 0.4.1, Python 3.6.3, Jupyter Notebook 1.0.0, Development preset 1 on CentOS 7
* Jetware appliance: [aise/pytorch04_python36_notebook-190103](https://jetware.io/appliances/aise/pytorch04_python36_notebook-190103?us=dockerhub)

#### `0-cpu_mkl`

* Full tag alias: `0.4.1-python3.6.3-cpu_mkl2018.2.199-alpine3.8`
* Software: PyTorch 0.4.1, Python 3.6.3, Jupyter Notebook 1.0.0, Development preset 1 on Alpine 3.8
* Jetware appliance: [aise/pytorch04_python36_mkl_notebook-190103](https://jetware.io/appliances/aise/pytorch04_python36_mkl_notebook-190103?us=dockerhub)

#### `0-cpu_mkl-ubuntu18.04`

* Full tag alias: `0.4.1-python3.6.3-cpu_mkl2018.2.199-ubuntu18.04`
* Software: PyTorch 0.4.1, Python 3.6.3, Jupyter Notebook 1.0.0, Development preset 1 on Ubuntu 18.04 LTS
* Jetware appliance: [aise/pytorch04_python36_mkl_notebook-190103](https://jetware.io/appliances/aise/pytorch04_python36_mkl_notebook-190103?us=dockerhub)

#### `0-cpu_mkl-debian9`

* Full tag alias: `0.4.1-python3.6.3-cpu_mkl2018.2.199-debian9`
* Software: PyTorch 0.4.1, Python 3.6.3, Jupyter Notebook 1.0.0, Development preset 1 on Debian 9
* Jetware appliance: [aise/pytorch04_python36_mkl_notebook-190103](https://jetware.io/appliances/aise/pytorch04_python36_mkl_notebook-190103?us=dockerhub)

#### `0-cpu_mkl-centos7`

* Full tag alias: `0.4.1-python3.6.3-cpu_mkl2018.2.199-centos7`
* Software: PyTorch 0.4.1, Python 3.6.3, Jupyter Notebook 1.0.0, Development preset 1 on CentOS 7
* Jetware appliance: [aise/pytorch04_python36_mkl_notebook-190103](https://jetware.io/appliances/aise/pytorch04_python36_mkl_notebook-190103?us=dockerhub)

#### `0-python2`

* Full tag alias: `0.4.1-python2.7.14-cpu-alpine3.8`
* Software: PyTorch 0.4.1, Python 2.7.14, Jupyter Notebook 1.0.0, Development preset 1 on Alpine 3.8
* Jetware appliance: [aise/pytorch04_python27_notebook-190103](https://jetware.io/appliances/aise/pytorch04_python27_notebook-190103?us=dockerhub)

#### `0-python2-ubuntu18.04`

* Full tag alias: `0.4.1-python2.7.14-cpu-ubuntu18.04`
* Software: PyTorch 0.4.1, Python 2.7.14, Jupyter Notebook 1.0.0, Development preset 1 on Ubuntu 18.04 LTS
* Jetware appliance: [aise/pytorch04_python27_notebook-190103](https://jetware.io/appliances/aise/pytorch04_python27_notebook-190103?us=dockerhub)

#### `0-python2-debian9`

* Full tag alias: `0.4.1-python2.7.14-cpu-debian9`
* Software: PyTorch 0.4.1, Python 2.7.14, Jupyter Notebook 1.0.0, Development preset 1 on Debian 9
* Jetware appliance: [aise/pytorch04_python27_notebook-190103](https://jetware.io/appliances/aise/pytorch04_python27_notebook-190103?us=dockerhub)

#### `0-python2-centos7`

* Full tag alias: `0.4.1-python2.7.14-cpu-centos7`
* Software: PyTorch 0.4.1, Python 2.7.14, Jupyter Notebook 1.0.0, Development preset 1 on CentOS 7
* Jetware appliance: [aise/pytorch04_python27_notebook-190103](https://jetware.io/appliances/aise/pytorch04_python27_notebook-190103?us=dockerhub)

#### `0.3`

* Full tag alias: `0.3.1-python3.6.3-cpu-alpine3.8`
* Software: PyTorch 0.3.1, Python 3.6.3, Jupyter Notebook 1.0.0, Development preset 1 on Alpine 3.8
* Jetware appliance: [aise/pytorch03_python36_notebook-190103](https://jetware.io/appliances/aise/pytorch03_python36_notebook-190103?us=dockerhub)

#### `0.3-ubuntu18.04`

* Full tag alias: `0.3.1-python3.6.3-cpu-ubuntu18.04`
* Software: PyTorch 0.3.1, Python 3.6.3, Jupyter Notebook 1.0.0, Development preset 1 on Ubuntu 18.04 LTS
* Jetware appliance: [aise/pytorch03_python36_notebook-190103](https://jetware.io/appliances/aise/pytorch03_python36_notebook-190103?us=dockerhub)

#### `0.3-debian9`

* Full tag alias: `0.3.1-python3.6.3-cpu-debian9`
* Software: PyTorch 0.3.1, Python 3.6.3, Jupyter Notebook 1.0.0, Development preset 1 on Debian 9
* Jetware appliance: [aise/pytorch03_python36_notebook-190103](https://jetware.io/appliances/aise/pytorch03_python36_notebook-190103?us=dockerhub)

#### `0.3-centos7`

* Full tag alias: `0.3.1-python3.6.3-cpu-centos7`
* Software: PyTorch 0.3.1, Python 3.6.3, Jupyter Notebook 1.0.0, Development preset 1 on CentOS 7
* Jetware appliance: [aise/pytorch03_python36_notebook-190103](https://jetware.io/appliances/aise/pytorch03_python36_notebook-190103?us=dockerhub)

#### `0-python2-cpu_mkl`

* Full tag alias: `0.4.1-python2.7.14-cpu_mkl2018.2.199-alpine3.8`
* Software: PyTorch 0.4.1, Python 2.7.14, Jupyter Notebook 1.0.0, Development preset 1 on Alpine 3.8
* Jetware appliance: [aise/pytorch04_python27_mkl_notebook-190103](https://jetware.io/appliances/aise/pytorch04_python27_mkl_notebook-190103?us=dockerhub)

#### `0-python2-cpu_mkl-ubuntu18.04`

* Full tag alias: `0.4.1-python2.7.14-cpu_mkl2018.2.199-ubuntu18.04`
* Software: PyTorch 0.4.1, Python 2.7.14, Jupyter Notebook 1.0.0, Development preset 1 on Ubuntu 18.04 LTS
* Jetware appliance: [aise/pytorch04_python27_mkl_notebook-190103](https://jetware.io/appliances/aise/pytorch04_python27_mkl_notebook-190103?us=dockerhub)

#### `0-python2-cpu_mkl-debian9`

* Full tag alias: `0.4.1-python2.7.14-cpu_mkl2018.2.199-debian9`
* Software: PyTorch 0.4.1, Python 2.7.14, Jupyter Notebook 1.0.0, Development preset 1 on Debian 9
* Jetware appliance: [aise/pytorch04_python27_mkl_notebook-190103](https://jetware.io/appliances/aise/pytorch04_python27_mkl_notebook-190103?us=dockerhub)

#### `0-python2-cpu_mkl-centos7`

* Full tag alias: `0.4.1-python2.7.14-cpu_mkl2018.2.199-centos7`
* Software: PyTorch 0.4.1, Python 2.7.14, Jupyter Notebook 1.0.0, Development preset 1 on CentOS 7
* Jetware appliance: [aise/pytorch04_python27_mkl_notebook-190103](https://jetware.io/appliances/aise/pytorch04_python27_mkl_notebook-190103?us=dockerhub)

#### `0.3-python2`

* Full tag alias: `0.3.1-python2.7.14-cpu-alpine3.8`
* Software: PyTorch 0.3.1, Python 2.7.14, Jupyter Notebook 1.0.0, Development preset 1 on Alpine 3.8
* Jetware appliance: [aise/pytorch03_python27_notebook-190103](https://jetware.io/appliances/aise/pytorch03_python27_notebook-190103?us=dockerhub)

#### `0.3-python2-ubuntu18.04`

* Full tag alias: `0.3.1-python2.7.14-cpu-ubuntu18.04`
* Software: PyTorch 0.3.1, Python 2.7.14, Jupyter Notebook 1.0.0, Development preset 1 on Ubuntu 18.04 LTS
* Jetware appliance: [aise/pytorch03_python27_notebook-190103](https://jetware.io/appliances/aise/pytorch03_python27_notebook-190103?us=dockerhub)

#### `0.3-python2-debian9`

* Full tag alias: `0.3.1-python2.7.14-cpu-debian9`
* Software: PyTorch 0.3.1, Python 2.7.14, Jupyter Notebook 1.0.0, Development preset 1 on Debian 9
* Jetware appliance: [aise/pytorch03_python27_notebook-190103](https://jetware.io/appliances/aise/pytorch03_python27_notebook-190103?us=dockerhub)

#### `0.3-python2-centos7`

* Full tag alias: `0.3.1-python2.7.14-cpu-centos7`
* Software: PyTorch 0.3.1, Python 2.7.14, Jupyter Notebook 1.0.0, Development preset 1 on CentOS 7
* Jetware appliance: [aise/pytorch03_python27_notebook-190103](https://jetware.io/appliances/aise/pytorch03_python27_notebook-190103?us=dockerhub)


### Issues

If you encountered a problem running this container, please file an [issue](https://github.com/jetware/dockerhub-pytorch-notebook/issues).

---
(c) 2019 [Jetware](https://jetware.io)
