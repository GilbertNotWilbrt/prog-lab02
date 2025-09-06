Project: naive-ticket-machine
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling
   Pearson Education

It is discussed in chapter 2.

Purpose of project: To illustrate the basics of fields, constructors, and methods.
How to start this project: Create one or more TicketMachine objects.


QUESTIONS

#2 The balance is 0.

#3 It prints out 1 ticket, but it takes away all the money without giving me
change/refund.

#5 The difference is that it states that it is a different int value than
the original ticket machine I originally made.

#6

#7 As Java reads code from left to right, it wouldn't recognize public being first
which it has to be as public declares it to be there.

#8 Yes it is possible.

#9 No it is not possible to put public only.

#10 The constructor is public  TicketMachine(int cost) 

#11 The two features are that it doesn' have a return and ----- ANSWER LATER

#12
private int count; --> int
private Student representative; --> Student
private Server host; --> Server

#13
alive
tutor
game

#14
Student
Server

Person
Game

#15 Yes it does matter in which order, other orders aren't possible as
Java reads left to right.

#16 
Yes, it is always necessary to hav ea semicolon at the end of a field
declaration.

#17 private int status

#18
It belongs to the class Student

#19
2 paramaters, being String and double.

#20

#21
public Pet (String petsName){
    Name = getName
}

#22

#23

#24
"How much money is currently in the machine?"

#25
Its name can be different than its associated fild.

#26

#27
It says "missing return statement"

#28
They have different types
getPrice: int
printTicket: void

#29
No they don't have return statements as they are storing a value and 
that value is being stored into another statement so it can be printed 
elsewhere

#30 
The original value of balance was 0
I put 1000 in insertMoney and the new value of balance is now 1000.

#31
increaseScore

#32
It is a mutator, as when you call it, it changes the state of the Student
object by increasing the number of credits inside.  
Ex Student starts with 0 creds, after calling addCredits(10), student now has 10 credits

#33

#34 
public void setAge(int currentAge) {
    age = currentAge;
}

35.
public void setAlive(boolean aliveStatus){
    alive = aliveStatus;
}

36.

37. 
My cat has green eyes.

38. 
 public void insertMoney(int amount)
    {
        balance = balance + amount;
    }
I also put this in the TicketMachine itself as I didn't know
whether you wanted me to answer it here or on the source code

39.
It would literally print # price cents everytime, it wouldn't 
return the price of the ticket it would literaly put price.

40.
It would also print the same thing as question 39.

41.

public void showPrice(){
 System.out.println("The price of a ticket is " + price + " cents.");
}

42.
No they are different, as their TicketMachine prices are different they
display the price of the ticket according to its ticket price

43.
It prints the same output as before. %d is replace by the int value of price,
%n moves to a new line, like println.

44.
The value of price is fixed at 1000 despite trying to change the initial value of it
when prompted to.

45.
I did it on the source code and the one with a set price, its price doesn't change
and the other one I'm able to set a value of my choosing.

46.
public void empty()
{
    total = 0;
}

No paramaters needed as it only affects the total field.
And it is a mutator, as it only changes the state of total to zero.
