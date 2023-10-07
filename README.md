
# String
    Strings in python are surrounded by either single quotation marks, or double quotation marks.
    'India' is the same as "India"

## Create a variable containing STRING
     a = "India"
     print(a)
     India
## Multiline Strings: should enclosed within triple single/double quotes
     a = """This is a multiline string."""
     You can see it is enclosed within thrice double quotes"""
     print(a)
# you can notice in result that new line is printed same as it is written
     This is a multiline string.
     I am writing this string for demo purpose.
     You can see it is enclosed within thrice double quotes


# Slicing in string
     You can slice the string by passing its index.
     Positive index start from ZERO and goes from left to right
     Negative index start from -1 and goes from right from left
     Starting index starts slicing from same index
     Ending index ends slicing one step before.
     Syntax: string[Start : Stop : Step]

     # Slice string from index 2 to 4
     country = "India"
     print(country[2:4])
     di
     Hete, You can notice slicing start from 2(start index) but it ended at 3 instead of 4


     # Slice From the Start: If start index missing it will take default=0
     country = "India"
     country[:4]
     Indi

     # Slice To the End: If end index missing then it will take default=last index
     country = "India"
     country[2:]
     dia
