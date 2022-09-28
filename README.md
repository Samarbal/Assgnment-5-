# Assgnment-5-
print (" 1 Addition ")
print (" 2 Subtraction ")
print (" 3 Multipliction ")
print (" 4 Division ")

choice = input (' Enter your choice :')

number1 = float(input("Enter the first number:"))
number2= float(input("Enter the sconed number :"))

if choice == "1":
    print ( number1 , " + ", number2 ," = ", (number1 + number2))
elif choice == "2"  :
    print ( number1 , " _", number2 , " = ", ( number1- number2))
elif choice == "3":
    print ( number1 , " *", number2, " =",(number1*number2) )
elif choice == "4":
    if number2 == 0 :
        print ("Divide by 0 Error ")
    else : print ( number1 ,"/", number2, '=', ( number1/number2) )
