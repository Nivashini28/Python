**Python** 
Python is an object-oriented programming language.
It can run on any platform like Windows, MAC, LINUX and on other OS.
It runs on a interpreter system where the codes are executed when it is written.

**Uses:**
It is used for:
1.Web development.
2.Software development.
3.To solve complex mathematics problems.
4.Used in data analysis.
5.Used in data visualization.
6.Task automation.

**Benefits:**
1.Increases code readability.
2.Increases code reusability.
3.It can be used on a server to create web applications.
4.It can be connected to databases where we can read or modify the code.
5.It can be used for rapid prototyping for software development.
6.It has a basic syntax where users require fewer lines to execute the code.

**Functions and Variables:**
def display():
	first=”hallo”
	second=”hi”
	third=”welcome”
	total={“hallo”: first, ”hi”: second}
return total
total=display()
print(total)

Output: hi
After using dictionary the output will be changed according to the user requirement.

Explanation:
In the above example, three variables with values are defined and a  method is declared. By using return keyword we return the required value from the method and the method values are stored in a   new variable. By using print statement we can print the required output.

**Dictionary:**
It is used to store date vales in  keys:value pairs.
Eg:
thisdict ={ “brand”: “Ford”,
                     “model”:”Mustang”, 
                     ”year”:”1990”
}
Length
len()
eg: print(len(thisdict))

type()
 eg: print (type(thisdict)) 
output : <class ‘dict’>

**Collections(Arrays):**
There are four collection data types:
1.List:
 Ordered, Changeable, Allows duplicate values.
2.Tuples:
Ordered, Un-Changeable, Allows duplicate values.
3.Set:
Unordered, Un-Changeable, No duplicate values.
4.Dictionary:
Ordered, Changeable, No duplicate values.

We can access the dictionary items using various functions which are:
Keys() :
This method will return a list of all the keys in the dictionary.

get() 
To get the value of the dictonary, we use get() or [ ]

Values():
This method will return a list of all the values in the dictionary.

Items():
This method will return items in the dictionary.

In
To check a key is present in the dictionary a keyword “in” is used.

eg: if “model” in thisdict:
            print(“model is present”) 


if and elif statements:
x=23
y=45
if x<y:
	print(“y is greater than x”)
elif x>y
	print(“x is greater than y”)
Output:
y is greater than x
 








