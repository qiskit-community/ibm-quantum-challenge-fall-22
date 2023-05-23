While the fall 2022 challenge is over, you can still run the Jupyter notebooks using one of these two options:

Option 1: Run the Jupyter notebooks in the IBM Quantum Lab:
===========================================================

1. Create an IBM quantum account on https://quantum-computing.ibm.com/ .
2. Go to the IBM quantum dashboard.
3. Click "Launch Lab".
4. Upload the [jupyter notebooks](content) from the github repository.
5. Open _lab1.ipynb_.
6. Insert a new cell at the top of the notebook and run this in it:
```
!pip install git+https://github.com/qiskit-community/Quantum-Challenge-Grader.git
```
7. Insert a new cell after the previous one and run this in it:
```
%env QC_GRADE_ONLY=true
```
8. Now you are ready to solve all exercises.

Option 2: Run the Jupyter notebooks on your local computer using Anaconda:
==========================================================================

**Note: You will still need to create an account on https://quantum-computing.ibm.com/  to run some of the cells that use IBM backends.**

1. Install Anaconda:

    https://www.anaconda.com/

2. Open an Anaconda prompt.

3. Create a new environment and activate it:
    ```
    conda create --name ibm-quantum-challenge-fall-22 python=3.8.12
    conda activate ibm-quantum-challenge-fall-22
    ```

4. Change into the directory containing [requirements.txt](requirements.txt):
    ```
    cd "ibm-quantum-challenge-fall-22"
    ```

5. Install requirements:
    ```
    pip install -r requirements.txt
    ```
    
6. Start Jupyter:
    ```
    jupyter notebook
    ```

7. Since the fall challenge is over, make sure you run the following in a new cell in the notebooks before running any other cells in order to be able to run the grader:
    ```
    %env QC_GRADE_ONLY=true
    ```
    
    If you had already run some cells, restart the kernel after running that command.
