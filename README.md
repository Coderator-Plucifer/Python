# Python
#to check whether a number is armstrong or not

num=eval(input("Enter the number: "))
num1=len(str(num))
temp=num
s=0
while temp!=0:
    rem=temp%10
    s=s+rem**num1
    temp=temp//10
if(s==num):
    print("The number is armstrong:",num)
else:
    print("The number isn't armstrong:",num)
