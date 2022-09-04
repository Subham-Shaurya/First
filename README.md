#Python program to find out grades on the basis of marks of each subject
english = int(input("English:"))
science = int(input("Science:"))
hindi = int(input("Hindi:"))
maths = int(input("Mathematics:"))
sum = english + science + hindi + maths
print(sum)
p = (sum/400)*100
if p> 90:
    print("A++")
elif p>80 and p<=90:
    print("A+")
elif p>70 and p<=80:
    print("A")
elif p>60 and p<=70:
    print("B")
else:
    print("Fail")
