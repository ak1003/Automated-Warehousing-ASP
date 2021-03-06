# Automated Warehousing Scenario

- The following is the implementation for the Automated Warehouse Scenario, details about which can be found in the [ASP challenge 2019](https://sites.google.com/view/aspcomp2019/problem-domains)
- The project is complete with no currently known anomalies
- Please find the directory structure below

	- simpleInstances
	**It contains the various initialization files for checking the working of the system.**
	```python
		+ inst1.asp
		+ inst2.asp
		+ inst3.asp
		+ inst4.asp
		+ inst5.asp
	```
    
	- convert_input.asp - 
	**It changes the input file schema to an easily readable and understanble form that we used to implement the constraints of the project.**
	
	- parsing.asp - 
	**This file contains code for obtaining various values for the number of objects and their type in the system.**
	
	- demo.asp - 
	**The main file where the code for all the constraints resides including**
	
  	- description.pdf - 
  	**The pdf containing the problem statement and description of the system.**
  
	- script.py - 
	**A python file for easier execution of the program.**

## Dependencies
```python
1. Python==3.7
2. Clingo==5.4.0
```

## How to Run
1. Make sure you have **python** and **clingo** configured on the system.
2. Download the project into a suitable folder on your local computer.
3. Run the **script.py** file to test the project.

## Commands
```python
python script.py
```
