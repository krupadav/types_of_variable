# types_of_variable:
Types of Variable:
Global var.
Local Var.
Non local
1.)Global variable:The variable which is available anywhere throughout the program and we declare this variable outside the function at the same indent level
Example: global variable
x = 200
def test():
   Global variable:
The variable which is available anywhere throughout the program
and we declare this variable outside the function
at the same indent level
Example:
# global variable
x = 200
def test():
    print('Inside:',x) # access x inside a function
print('Outside:',x) # access x outside a function
test()
    print('Inside:',x)
2.)Local Variable:The variable which is declared inside a function called as Local var This var. wil nt be accessible outside the function Local var is having a restricted scope means it will be accessible only to that function or within the function outside we  cant access. local var is available anywhere INSIDE a function
nt outside. If local var. we want outside then use return with calling function u wil get it.
Nonlocal var: is associated with nested function
def politics():
    cm = 'UT'
    def S_sena():
        nonlocal cm
        cm = 'DF'
        print(cm)
    S_sena()
    #print(cm)
    return cm
cm = politics()
print(cm)
