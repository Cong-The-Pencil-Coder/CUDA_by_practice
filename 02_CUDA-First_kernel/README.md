02_CUDA-First_kernel
===================

Introduction
-------------
This is an introduction to learn CUDA. I used a lot of references to learn the basics about CUDA, all of them are included at the end. There is a pdf file that contains the basic theory to start programming in CUDA, as well as a source code to practice the theory explained and its solution.

-------------

Details
-------------

####List of files

> * **00_References.pdf** list of references used for the presentation.
> * **02_First kernel.pdf** theory to solve the practice.
> * **Source_code/01simple_kernel/01simple_kernel.cu**  example.
> * **Source_code/01simple_kernel/makefile**  to compile and to execute.
> * **Source_code/02simple_kernel2/01simple_kernel2.cu**  example.
> * **Source_code/02simple_kernel/makefile**  to compile and to execute..


####Description of the exercise

During the presentation, there are some examples and practices. For the examples, it is just necessary to do what is described in the **Running the scripts** section. For the practices, it is required to implement some sections of the code.

The **_P** and the **_S** in the scripts' name mean *practice* and *solution* respectively. Try to complete the practice and compare it with the solution at the end.

It is not mandatory to create the source code from scratch, the file contains certain sections that need to be completed. The following example shows a line with the sentence **// -:YOUR CODE HERE:- **. This indicates that you have to complete the code *just in that section* avoiding removing the other parts of the code.


```
//Do the add vector operation
int* add(int *a, int *b, int *result, int N){

	// -:YOUR CODE HERE:-
}
```

####Running the scripts


**NOTE**: All the codes have been tested in linux environments. A makefile is used to generate the execution file, you can see the makefile's description here [Wiki](http://en.wikipedia.org/wiki/Makefile) and here [GNU make](https://www.gnu.org/software/make/manual/make.html#Introduction).

```
// The '$' indicates the prompt in the command window in linux.

//1. Compile. 
$ make

//2. Execute. 
$make run

//3. Result.
./exe
Hello, World!
```

-------------

Installation of CUDA
-------------


>* [Windows](http://docs.nvidia.com/cuda/cuda-getting-started-guide-for-microsoft-windows/index.html)
>* [OS X](http://docs.nvidia.com/cuda/cuda-getting-started-guide-for-mac-os-x/index.html)
>* [Linux](http://docs.nvidia.com/cuda/cuda-getting-started-guide-for-linux/index.html)

-------------

References
-------------

####Books
>* **CUDA by Example: An Introduction to General-Purpose GPU Programming**. Jason Sanders, Edward Kandrot
>* **CUDA Application Design and Development**. Rob Farber
>* **CUDA Programming: A Developer's Guide to Parallel Computing with GPUs (Applications of GPU Computing Series)**. Shane Cook
>* **Programming Massively Parallel Processors, Second Edition: A Hands- on Approach**. David B. Kirk , Wen-mei W. Hwu

####Courses
>* [Udacity:](https://www.udacity.com/course/cs344) Introduction to Parallel Programming.
>* [Coursera:](https://www.coursera.org/course/hetero) Heterogeneous Parallel Programming

####Websites

>* [Dr. Dobbs: ](http://www.drdobbs.com/parallel/cuda-supercomputing-for-the-masses-part/207200659) CUDA, Supercomputing for the Masses.
>* [Livermore Computing:](https://computing.llnl.gov/?set=training&page=index) High performance computing training
>* [Parallel for all:](http://devblogs.nvidia.com/parallelforall/) Nvidia developer zone

-------------


> Written with [StackEdit](https://stackedit.io/).
