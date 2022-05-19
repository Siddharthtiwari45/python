# python
s={1:{"name":"","age":0},2:{"name":"","age":0},3:{"name":"","age":0}}


i=1

while(i<=len(s)):
    s[i]['name']=input("enter your name:")
    s[i]['age']=int(input("enter your age:"))
    i=i+1
print(s)



<!-- standard data type:standard data type of task based on dynamic memory type of task.
these are of following types:
1.List
2.Set
3.Tuple
4.Dictionary

1.List:List is a standard data type,this type of variable allocate memory ,is in insertion order and we can store duplicate element also.List based on indexing.
indexing start from 0 but length length start 1.
List is denote by(create by) list() or [ ] square bracket.

syntax:

library=["book1","book2","book2"]

Note:
inside a list,we can store multiple type of data.
Example:
we store user information: -->

<!-- user=["priya",21,5.2,True]

all data that contain inside user are based on indexing.
user[0]    ->its return priya
user[1]    ->its return 21


len()    :len method is use for access length of data.
lenght start from 1.

len("data")    :4
but we can't access integer and float type of data length.

Example:
WAP to print one by one element based on List.


Note:
for loop is based on iteration concept.
iteration concept means one by one process.
first access and then move on next.


iterator concept:
in python programming,iterator concept perform by __iter__() and __next__().

by default for loop perform these task.
 -->
users=["Ram","Seeta","Geeta","Deepa"]

myiter=__iter__(users)

print(__next__(myiter))    ->Ram

<!-- list are of following methods:
1.append()    :append method is use for add data at the end of list.

syntax:

listvariable.append(data)

Q1.WAP to add 2 name in a list.

Q2.WAP to add two list and create new list. -->

a=["abcd","12345"]
b=["deepak","amit","reena","meena"]

c=a+b

print(c)

<!-- ----------------------------------------------------------------- -->
class Record:
    def addNum(self):
        a=int(input("enter first number:"))
        b=int(input("enter second number:"))
        print("Addition",a+b)
    def subNum(self):
        a=int(input("enter first number:"))
        b=int(input("enter second number:"))
        print("Subtraction",a-b)

r=Record()

i=input("enter + for Add\nenter - for subtract\n")
if(i=="+"):
    r.addNum()
elif(i=="-"):
    r.subNum()
else:
    print("sorry")





class User:
    def firstname(self):
        f=input("enter first name:")
        print("First name is",f)

    def lastname(self):
        l=input("enter last name:")
        print("LAst name is",l)

u=User()
u.firstname()
u.lastname()
