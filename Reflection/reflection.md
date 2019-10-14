# Reflection

## Question 1 (50 words)
#### When and why should you use a function like `carefulSubract` rather than `subtract`? 
You should use a function like "careful subtract" if you are unsure whether or not the input will be numbers or whether it will be a string. By testing the variable first, you can then have the correct output (whether the correct output is the subtracted number or a designated message). This testing of the variable will help prevent errors in the code form occuring. For example, if the input for the "subtract" function was two strings, it may subtract the number of words in the string (or the number of letters if the string is just one word), which would ne be the desired outcome. 

## Question 2 (100 words)
#### What are `data types`, and how does data typing work in JavaScript? Name at least 4 built-in data JS data types. 

Data Types are the built in designators for different data the system may encounter. By placing all of this data into designated types, it helps JavaScript to know what to do with the data,and use it properly in the code. 
Some examples of built in data types are: string, number, boolean, arrays, onjects, and undefined. 
Using the examples above, by knowing that the inputted data is a "number", Javascript will know that this piece of data can be added, subtracted, multiplied etc with another "number". By classifying that it is an "array" rather than a "string", Javascript will use that classification and make the inputted words into a list rather than into a longer sentence. 

## Question 3 (100 words)
#### What is the advantage to storing information as an object (`{firstName: 'Italo', lastName: 'Calvino', profession: 'novelist' }`) rather than as an array (`['Italo', 'Calvino', 'novelist']`)? Are there any disadvantages?

The advantage to storing information as an object rather than as an array is that it requires less code and is easier to manipulate the variables. By using the example in the question, by storing the information as an object, we can return it as (firstName, LastName, Profession) and then just simply change the input as needed. From here, every function that uses this onject label willbe immidiately changed. However, with the array, you would have to go into each array list seperately and change the input that you wish to change. 

## Question 4 (150 words)
#### The function `sentences` transforms a data structure (in this case, a list of object literals) into a sequence of sentences. If the data structure were less predictable (e.g., if some properties of each object were occasionally missing, or if their data type was not always the same), what programming techniques could you use to ensure that your function produced a coherent output? Also, can you think of a more interesting "transform" that could be done with the same data structure?


