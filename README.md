# Combinatorics-ML-Gene-Fusion
[a.a. 23/24] E. Autore

                                          
--------------------------------------------------------------------------------------------------------------------
**To run the project follow the steps:**
  
   1) Navigate to the "Combinatorics-ML-Gene-Fusion" folder, open terminal and create a virtual environment for Python:

      ```python -m venv venv``` (Windows)

      ```python3 -m venv venv``` (Mac)
   
   1) Run the commands to activate the virtual environment:
   
      ```venv\Scripts\activate``` (Windows)
   
      ```source venv/bin/activate``` (Mac)
      
   2) Install the libraries with the following command:
   
      ```pip install -r requirements.txt```
   
   3) If python interpreter is not configured:

      - Go to **File** ->**Settings** ->**Python interpreter** ->**click the gear icon** ->Select **Add** ->**Exsisting Enviroment** ->**Combinatorics-ML-Gene-Fusion\venv\Scripts\python.exe** -> **click ok** 
--------------------------------------------------------------------------------------------------------------------

**Preliminary actions**:

Go to project folder **Combinatorics-ML-Gene-Fusion** with explorer and extract all **file .rar** or those that can be used to repeat tests

--------------------------------------------------------------------------------------------------------------------
**information about options for various commands**:

- **dictionary= yes or no**: you can decide whether to use fingerprint management with an adaptive window (yes) or with a fixed window (no) of size 300 bp
  
- **k_value = 3 to 8 (8 best value)**: is the number of k-mers extracted from a fingerprint (k-finger) and it has been found that the value with the best results is (k_value = 8)
  
- **n = 4 or 8**: is the number of processors used for parallel execution, for an averagely powerful machine the value (n = 4) is recommended, otherwise for more powerful machines or servers (n = 8)
    
    - if k = 4 would give an error like this: **UserWarning: Loky-backed parallel loops cannot be called in a multiprocessing,, setting n_jobs=1n_jobs = min(effective_n_jobs(n_jobs), n_estimators)**
      or other types of problems, **set (k = 2)**

