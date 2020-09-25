# Promotion Program on Quantum Computing Science and Technology
The IBM Quantum Computer Hub at National Taiwan University holds a series of promotion courses nationwide. Yun-Chih Liao is one of the lecturers in the hub. This repository contains the slides, demonstrations, and related reference materials of the courses.
In the courses, we give demos by Qiskit, an online platform helping you execute quantum programs with simulators and real quantum proccessors. Before doing the so, you need to make sure that 
1. you have applied an [IBM Quantum Experience](https://quantum-computing.ibm.com/) account
2. you have a Python (3.5 or later) platform in your computer
3. you have insalled Qiskit package
For the installation, please visit [here](https://github.com/ycldingo/IBMQ/blob/master/README.md). 

Qiskit upgrade their packages and relevant environment frequently. Please verify your version before programming with 
```python
## Check qiskit version
from qiskit import version
version._get_qiskit_versions()
```
If you would like to upgrade Qiskit, run
```python
pip install --upgrade qiskit
```
in terminal under the environment you install qiskit.

## Normal Lectures 
These short lectures are given for audience in various background, such as the feshman, college students majoring in Finance, students in Physics department, or those from industries and engineering people.

### National Chunghua University of Education (NCUE) - April 13, 2020
The audience of the lecture are undergraduate students in Department of Physics.
- Lecture 1: Let's Talk in Quantum
- Lecture 2: Quantum Algorithmns & Programming

### National Tsing Hua University (NTHU) - May 02, 2020
An virtual seminar is given to Department of Electrical Engineering.
- Lecture: Step into Quantum

### Tamkang University (TKU) - May 14, 2020
We are invited to Department of Finance to give a brief introduction to quantum computing and possible application on finance.
- Lecture 1: How to Quantum?
  - Demo: Pricing Options (reference: [Qiskit Finance](https://github.com/Qiskit/qiskit-tutorials/blob/4e76af1f26af57f3a1112318e5c611c52cf960de/qiskit/advanced/aqua/finance/simulation/european_call_option_pricing.ipynb))
    1. [Load distribution](https://github.com/ycldingo/QuantumComputer_tw/blob/master/demo/LoadDistribution.ipynb)
    2. [Option Pricing](https://github.com/ycldingo/QuantumComputer_tw/blob/master/demo/OptionPricing_butterfly.ipynb)
- Lecture 2: Quantum V.S. Programming

### National Chung Cheng University (CCU) - September 25, 2020
The audience are mostly college and graduate students from physics, computer science, electrical engineering background.
- Lecture 1: [Quantum, Quantum, Quantum](https://github.com/ycldingo/QuantumComputer_tw/blob/master/slides/CCU092520-QuantumQuantumQuantum.pdf)
- Lecture 2: [Introduction to Quantum Programming](https://github.com/ycldingo/QuantumComputer_tw/blob/master/slides/CCU092520-IntorductionToQuantumProgramming.pdf)
- [Quiz](https://forms.gle/kUZdNFa4N5WY7PjH8): The quiz covers the content of the lectures.

## Quantum Computing Workshop
### Joint Workshop with Gogoro Network - April 27, 2020
A joint symposium, focusing on quantum computing and the possible industrial applications, was held with Gogoro Network team together. We demostrate quantum random walks and maxcut problem with QAOA and VQE.
- Presentation 1: [Step into Quantum](https://github.com/ycldingo/QuantumComputer_tw/blob/master/slides/Step%20into%20Quantum.pdf) (some content are also presented in an online seminar in NTHU)
- Presentation 2: [First Quantum Programming](https://github.com/ycldingo/QuantumComputer_tw/blob/master/slides/First%20Quantum%20Programming.pdf)
- Presentation 3: [Variational Quantum Eigensolver](https://github.com/ycldingo/QuantumComputer_tw/blob/master/slides/Variational%20Quantum%20Eigensolver.pdf)

### National Taiwan University (NTU) - June 30, 2020
This is a worskop open for folks. The participants come from various background, finance, material engineering, physics, computer science, electric engineering, chemistry engineering, etc. 
- Morning - Introduction
  - Lecture 1: [Quantum Computing?](https://github.com/ycldingo/QuantumComputer_tw/blob/master/slides/063020-QuantumComputing.pdf)
  - Lecture 2: Quantum Programming
- Afternoon - Demonstrations
  - Lecture 1: [Quantum Random Walks](https://github.com/ycldingo/QuantumComputer_tw/blob/master/slides/063020-QuantumRandomWalks.pdf)
  - Lecture 2: Varioanl Quantum Eigensolver


## 2020 Quantum Computing Summer School
A three-day summer school on Quantum computing and programming was held on August 4 to August 6 in 2020 in National Taiwan University. The content including schedule, lecture slides, and demo files are [here](https://github.com/ycldingo/QuantumComputing_2020Summer).

## Open House - September 19, 2020
An open house was held in National Taiwan University (NTU), which is mainly for the high school students. The event is supervised by MOST (Ministry of Science and Technology) Taiwan.
- Lecture 1: [Overview on Quantum Computing](https://github.com/ycldingo/QuantumComputer_tw/blob/master/slides/OpenHouse091920-overview.pdf)
- Lecture 2: [Introduction to Quantum Computing](https://github.com/ycldingo/QuantumComputer_tw/blob/master/slides/OpenHouse091920-introduction.pdf)
- [Take-home exercise](https://github.com/ycldingo/QuantumComputer_tw/tree/master/exercise)

## Others
Here, we also post some [basic introduction to quantum computing](https://github.com/ycldingo/QuantumComputer_tw/blob/master/QA_QuantumComputer.ipynb). Some of the contents is in Chinese since the reader is set to be the folk in Taiwan.


## Reference
Some of the content are from online resource. We do not own the copyright.
- [Qiskit](https://qiskit.org/)
  - [GitHub](https://github.com/Qiskit)
    - [Tutorial](https://github.com/Qiskit/qiskit-tutorials)
  - [Textbook](https://qiskit.org/textbook/preface.html)
  - [Document](https://qiskit.org/documentation/)
  - [2020 Global Summer School](https://qiskit.org/events/summer-school/)
- [Microsoft Quantum Document](https://docs.microsoft.com/en-us/quantum/)
