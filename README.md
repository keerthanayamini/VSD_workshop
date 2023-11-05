VSD WORKSHOP

5 day TCL training workshop by VSD using Yosys and Opentimer open-source EDA tools and TCL to generate a report from a design, wherein the input is design file paths in .csv format to the TCL program. The final objective by day 5 is to give design details, namely paths of design data, to the "TCL BOX", which is the UI being designed, which runs the design in Yosys and Opentimer open-source EDA tools and returns a report of the design.

DAY 1:
Task : To pass csv file from UNIX shell to tcl script

3 general scenarios

1.Not provided .csv file

2.Ask for help

3.CSV file which was provided is not available

UNIX script:
![image](https://github.com/keerthanayamini/VSD_workshop/assets/149821079/44640590-cbe4-463f-9506-9b1ade3f63b8)

![image](https://github.com/keerthanayamini/VSD_workshop/assets/149821079/beac6c6e-f10c-4597-a09f-1e0151e0d382)
RESULTS:
scenario1:
![image](https://github.com/keerthanayamini/VSD_workshop/assets/149821079/e0443d2a-7d3d-487d-bcf6-faa5b62544ea)

scenario2:
![image](https://github.com/keerthanayamini/VSD_workshop/assets/149821079/323702e7-9eee-4d1b-9dab-c08adc42dbbb)

scenario3:
![image](https://github.com/keerthanayamini/VSD_workshop/assets/149821079/b4106b7d-0958-4ecc-90ee-523344330848)
DAY2:

1.Create variables for the inputs
(tclsh yamini1.tcl openMSP430_design_details.csv) to csv file to tcl scripts

Code for assigning directory or file paths to variables:
![image](https://github.com/keerthanayamini/VSD_workshop/assets/149821079/989f8caa-9c65-4905-8f2c-f840bfca8ec4)
OUTPUT
![image](https://github.com/keerthanayamini/VSD_workshop/assets/149821079/b11537ee-3bc8-44ea-95db-a94ee10041d1)
Code to check if directories and files exits:
![image](https://github.com/keerthanayamini/VSD_workshop/assets/149821079/453afcc0-3adc-4350-aee7-5b8a2bd767c7)
OUTPUT
![image](https://github.com/keerthanayamini/VSD_workshop/assets/149821079/02455f1f-747b-489f-a624-c1733ba9b813)
Code to check number of rows & number of columns and row number and column no. of the given element in csv file:
![image](https://github.com/keerthanayamini/VSD_workshop/assets/149821079/c21707a4-6109-4166-86ba-98c3418705eb)
OUTPUT
![image](https://github.com/keerthanayamini/VSD_workshop/assets/149821079/28ada7ac-0566-48b9-a5a7-cbfdd0763f27)
Code to convert excel sheet of clocks section to sdc format:
![image](https://github.com/keerthanayamini/VSD_workshop/assets/149821079/45e15067-bf98-4471-97b7-6565c086c8e7)
OUTPUT
![image](https://github.com/keerthanayamini/VSD_workshop/assets/149821079/a83b4f1a-4452-4d34-b5fc-980d723e49c0)
SDC file:
![image](https://github.com/keerthanayamini/VSD_workshop/assets/149821079/1279d584-5055-4d4b-bc41-31e8e981762e)








