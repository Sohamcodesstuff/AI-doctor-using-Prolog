# AI-doctor-using-Prolog
This is a simple AI based doctor coded in Prolog.
The report describes a program written in SWI-prolog declarative language to mimic the diagnosisprocess by conversing with a patient who can only say yes or no, and additional two commandstoquit the program and force to diagnose. 
The doctor will ask about the mood and pain level of the patient, and the tone of the questionswillchange accordingly. 
Afterwards the doctor will ask consecutive questions to determine the symptomsthe patient has. 
If the patient affirms one particular symptom, the symptomwill be recorded, andanother related symptom will be randomly picked, and the program will ask the patient again. 
Otherwise if the patient negates the symptom, the program will record it as well and randomly pick one symptom from all available unasked symptom poll to ask the patient. 
If one or more diseased can be diagnosed, the program will display the diagnose analysisandterminate. 
If no match can be found, the program will print the error message and terminate. 
The diseases and their related symptoms are pre-defined and stored in the program’s knowledge base. 
The program can be rerun for arbitrary times in one execution process with previous diagnosis historycleared.
