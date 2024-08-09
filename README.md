# QML-for-Conspicuity-Detection-in-Production
Womanium Quantum+AI 2024 Projects

**Please review the participation guidelines [here](https://github.com/womanium-quantum/Quantum-AI-2024) before starting the project.**

_**Do NOT delete/ edit the format of this read.me file.**_

_**Include all necessary information only as per the given format.**_

## Project Information:

### Team Size:
  - Maximum team size = 2
  - While individual participation is also welcome, we highly recommend team participation :)

### Eligibility:
  - All nationalities, genders, and age groups are welcome to participate in the projects.
  - All team participants must be enrolled in Womanium Quantum+AI 2024.
  - Everyone is eligible to participate in this project and win Womanium grants.
  - All successful project submissions earn the Womanium Project Certificate.
  - Best participants win Womanium QSL fellowships with Fraunhofer ITWM. Please review the eligibility criteria for QSL fellowships in the project description below.

### Project Description:
  - Click [here](https://drive.google.com/file/d/1AcctFeXjchtEhYzPUsHpP_b4HGlI4kq9/view?usp=sharing) to view the project description.
  - YouTube recording of the project description - [link](https://youtu.be/Ac1ihFcTRTc?si=i6AIVfQQh8ymYQYp)

## Project Submission:
All information in this section will be considered for project submission and judging.

Ensure your repository is public and submitted by **August 9, 2024, 23:59pm US ET**.

Ensure your repository does not contain any personal or team tokens/access information to access backends. Ensure your repository does not contain any third-party intellectual property (logos, company names, copied literature, or code). Any resources used must be open source or appropriately referenced.

### Team Information:
Team Member 1:
 - Full Name: Marzieh Bathaee
 - Womanium Program Enrollment ID (see Welcome Email, format- WQ24-xxxxxxxxxxxxxxx):WQ24-xxxxxxxxxxxxxxx


Team Member 2:
 - Full Name: KRISHANG GUPTA
 - Womanium Program Enrollment ID (see Welcome Email, format- WQ24-xxxxxxxxxxxxxxx):WQ24-eoDA9GwbezQsby6


### Project Solution:
_Include a comprehensive summary of all important information about your project solution here._
All necessary code files and any additional information required to judge your project solution should be included in the repository. 

After warming up with Task 1 and recording our result in the repository titled Task 1, this project explored two other mini-projects of Task 2 and Task 3.
The purpose of task 2 is to utilize quantum computation power for classification. In this respect, a variational classifier is implemented through variational quantum circuits.

 A parity function is emulated via a quantum circuit in the first part.  The classical data is encoded in a quantum state via Basisencoding. We tried other encoding strategies of Pennylane template IQPEmbedding, and we found the accuracy of the network converges to one sooner than Basisencoding.
 
Iris data, which has a real value dataset, must be classified in the second part. Here, the code utilizes angle encoding strategies. The original data is two-dimensional but has been padded to four dimensions. Therefore, the whole data set is encoded to two qubits via angled encoding. In task 4, we found the importance of this kind of data featuring more. Please see the Task 2 file in the repository.

Task 3 explores whether quantum computation and its complex Hilbert space can outperform conventional convolutional neural networks (CNN). To do so, a quantum convolutional neural network is defined. CNN is a proper neural network for image processing. Preprocessing a dataset through a quantum circuit that provides a highly complex kernel that is classically intractable is a potential novelty of QCNN. This work employs a partial of the MNIST data set. Each image is divided into 2x2 boxes; four real data of each box are encoded to a quantum state through an angle encoding technique on four qubits, then evolved by a quantum random circuit. After measurement, the result of each qubit is saved on a separate channel. Finally, the result goes to the classical NN to learn how to classify data sets. The output result with a limited number of data and simple NN does not display any priority of this quantum preprocessing to totally classic NN. However, adding a layer of ReLu has shown a marginal enhancement of the QCNN. Please see the Task 3 file in the repository.

For Task 4, we follow two strategies. First, we encode a real value sample in bits and then use the Basisencoding technique accompanied by a variational quantum circuit. However, we did not reach a good result. Then, we utilized angle encoding while padding one-dimensional data in six dimensions and encoded them in two qubits. We saw, to some extent, progress in our model.


### Project Presentation Deck:
_Upload/ Link a 3min. presentation deck here._
https://docs.google.com/presentation/d/1AFHkWSujBewsu2mIN09ye2jk2ahBGaZN/edit?usp=sharing&ouid=110859617138535429570&rtpof=true&sd=true
See project presentation guidelines [here](https://docs.google.com/document/d/13nWF8AxFAfFYTWEYPT3BpPdYkqtxxSAjmuXj_zcMh-E/edit?usp=sharing)

