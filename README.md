# python
s={1:{"name":"","age":0},2:{"name":"","age":0},3:{"name":"","age":0}}


i=1

while(i<=len(s)):
    s[i]['name']=input("enter your name:")
    s[i]['age']=int(input("enter your age:"))
    i=i+1
print(s)
