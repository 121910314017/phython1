# phython1
n1=int(input("Enter the first number"));

n2=int(input("Enter the second number"));

n3=int(input("Enter the Third number"));

 

if(n1<n2)and(n1<n3):

    s_num=n1;

elif(n2<n1)and(n2<n3):

    s_num=n2;

else:

    s_num=n3;

 

print("the smallest of the 3 numbers is",s_num);

 

Output:::

Enter the first number2

 

Enter the second number31

 

Enter the Third number9

the smallest of the 3 numbers is 9 
 
SECOND CODE
Gcd of two numbers

def compute_gcd(x, y):

    if x > y:
        smaller = y
    else:
        smaller = x
    for i in range(1, smaller+1):
        if((x % i == 0) and (y % i == 0)):
            Gcd = i 
    return gcd

x= int(input("Enter first number: "))  
y = int(input("Enter second number: ")) 
 
 


print("The G.C.D.is", compute_hcf(num1, num2))

Output:
Enter first number:54
Enter second number:24
Gcd is 6

THIRD CODE
Lcm of two numbers

def lcm(x, y):  
   if x > y:  
       greater = x  
   else:  
       greater = y  
  while(True):  
       if((greater % x == 0) and (greater % y == 0)):  
           lcm = greater  
           break  
       greater += 1  
   return lcm  
 
 
num1 = int(input("Enter first number: "))  
num2 = int(input("Enter second number: "))  
print("The LCM of", num1,"and", num2,"is", lcm(num1, num2))  


Output::
Enter first number: 3
Enter second number:4
The LCM of 3 and 4 is 12

FOURTH CODE
Lcm and gcd of three numbers



