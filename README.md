print("Menu: ")
print("1. Greetings: ")
print("2. Check Even/odd: ")
print("3. Exit: ")

choice=int(input("enter your choice: "))
if choice==1:
    name=input("enter your name:")
    print("Hello", name)
    
elif choice==2:
    num=int(input("enter your number: "))
    if num % 2 == 0:
        print(num,"is Even")
    else:
        print(num, "is Odd")
        
elif choice==3:
    print("Exiting program bye!...")
else:
    print("Invalid choice, Plz try again later")
