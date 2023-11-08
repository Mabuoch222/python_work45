print("1:check if n is a prime")
print("2:generate prime less than n")
print("3:genrate first n prime numbers")

choice=int(input("enter your choice:"))
                 
#check if n is a prime
if choice == 1:
    num = int(input("enter your number:-"))
    a= False
    if num > 1:
        for i in range(2, num):
            if (num % i) == 0:
                a= True       
            break
    if a:
        print(num, "is not a prime number")
    else:
        print(num, "is a prime number")

#generate prime number less than n
elif choice ==2:
    list1=[]    
    print("The Prime Numbers less then your are: ")
    for j in range(0, num + 1):
        if j > 1:
            for i in range(2, j):
                if (j % i) == 0:
                    break
                else:
                    list1.append(j)
                    print(list1)            

#for generating first n prime numbers
elif choice==3:
    l = True
while l == True: 
    n = int(input("Enter the number of primes you want: "))
    i = int(2)
    while n != 0:
        for j in range(2, i):
            if i % j == 0:
                break
        else:
            print(i)
            n -= 1
        i += 1
