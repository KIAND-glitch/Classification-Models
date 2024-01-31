
This README contains detailed feature descriptions for the two data sets provided with this assignment.


************************************************************************************
1.) The Student data set

Instances:
- Each instance (line in the file) represents a student.

label: 
- The final grade (A+, A, B, C, D, F) indicating what score the student achieved.

Features: 
1 school - students school (binary: "GP" - Gabriel Pereira or "MS" - Mousinho da Silveira)
2 sex - students sex (binary: "F" - female or "M" - male)
3 address - students home address type (binary: "U" - urban or "R" - rural)
4 famsize - family size (binary: "LE3" - less or equal to 3 or "GT3" - greater than 3)
5 Pstatus - parents cohabitation status (binary: "T" - living together or "A" - apart)
6 Medu - mothers education (nominal: low, none, mid, mid, high)
7 Fedu - fathers education (nominal: low, none, mid, mid, high)
8 Mjob - mothers job (nominal: "teacher", "health" care related, civil "services" (e.g. administrative or police), "at_home" or "other")
9 Fjob - fathers job (nominal: "teacher", "health" care related, civil "services" (e.g. administrative or police), "at_home" or "other")
10 reason - reason to choose this school (nominal: close to "home", school "reputation", "course" preference or "other")
11 guardian - students guardian (nominal: "mother", "father" or "other")
12 traveltime - home to school travel time (nominal: none,  low, medium, high, very_high)
13 studytime - weekly study time (nominal: none,  low, medium, high, very_high)
14 failures - number of past class failures (nominal: none,  low, medium, high, very_high)
15 schoolsup - extra educational support (binary: yes or no)
16 famsup - family educational support (binary: yes or no)
17 paid - extra paid classes within the course subject (binary: yes or no)
18 activities - extra-curricular activities (binary: yes or no)
19 nursery - attended nursery school (binary: yes or no)
20 higher - wants to take higher education (binary: yes or no)
21 internet - Internet access at home (binary: yes or no)
22 romantic - with a romantic relationship (binary: yes or no)
23 famrel - quality of family relationships (nominal: very_bad, bad, mediocre, good, excellent)
24 freetime - free time after school (nominal: very_low, low, mediocre, high, very_high)
25 goout - going out with friends (nominal: very_low, low, mediocre, high, very_high)
26 Dalc - workday alcohol consumption (nominal: very_low, low, mediocre, high, very_high)
27 Walc - weekend alcohol consumption (nominal: very_low, low, mediocre, high, very_high)
28 health - current health status (nominal: very_bad, bad, mediocre, good, excellent)
29 absences - number of school absences (nominal: none, one_to_three, four_to_six, seven_to_ten, more_than_ten)

Source: https://archive.ics.uci.edu/ml/datasets/student+performance# 

************************************************************************************
2.) The Adult data set

Instances:
- Each instance (line in the file) represents a single US citizen.

label: 
- binary in {<=50, >50} indicating whether an individual earns more than 50K USD a year or up to 50K USD.

Features: 

1 workclass :  type of work arrangement (self employed, government employed, private, ...)
2 education :  highest degree obtained by the individual
3 marital-status :  marital status of the individual
4 occupation : coarse-grained type of occupation (repair, sales, armed forces, ...)
5 relationship : relationship status in the individual's household (husband, wife, own-child, ...)
6 race : race of the individual
7 sex : sex of the individual (male, female(
8 native-country : country of birth of the individual
9 age : age of the individual
10 fnlwgt : "final weight" derived from sociodemographic features in the US census statistics
11 Education-num : duration of education (in years)
12 Capital-gain : Total capital gain of the individual
13 Capital-loss : Total capital loss of the individual
14 Hours-per-week : Hours of paid work done by the individual (per week)


Source: https://archive.ics.uci.edu/ml/datasets/adult

************************************************************************************


