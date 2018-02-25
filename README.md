## Naughty Solution
## Ali Khazendar, Casper Emde Christensen, Stephan Pedersen, Nicklas Vikke (JEFF)


Pre words on our solution: 
- We have only been able to complete question 1 and 2, and not in a way that have been expected. We had some major issues with converting the file with the data, although after some time we managede to convert the file but got reallly bad structure of data in the file, which gave us some huge problems to solve the assignment.
So therefore in question 1 we decided that we only look on the crimes for the first year, and last year to analyse if the crime has dropped or grown.
For question 2 we use the result from the first answer, where the graphs shown how the crime has changed.

## NOTE: We couldn't find a way to put to graphs in one model, so we have code for two graps in the bottom of the script which you have to outcomment one at a time to run at see the result.

## ---> Jupyter NoteBook Format <---:
## https://github.com/INFINITE-KH/Python-Assignment1/blob/master/codeInNoteBook.ipynb

## NB!! on X axis: The output of the long list should be the data on the X axis but it's messed up so that's why. (Messed up data converting in the first place!!!).

Questions:

- 1) Has the crime decreased or increased over the last 20 years?

Text answer: xxxx

Code answer: 

%matplotlib notebook
import c
import matplotlib.pyplot as plt
import matplotlib.pyplot as plt2

count = 0
data = {}
my_data = c.STATISTICS["1994"][0]
my_data2 = c.STATISTICS["2013"][0]

my_data3 = c.STATISTICS["Year"][0]
array_1994 = []
array_2013 = []
for value in my_data.values():
    value = value.replace(".", "")
    value = value.split(",")
    array_1994.insert(len(array_1994), value[0])
for n, g in zip(my_data3.values(), array_1994):
    print(n, g)
    
for value in my_data2.values():
    value = value.replace(".", "")
    value = value.split(",")
    array_2013.insert(len(array_2013), value[0])

for n, g in zip(my_data3.values(), array_2013):
    print(n, g)
    
#plt.bar(my_data3.values(), array_1994, color = "green")
#plt.bar(my_data3.values(), array_2013, color = "blue")

Our results: xxxx

- 2) Has the type of crime changed?

Text answer: xxxx

Code answer: 

%matplotlib notebook
import c
import matplotlib.pyplot as plt
import matplotlib.pyplot as plt2

count = 0
data = {}
my_data = c.STATISTICS["1994"][0]
my_data2 = c.STATISTICS["2013"][0]

my_data3 = c.STATISTICS["Year"][0]
array_1994 = []
array_2013 = []
for value in my_data.values():
    value = value.replace(".", "")
    value = value.split(",")
    array_1994.insert(len(array_1994), value[0])
for n, g in zip(my_data3.values(), array_1994):
    print(n, g)
    
for value in my_data2.values():
    value = value.replace(".", "")
    value = value.split(",")
    array_2013.insert(len(array_2013), value[0])

for n, g in zip(my_data3.values(), array_2013):
    print(n, g)
    
#plt.bar(my_data3.values(), array_1994, color = "green")
#plt.bar(my_data3.values(), array_2013, color = "blue")

Our results: xxxx

- 3) Has the crime moved to from one area to another?

Text answer: xxxx

Code answer: xxxx

Our results: xxxx

- 4) Is there a connection between type of crimes and locations?

Text answer: xxxx

Code answer: xxxx

Our results: xxxx

- 5) Which year was the most crime and what crime occured most times?

Text answer: xxxx

Code answer: xxxx

Our results: xxxx
