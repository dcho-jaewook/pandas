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


##Lesson 17 "String Methods"

*.upper()*
`"Hello World".upper()`
`HELLO WORLD`

*.lower()*
`"Hello World".lower()`
`hello world`

*.swapcase()*
`"Hello World".swapcase()`
`hELLO wORLD`

*.title()*
`"luna and david".title()`
`Luna And David`

*.capitalize()*
`"luna and david".title()`
`Luna and david # Only the first letter of the entire string`

*.lstrip(), .rstrip(), .strip()*
`"   Hello World   ".lstrip()`
`Hello World   `

`"   Hello World   ".rstrip()`
`   Hello World`

`"   Hello World   ".strip()`
`Hello World`

*.replace(str1, str2)*
`status = "UCLA Student"`
`status.replace("UCLA", "UC Berkeley")`
`status # Output: "UC Berkeley Student"`
Replace all the exsistence of str1 to str2


*.startswith(str)*
Boolean
Check whether the string starts with str

*.endswith(str)*
Boolean
Check whether the string ends with str

