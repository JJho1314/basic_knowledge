# Things to learn for new students in Lab611

## Software Programming

Learn the following two programing langrages

* C (C99)
* Python (v3.0)

Do the following projects to practice and learn good habits when programming in C

* [codewithc](https://www.codewithc.com/c-projects-with-source-code/)

Here's another good repo that has lots of good projects for you to practice.

* [Project-Based-Tutorials-in-C](https://github.com/rby90/Project-Based-Tutorials-in-C) (try 'Emulator 101', 'hash table', 'How to Write a Video Player in Less Than 1000 Lines')

Learn the following Good Coding Styles and use them in your research projects:

* [C���Ե��﷨����������д�淶ָ��](https://www.ctolib.com/topics-55863.html) ���򵥣�
* [NASA C coding style](http://mechatronics.me.wisc.edu/labresources/DataSheets/NASA-GSFC_C_Programming_Styles-94-003.pdf), NASA, 1994 ���Ƽ���
* [Recommended C Style and Coding Standards](https://www.maultech.com/chrislott/resources/cstyle/indhill-cstyle.pdf), UC Berkeley, 1997 ���򵥣�
* [Guidelines for the use of the C language in critical systems](http://caxapa.ru/thumbs/468328/misra-c-2004.pdf), MISRA, 2018 ���߼���
* [A list of C and C++ Style Guides](https://www.maultech.com/chrislott/resources/cstyle/)


## Hardware Basic Knowledge

Read the following two books to learn basic concepts for computer architecture. Important things to understand include pipeline, memory hierarchy, roofline model, Amdahl's law, ILP (instruction level parallelism), TLP (task level parallelism), DLP (data level parallelism), SIMD/VLIW processor

* [''Computer Organization and Design The Hardware Software Interface''](http://home.ustc.edu.cn/~louwenqi/reference_books_tools/Computer_Organization_and_Design_3Rd.pdf), 3rd Edition, 2004 ��������
* [''Computer Architecture A Quantitative Approach''](https://book.douban.com/subject/6795919/), 6th Edition, 2019 �����ף�

More reading:

* Loop-carried dependency: [1](https://www.cs.utexas.edu/~lin/cs380c/handout27.pdf), [2](https://people.engr.ncsu.edu/efg/506/s10/www/lectures/notes/lec5.pdf)


## FPGA Design

Read the following book to learn OpenCL programing (GPU/FPGA):

* ''OpenCL Programming Guide'', Aaftab Munshi, et.al., 2012  [also known as The Green Book]
* [''FPGA�칹���㡪������OpenCL�Ŀ�������''](https://baike.baidu.com/item/FPGA%E5%BC%82%E6%9E%84%E8%AE%A1%E7%AE%97%E2%80%94%E2%80%94%E5%9F%BA%E4%BA%8EOpenCL%E7%9A%84%E5%BC%80%E5%8F%91%E6%96%B9%E6%B3%95), ������ ��, 2015

Also, refers to Intel/Xilinx's OpenCL user guide to learn specific techniques that will be used in the project.

*  [''���� OpenCL ��Ӣ�ض� FPGA SDK ���ʵ��ָ��''](https://www.intel.cn/content/www/cn/zh/programmable/products/design-software/embedded-software-developers/opencl/support.html)

Finally, learn our opensource project [PipeCNN](https://github.com/doonny/PipeCNN). Run the examples, such as caffenet, vgg-16, resnet, YOLO on the DE10-nano and DE5-net platforms. Learn how to configure, compile, debug the source codes and profile the performance of the accelerator.

Zhang DeZheng has wrote a good study note on PipeCNN, please read it [here](https://github.com/doonny/basic_knowledge/blob/master/PipeCNN_note.md).

## GPU Design

Learn TensorRT and CUDA programing. Try examples on our TX2/TK1 platforms.

* [TensorRT](https://developer.nvidia.com/tensorrt)


## Tutorials for Hardware Architectures for DNN

Students who are working on hardware designs for deep neural networks should read the following tutorials.

* [Hardware Architectures for Deep Neural Networks](http://eyeriss.mit.edu/tutorial.html), MICRO Tutorial 2016.


## For Phd. Students

First, read the following artichles to learn how to write research papers.

* [''How to write a great research paper''](http://www.sohu.com/a/254967611_473283), Deep Learning Indaba, Stellenbosch, 2018
* [''How to Publish a Research Paper''](https://www.wikihow.com/Publish-a-Research-Paper), wikiHow, 2019
* [''How to Write a Good Scientific Paper''](https://spie.org/samples/9781510619142.pdf), Chris A. Mack, SPIE, 2018
* [''How to Write a Good Paper in Computer Science and How Will It Be Measured by ISI Web of Knowledge''](http://univagora.ro/jour/index.php/ijccc/article/view/2493), R?zvan Andonie, et.al., 2010

Secondly, read the following papers, which are really good examples in the related fields.

### FPGA accelerator design

* Optimizing FPGA-based Accelerator Design for Deep Convolutional Neural Networks, FPGA 2015.
* Throughput-Optimized OpenCL-based FPGA Accelerator for Large-Scale Convolutional Neural Networks, FPGA 2016.
* An OpenCL Deep Learning Accelerator on Arria 10, FPGA 2017.
* Improving the Performance of OpenCL-based FPGA Accelerator for Convolutional Neural Network, FPGA 2017.
* A Framework for Generating High Throughput CNN Implementations on FPGAs, FPGA 2018.
* An Efficient Hardware Accelerator for Sparse Convolutional Neural Networks on FPGAs, FCCM 2019.

The following survery papers are also worth reading.

* A Survey of FPGA Based Neural Network Accelerator, ACM TRETS 2017.
* Deep Neural Network Approximation for Custom Hardware: Where We��ve Been, Where We��re Going, ACM Computing Surveys 2019.

Our own research papers on FPGA accelerators:

* PipeCNN: An OpenCL-Based Open-Source FPGA Accelerator for Convolution Neural Networks, FPT 2017
* ABM-SpConv: A Novel Approach to FPGA-Based Acceleration of Convolutional Neural Network Inference, DAC 2019

### Neural network optimization (quantization, pruning, et.al.)

#### Quantization

* Ristretto: A Framework for Empirical Study of Resource-Efficient Inference in Convolutional Neural Networks, IEEE T-NNLS 2018.
* 8-bit Inference with TensorRT, Nvidia 2017.
* Quantizing deep convolutional networks for efficient inference: A whitepaper, Google, 2018.

A more complete list is [here](https://github.com/doonny/basic_knowledge/blob/master/quantization.md).

#### Pruning and Compression

A more complete list is [here](https://github.com/doonny/basic_knowledge/blob/master/pruning.md).


