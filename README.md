# Fuzzy-Logic-on-LabView
Implementation of Fuzzy Logic on Labview to regulate the the water level in a tank

## Fuzzy Logic 
The term fuzzy refers to things which are not clear or are vague. In the real world many times we encounter a situation when we can’t determine whether the state is true or false, their fuzzy logic provides a very valuable flexibility for reasoning. In this way, we can consider the inaccuracies and uncertainties of any situation.

![fuzzy](https://user-images.githubusercontent.com/38221793/58820261-660b1580-8632-11e9-80f7-341a276bc2b0.PNG)

Fuzzy System Designer

## ARCHITECTURE
Its Architecture contains four parts :


RULE BASE: It contains the set of rules and the IF-THEN conditions provided by the experts to govern the decision making system, on the basis of linguistic information.

FUZZIFICATION: It is used to convert inputs i.e. crisp numbers into fuzzy sets. Crisp inputs are basically the exact inputs measured by sensors and passed into the control system for processing, such as temperature, pressure, rpm’s, etc.

INFERENCE ENGINE: It determines the matching degree of the current fuzzy input with respect to each rule and decides which rules are to be fired according to the input field. Next, the fired rules are combined to form the control actions.

DEFUZZIFICATION: It is used to convert the fuzzy sets obtained by inference engine into a crisp value. There are several defuzzification methods available and the best suited one is used with a specific expert system to reduce the error.

![rules](https://user-images.githubusercontent.com/38221793/58820259-65727f00-8632-11e9-991f-82871905ea79.PNG)

Fuzzy Rules

The function of this project is to design a tank control system that regulates the height of the water level based on fuzzy logic. 
The input variables are the rate of change of height and the error from the desired height,
which are used to determine the output flow change.

![vi](https://user-images.githubusercontent.com/38221793/58820260-65727f00-8632-11e9-90a3-855a5cbb1bdb.PNG)

![overview](https://user-images.githubusercontent.com/38221793/58820263-660b1580-8632-11e9-8d39-5414f2fda785.JPG)

https://www.behance.net/gallery/81068741/Fuzzy-Logic-on-LabView


