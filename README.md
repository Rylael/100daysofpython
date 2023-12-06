# 100daysofpython

100 days of python - udemy course

**git stuff** 
 *terminal commit* - git add . && git commit -m "comment"
# day 1

**comments** - # *single line*
**"\n"** - string in a new line
**input = ()** - prompts an input from the user
   *inputs can be nested* - print("Hello" + input("What is your name?"))
   *moar nesting!!!* - print( len( input("What is your name? ") ) )

# day 2

"string"[number] - *subscripting* - references the character at the number position (starting with 0)
123_234_456 - Same as , in large numbers
newType(variable) - *type conversion* - converts ex. int into str **Give it a newVariable!!**

# day 3

rounding - round(x / y, z) - where z is the number of decimals
(x // y) - division into an int
variable += x - where operators can be + - * / followed by = result in that variable operating on itself by x
**f-string**!! - *f"string {var} {var2}"* - lets you concatenate various var types without +
Finished the tipCalculator project

# day 4

if else - if x: else: - colon to signal indentation
elif - else if statement, checks for more conditions
== - equal to
!= - not equal to

# day 5 

**random numbers**
import random
random.randint (a, b)

**IMPORTING** 
import xy - importing modules, modules are and can be different .py files

**LISTS**
list = [item1, item2]
list = ["string1", "string2"]
list[0] - first item in the list

len(listName) - number of items

After creating the list, you can modify it, by using the *list[offset] = new data

Add item to the list - listName.append(newItem)
Add list to list - listName.extend([item1, item2])

index errors - list index out of range - when calling a variable that's a len, usually subtract 1 from the call - print(indexName[itemNumber] - 1)

You can nest lists - bigList[list1, list2]