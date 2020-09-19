__________________________________________________________________________________________
---------------------------------------READ ME--------------------------------------------
__________________________________________________________________________________________

INSTRUCTION  : To run the Project_Main.py (Runs both the algorithm automatically)
__________________________________________________________________________________________

Requirements: 3 Datasets provided with the project namely:
              1) Market_Basket_Optimisation.txt
              2) Random_Test.txt
              3) Chess_data.txt
          
# The Project_Main.py runs both the H_mine and Apriori algorithm for all the 3 datsets and
  outputs the result into files.
 
 To Run the program :
 
 1. Open Terminal(Mac) or Cmd(Windows).

 2. Change your directory to the same directory where the program is stored.

      Command: cd /path/to/program

 3.  Enter The Command:
    
    python Project_Main.py  

    Note : enter "python3 Project_Main.py" for bluenose.
     
 4. After Running, the Program will read all the 3 datasets one by one and run H-mine and 
    Apriori with arbitrary value of minimum_support given in the file. 

 5. The ouput file is generated indicating the name of the dataset and the algorithm
    used. Confirmation of storage is given in the terminal with a prompt.

 NOTE: Only 5 files are generated since Apriori algorithm is not triggered for chess.txt.

__________________________________________________________________________________________

Instruction: To Run algorithm H_Mine_Algo.py or Apriori_Algo.py Invidually.
__________________________________________________________________________________________

# Any .txt dataset with items seprated by delimiter = " " can be used.

NOTE :Python interactive shell is used to run the runHmine() or runApriori().

To Run the module :
 
 1. Open Terminal(Mac) or Cmd(Windows).

 2. Change your directory to the same directory where the program is stored.

      Command: cd /path/to/program
      Command: "python" (to enter pyhton interactive shell)
      NOTE: use "pyhton3" for Bluenose

 3.  Enter The following Command in python interactive shell:

     >>import Apriori_Algo
     >>import H_Mine_Algo

     Apriori_Algo() and H_Mine_Algo() takes 3 parameters:

     1) Input_file_name.txt
     2) Output_file_name.txt
     3) Relative support (Valid range 0<x<1)

     For example,

     >>Apriori_Algo.runApriori("Random_Test.txt","Random_Test_Out.txt",0.1)

     >>H_Mine_Algo.runHmine("Random_Test.txt","Random_Test_Out.txt",0.1)
       
     
 4. After Running, the Program will read the input file and run the corresponding
    algorithm with the given minimum_support. 

 5. The ouput file is generated with the given name. If completed successfully Program 
    will print a completion message.


__________________________________________________________________________________________

CONTACT INFO
__________________________________________________________________________________________
__________________________________________________________________________________________

NAME: Aman Jaiswal                              
Banner Id: B00857194
Email: aman.jaiswal.dal.ca

NAME: Mohamed Muzamil H
Banner Id: B00838531
Email: mohamed.muzamilh@dal.ca
__________________________________________________________________________________________