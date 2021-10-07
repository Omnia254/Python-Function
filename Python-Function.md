```python
def my_function_name(firstname):
  print (firstname)
  
# Now you can call printme function
my_function_name("Omnia")
my_function_name("Sayed")
my_function_name("Hamed")
```

    Omnia
    Sayed
    Hamed
    


```python
# Function definition is here
def printme( str ):
    #"This prints a passed string into this function"
    print(str)
    return;
   
   # Now you can call printme function
printme("omnia")

```

    omnia
    


```python
# Function definition is here
def printme( str ):
#"This prints a passed string into this function"
    print (str)
    return;
   # Now you can call printme function
printme( str = "My string")
```

    My string
    


```python
def printinfo( name, age ):
#"This prints a passed info into this function"
   print ("Name: ", name)
   print ("Age ", age)
   return;
 # Now you can call printinfo function
printinfo( age=50, name="Omnia" )
```

    Name:  Omnia
    Age  50
    


```python
# Function definition is here
def printinfo( name, age = 35 ):
#"This prints a passed info into this function"
   print ("Name: ", name)
   print ("Age ", age)
   return;
   # Now you can call printinfo function
printinfo( age=20, name="Omnia" )
printinfo( name="Omnia" )
```

    Name:  Omnia
    Age  20
    Name:  Omnia
    Age  35
    


```python
# Function definition is here
def printinfo( arg1, *vartuple ):
#"This prints a variable passed arguments"
   print ("Output is:")
   print (arg1)
   for var in vartuple:
    print (var)
    return;
   # Now you can call printinfo function
printinfo( 10 )
printinfo( 70, 60, 50 )
```

    Output is:
    10
    Output is:
    70
    60
    


```python

```
