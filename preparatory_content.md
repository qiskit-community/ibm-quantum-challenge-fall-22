# Preparatory Study Resources

In preparation for the challenge, you should make yourself familiar with the foundational content necessary to understand and complete the four challenges and associated exercises. 

## Introduction to Quantum Computing

If you are new to quantum computing, please watch this YouTube video:
- [Understanding Quantum Information and Computation | Lesson 1](https://youtu.be/3-c4xJa7Flk)

## Linear Algebra

Most quantum computing algorithms require an understanding of linear algebra to formulate the problem. However, you need not be an expert on the topic to complete the IBM Quantum Challenge Fall 2022. Here are  the resource that can help you learn or brush-up on the foundations of linear algebra and matrices.


- [Qiskit Textbook: Linear Algebra Chapter](https://qiskit.org/textbook/ch-appendix/linear_algebra.html)

## Python Crash Course

Qiskit, and thus the challenge, is implemented in Python. If you’re not familiar with Python, you can learn how the basics from the Qiskit Textbook chapter on [Python and Jupyter Notebooks](https://learn.qiskit.org/course/ch-prerequisites/introduction-to-python-and-jupyter-notebooks). Jupyter notebooks are an interactive way to program and are the most common method for communicating Qiskit work. All exercises for the challenge are provided as Jupyter Notebooks on the IBM Quantum platform. To access the platform, you should create an account using the links provided in the section below.

## Qiskit Runtime
This blog post from the Qiskit offers a simple overview of what Qiskit Runtime is and why it’s so important:
- [So What is Qiskit Runtime, Anyway?](https://medium.com/qiskit/so-what-is-qiskit-runtime-anyway-c78aecf3742)

This video is also good for the overview:
- [What are Quantum Primitives?](https://youtu.be/kyLi8Gswpxo)

## Error Mitigation

Here is a layperson introduction to quantum noise:
- [How I Use Quantum Computing to Create Bubble Art: A creative visualization of quantum noise](https://medium.com/qiskit/how-i-use-quantum-computing-to-create-bubble-art-d6c01f3ec2e)

The following short videos on Qiskit YouTube channel are a great introduction to error mitigation:
- [Nick Knows - Pauli Twirling](https://youtu.be/4MLHvmmpSQ8)
- [Nick Knows - Measurement Errors](https://youtu.be/9ZSBkH-2zjs)
- [Nick Knows - Dynamical Decoupling](https://youtu.be/67jRWQuW3Fk)

Below is for those who want to learn more.
- [What’s the difference between error suppression, error mitigation, and error correction?](https://research.ibm.com/blog/quantum-error-suppression-mitigation-correction)
- [With fault tolerance the ultimate goal, error mitigation is the path that gets quantum computing to usefulness](https://research.ibm.com/blog/gammabar-for-quantum-advantage)
- Qiskit Global Summer School 2021 - [Noise in Quantum Computers (part 1)](https://learn.qiskit.org/summer-school/2021/lec3-1-noise-quantum-computers-1)
- Qiskit Global Summer School 2021 - [Noise in Quantum Computers (part 2)](https://learn.qiskit.org/summer-school/2021/lec3-2-noise-quantum-computers-pt-2)

## IBM Quantum Account

Make sure you have registered on the [IBM Quantum platform](https://challenges.quantum-computing.ibm.com/fall-2022) as it hosts the challenge notebooks and exercises. You can register an account [here](https://auth.quantum-computing.ibm.com/auth/idaas?redirectTo=https%3A%2F%2Fquantum-computing.ibm.com%2F). You will be using the IBM Quantum Lab, which hosts Jupyter Notebooks for you. If you are not familiar with Jupyter or the IBM Quantum Lab, you can read the [Quantum Lab Guide](https://quantum-computing.ibm.com/lab/docs/iql/#qlab) for more information on how it is structured and what features are available.

## Working on the Challenges locally

If you struggle to maintain a stable internet connection to the IBM Quantum Challenge platform, you can download the notebooks from this repo. Note that the challenge notebooks will only be available from the start of the challenge (11 November @ 9:00 EDT).

For a guide on setting up Qiskit on your own computer, have a look at the ['Getting Started'](https://qiskit.org/documentation/getting_started.html) page in the Qiskit documentation. When you install Qiskit using pip, make sure you run the following command instead of that provided by the Qiskit documentation. This will make sure you have the correct dependencies.

```bash
pip install qiskit[all]
```
