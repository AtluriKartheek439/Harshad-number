# Harshad-number
num=int(input("Enter the number:"))
temp=num
sum=0
while temp>0:
    digit=temp%10
    sum+=digit
    temp//=10
print("Latest value of sum:",sum)
print("Latest value of temp:",temp)
if num%sum==0:
    print(num,"is a Harshad number")
else:
    print(num,"is not a Harshad number")
