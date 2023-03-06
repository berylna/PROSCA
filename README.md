This is the README document for PROSCA, an online platform for humanized scaffold mining facilitating rational protein engineering.  

**Release notes**  
* Version 1.0; Febrary 2023

**USAGE:**  
* GET STARTED  
* USAGE COMMANDS  
* RESULTS  

**(1) GET STARTED**  
PROSCA doesn't require any compilation. The input file, "AFalign" or "PDBalign" file, "AlphaFold_library" folder, as well as the "PDB_library" folder should be placed in the same shell's search PATH directory.Access rights of "AFalign" or "PDBalign" file may also need to be changed to make them executable.  
The latest version of TM-align (available from the Zhang lab at https://zhanggroup.org/TM-align/) need to be installed in the same PATH directory. "AlignedStructures1" folder and "AlignedStructures2" folder are created before runing PROSCA to save the results of 3D structures.   
It is noticed that "PDB_Supplement" file should be placed in the above PATH when running PDBalign script.  

**(2) USAGE COMMANDS**  
To aligh the input protein with AlphaFold structures: ./AFalign <input_file>  
To aligh the input protein with PDB structures: ./PDBalign <input_file>  

**(3) RESULTS**  
After processing the input file, PROSCA will generate a file "AlignedResults" and many structure files of target proteins.The "AlignedStructures1" folder stores various structures such as the superposed full-atom structures of two proteins and discontinuous strucures of human proteins. The "AlignedStructures2" folder stores the complete structures of aligned human proteins.  


**Availability**  
PROSCA is freely available at http://prosca.idrblab.cn/ and does not have a login requirement. The code for PROSCA is open source and available in the GitHub repository (https://github.com/berylna/PROSCA/).  

**Suggestions**  
If you have any feedback, please contact us at wangxn@cqu.edu.cn or zhangyintao@zju.edu.cn. If you are reporting a bug, please include the full error message recieved when running PROSCA.  
