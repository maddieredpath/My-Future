# My Future
_Hopefully_, my future consists of some IT career.  
Because of that, I will share why in python form code!  

```
print('my dad is an IT')
print('I love what I am studying, since I changed my major from business')
```
Also, here's a project I worked on for another class.
'''js
high_num = int(input("Print a highway number:" , ))
if (high_num % 2 != 0) and (1 <= high_num <= 99):
    result = "primary"
    direction = "north/south."
elif (high_num % 2 != 0) and (101 <= high_num <= 999):
    result = "auxiliary"
    direction = "north/south."
    service = (high_num % 100)
elif (high_num % 2 == 0) and (1 <= high_num <= 99):
    result = "primary"
    direction = "east/west."
elif (high_num % 2 == 0) and (100 <= high_num <= 999):
    result = "auxiliary"
    direction = "east/west."
    service = (high_num % 100)
elif (high_num % 100) == 0:
    result = "not possible"
    
if result == "primary":
    print("I-" , high_num , "is" , result , ",going" , direction)
if result == "auxiliary":
    print("I-" , high_num , "is" , result , "serving I-", service, ",going" , direction)
if result == "not possible":
    print(high_num , "is not a valid interstate highway number.")
'''
