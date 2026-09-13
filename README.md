# Python Learning

##Lesson 01: Print function
### Objectives:
- use the print function to print a message
- use the string manipulation to format strings appropriately
- establish variables

### Notes:
- print("message") will print any message included inside the quotations within the parenthesis.
- print() allows for a new line.
- assign a value to a variable with an equals sign.
  - this method can save time and optimize the program without repeated techniques.
- title() method changes each word to title case, where each word begins with a capital letter.
- lower() method changes each word to lower case.
- upper() method changes each word to upper case.
- f-strings can format strings by replacing the name of any variables in braces with its value.
  - example: print(f"I am majoring in {major.title()})
  - This example would print the string "I am majoring in" and includes the major in title case as it was assigned earlier. The value of the variable 'major' would replace the variable when the string is displayed.
- strip() method strips whitespace from both sides of a string.

##Lesson 02: Dictionaries and Lists
### Objectives:
- create a dictionary
- create a list

### Notes:
#### Dictionaries-
- a dictionary is a collection of key-value pairs. Each key is connected to a value, and you can use a key to access the value associated with that key.
- a dictionary is wrapped in braces ({}) with a series of key-value pairs inside the braces.
- every key is connected to its value by a colon, and individual key-value pairs are separated by commas.
- it is sometimes convenient, to start with an empty dictionary and then add each new item to it.
- example:
          scifi_book = {
            "title": "the martian",
            "author": "andy weir",
            "year": "2011",
            "isbn": ("978-0553418026")
          }

          fantasy_book = {
            "title": "a game of thrones",
            "author": "george r.r. martin",
            "year": "1996"
            "isbn": ("978-0553573404")
          }

          romance_book = {
            "title": "a court of thorns and roses",
            "author": "sarah j. maas",
            "year": "2015",
            "isbn": ("978-1635575569")
          }

#### Lists-
- a list is a collection of items in a particular order.
- a list is wrapped in square brackets ([]) to indicate a list, and individual elements in the list are separated by commas.
- example:
          fruits = ['apples', 'oranges', 'bananas']