STUDY OF DICTIONARY IN PYTHON

AIM: 
To study the concept of dictionary in Python and understand various dictionary operations such as accessing values, updating, adding, removing elements, and implementing real-life applications like product price update, student marks search, login validation, and finding highest scorer.

THEORY: (Functions and Concepts Used)

1. Dictionary in Python

A dictionary is a collection of key-value pairs.

Keys must be unique

Values can be duplicated

Dictionary is mutable (modifiable)

Syntax:

d = {"key": "value"}


Example:

d = {"brand": "ford", "year": 1964}

2. Accessing Values using Keys

Values are accessed using keys, not indexing.

print(d["brand"])

3. Duplicate Keys Not Allowed

If a key is repeated, the latest value overwrites the previous one.

{"year": 1964, "year": 2020}


Output will store only:

{"year": 2020}

4. Updating a Value

A value can be changed by assigning a new value to the key.

d["year"] = 2024

5. Adding New Key-Value Pair

A new entry can be added simply by writing a new key.

d["color"] = "red"

6. .update()

Used to modify or add multiple key-value pairs.

d.update({"color": "pink"})

7. .values()

Returns all values present in the dictionary.

y = d.values()

8. len()

Used to find number of key-value pairs.

len(d)

9. .pop()

Removes a specified key from dictionary.

d.pop("branch")

10. Membership Operator in

Used to check whether a key exists in dictionary.

if name in d:

11. .get()

Safely retrieves value of a key without error.

users.get(username)

12. max() with key=marks.get

Used to find key with maximum value.

topper = max(marks, key=marks.get)



_______________________________________________________________________________
PROGRAMS WITH ALGORITHMS

Program 1: Update Product Prices
Aim: To update the price of products stored in a dictionary.

Algorithm

1. Start
2. Create dictionary with product names and prices
3. Display original dictionary
4. Update product prices using key assignment
5. Print updated dictionary
6. Stop

Program 2: Search Student Marks

Aim: To search marks of a student using name input.

Algorithm
1. Start
2. Create dictionary with student names and marks
3. Take student name input from user
4. Check if name exists in dictionary
5. If found, display marks
6. Else, print student not found message
7. Stop

Program 3: User Login Validation

Aim: To validate login credentials using dictionary.

Algorithm

1. Start
2. Create dictionary with usernames and passwords
3. Accept username and password from user
4. Compare entered password with stored password using .get()
5. If matched, print login successful
6. Else, print login failed
7. Stop

 Program 4: Find Highest Scorer

Aim:
To find the student with the highest marks.

Algorithm

1. Start
2. Create dictionary with student names and marks
3. Use max() function with key=marks.get
4. Store topper name
5. Print topper name and marks
6. Stop

 CONCLUSION

Thus, we successfully studied the concept of dictionaries in Python, which store data in the form of key-value pairs. 
We learned operations like accessing values, updating entries, adding new keys, removing items, searching elements, validating users, 
and finding maximum values. Dictionaries are widely used for fast data storage and retrieval in real-world applications.
