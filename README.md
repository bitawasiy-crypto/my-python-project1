number = int(input("enter your number:"))
i=2
if number>1:
    while i<number:
        if number%i==0:
            print(number,"--number is not prime:---")
            break
        i+=1
    else:
        print(number,"prime")
else:
        print(number," not prime!")
