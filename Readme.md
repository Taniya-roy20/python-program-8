# Program 8: WAP to create a list of only the even integer appearing in the input list(may have elements of other types) using for loop and list comprehension.
def cubes():
<br>
    newlist=[]
    <br>
    number=[1,2,3,4,5,6,"seven"]
    <br>
   for i in number:
        if type(i)==int:
        <br>
          if i % 2==0:
          <br>
                newlist.append(i**3)
                <br>
    print(newlist)
    <br>
cubes()

![image](https://github.com/user-attachments/assets/793c5f14-0b11-477b-b6e3-2a0d0c646817)
