##Lesson 11 "Comments"

Command + /: comment/uncomment
--> `#3+3 (doesn't get executed)`


##Lesson 16 "Custom Functions"

*Default Argument(s)*

`
def sum(a = 1, b = 2):
    return (a + b)
    
print(sum(1, 1)) # Output: 2
print(sum()) # Output: 3
`
If there's no argument passed while function call, the default arguments will be automatically assigned to those values
