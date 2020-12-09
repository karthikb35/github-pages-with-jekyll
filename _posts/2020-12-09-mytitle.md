---
title: "pytest.ini"
date: 2020-12-09
---

pytest.ini file has some pytest configuration variables that define the:

	• Markers documentation
	• python_classes
	• python_functions
	• python_files
	
![image](https://user-images.githubusercontent.com/66718708/101616162-0b2b5900-3a35-11eb-9ccf-ce81132ca2be.png)

  How to run cases that are marked:
	pytest -m "sample"
	pytest -m "sample and smoke"
	pytest -m "not smoke"
	
Marking a class will mark all functions(cases) in the class
