# Frequently Asked Questions
## General
#### How do I submit an answer?

Within each exercise notebook, on the [challenge portal](https://challenges.quantum-computing.ibm.com/fall-2022), you will find guidelines to submit an answer. For example in the Lab 1 notebook, for Exercise 1:

```python
# Submit your answer using following code
from qc_grader.challenges.fall_2022 import grade_lab1_ex1

grade_lab1_ex1(lab1_ex1_job)
```

#### Can I run the challenge notebooks on a local computer?

Yes it is possible. But we strongly recommend you solve the exercises on the [challenge portal](https://challenges.quantum-computing.ibm.com/fall-2022). If you really want to run the exercises locally, you can download the notebooks from the [challenge repository](https://github.com/qiskit-community/ibm-quantum-challenge-fall-22) and run using Jupyter notebook.

#### Can we check answers on a local computer?

Yes it is possible. But similar to the above question, we strongly recommend you solve the exercises and check answers on the [challenge portal](https://challenges.quantum-computing.ibm.com/fall-2022). If you really want to check answers on a local computer, you need to install the [grading client](https://github.com/qiskit-community/Quantum-Challenge-Grader) in addition to downloading the notebooks.

#### Do we need to download the notebooks from github?

No, you can run all exercises on the [challenge portal](https://challenges.quantum-computing.ibm.com/fall-2022) itself.

#### Do I need to take the exercises in order?

We encourage you complete the exercises in the given order as this is the intended structure for the challenge. However, you may take the exercises in any order.

#### Do I need an IBMid associated with my IBM Quantum Account?

Yes, you'll need an IBMid associated with your IBM Quantum account in order to complete some of the challenges. If you don't already have one, please [register a new IBMid](https://auth.quantum-computing.ibm.com/auth/idaas) using the SAME email address associated with your IBM Quantum account. If you have any questions or face any issues, please let us know in the [#challenge-fall-2022](https://qiskit.slack.com/archives/C0466L7D5CG) Slack channel.

#### I encountered “Server error”. What should I do?

We have a lot of participants at the moment. Please be patient, wait and try again.

#### I encountered this error `401 : Unauthorized You are not Authenticated to do this (1)` What should I do?

Please try the following on a notebook on Quantum Lab?
```python
import os
os.environ['QXToken'] = 'your token'
print(os.getenv('QXToken'))
```
You can find your token here: https://quantum-computing.ibm.com/account. Make sure the output matches the token you copied from the account page.

Run the code below to check if authentication is working. If you see a long string in the output, it means 401 error has been resolved.

```python
from qc_grader.api import get_access_token
get_access_token()
```

#### Will I receive a badge and what are the qualifications?
You will receive the IBM Quantum Challenge Fall 2022 Achievement digital badge for participating in the IBM Quantum Challenge Fall 2022 and successfully completing all four of the challenges by the deadline of 18 Nov, 9:00 AM (EDT). More details will be shared once the challenge has completed. 

#### Still have more questions?

Please let us know if you have any additional questions in the [#challenge-fall-2022](https://qiskit.slack.com/archives/C0466L7D5CG) in the [Qiskit Slack](https://ibm.co/joinqiskitslack) workspace. 
