# qiskit-quantum-Chemistry
## ▶️ Run in Google Colab

No need to install anything! You can run the full quantum example in your browser using Google Colab.

👉 [Click here to open the notebook in Colab](https://colab.research.google.com/drive/13-cbaJZAW3cXrBz1EsEhTLtN6Bpa1sYs?usp=sharing)

The notebook walks you through:
- import Neccessary library
- Creating a Bell state quantum circuit(##create a new circuit with two quibits)
  <img width="241" height="174" alt="image" src="https://github.com/user-attachments/assets/228b14aa-2b17-4c6f-a9ab-c1301eedcad5" />


  -using the RuntimeService

  
  - Running your quantum circuit on a real IBM QPU

**API_KEY = "<Your API Key from IBM Cloud>"
service = QiskitRuntimeService.save_account(
    channel="ibm_cloud",
    token=API_KEY,
    instance="<Your IBM instances>",
    set_as_default=True,
    overwrite=True
)**


- Measuring entangled qubits using Pauli operators
  <img width="796" height="251" alt="image" src="https://github.com/user-attachments/assets/42e2cc12-2a53-40ce-a64a-f8f8ef4c8f22" />


- CONSTRUCT AN ESTIMATOR
- Getting the results from the job submitted

- -RUNNING ON THE SIMULATOR
-**Analysing the Circuit built (0,1)**
<img width="567" height="455" alt="image" src="https://github.com/user-attachments/assets/72a86856-0e61-4412-8e8b-a41498578231" />
##CREATING THE LARGE SCALE NUMBER OF QUBITS AND GATEES

-Map to the operator of interest
-Optimizing the system
-EXECUTE ON THE HARDWARE*
- PLOTTING THE OBESERVABLES AND THE ERRORS  IN TERMS OF THTE GATES AND THE STANDARD DEVIATIONS
  <img width="582" height="436" alt="image" src="https://github.com/user-attachments/assets/1ec4a3d7-643d-4ec4-889a-1222d71016da" />





