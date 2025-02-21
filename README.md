### EX2 Generating Association Rules for Employee dataset using Apriori Algorithm
### DATE: 23-02-2024
### AIM: To generate associate rules for the employee dataset using Apriori Algorithm.
### Description:
In data mining, association rule learning is a popular and well researched method for discovering interesting
relations between variables in large databases. It can be described as analyzing and presenting strong rules discovered
in databases using different measures of interestingness. In market basket analysis association rules are used and they
are also employed in many application areas including Web usage mining, intrusion detection and bioinformatics.
Creation of Buying Table:
### Procedure:
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Buying Table.

```
@relation buying
@attribute age {L20,20-40,G40}
@attribute income {high,medium,low}
@attribute stud {yes,no}
@attribute creditrate {fair,excellent}
@attribute buyscomp {yes,no}
@data
L20,high,no,fair,yes
20-40,low,yes,fair,yes
G40,medium,yes,fair,yes
L20,low,no,fair,no
G40,high,no,excellent,yes
L20,low,yes,fair,yes
20-40,high,yes,excellent,no
G40,low,no,fair,yes
L20,high,yes,excellent,yes
G40,high,no,fair,yes
L20,low,yes,excellent,no
G40,high,yes,excellent,no
20-40,medium,yes,excellent,yes
L20,medium,yes,fair,yes
G40,high,yes,excellent,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows buying table on weka.
### OUTPUT:


### Procedure for Association Rules:
1) Open Start -> Programs -> Accessories -> Notepad
2) Open explorer.
3) Click on open file and select buying.arff
4) Select Associate option on the top of the Menu bar.
5) Select Choose button and then click on Apriori Algorithm.
6) Click on Start button and output will be displayed on the right side of the window.

### OUTPUT:
## Employee dataset
![exp2emp1](https://github.com/varalakshmi1084/WDM_EXP2/assets/93427594/2753cfc6-cbcc-41f1-a26b-17b76c04ca09)
## Banking dataset
![exp2bank1](https://github.com/varalakshmi1084/WDM_EXP2/assets/93427594/07e96211-a387-456b-9040-aede6c41f97b)
## Buying dataset
![exp2(1)](https://github.com/Archana2003-Jkumar/WDM_EXP2/assets/93427594/61e32485-d5b9-48da-9128-9ab9cf808911)

### Procedure for Association Rules:
1) Open Start -> Programs -> Accessories -> Notepad
2) Open explorer.
3) Click on open file and select buying.arff
4) Select Associate option on the top of the Menu bar.
5) Select Choose button and then click on Apriori Algorithm.
6) Click on Start button and output will be displayed on the right side of the window.
### OUTPUT:
![exp2emp2](https://github.com/varalakshmi1084/WDM_EXP2/assets/93427594/0a634b6e-5aec-4bfc-82fa-5980291ddd00)
![exp2bank2](https://github.com/varalakshmi1084/WDM_EXP2/assets/93427594/7c01d748-ea6c-45d9-b564-e4418113b359)
![exp2(1)](https://github.com/varalakshmi1084/WDM_EXP2/assets/93427594/881f1744-ee87-4840-ba1e-7bbb948d06c6)

### RESULT: 
Thus generation of  associate rules for the various dataset using Apriori Algorithm has been successfully executed.
