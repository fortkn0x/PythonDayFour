# Day 4 Coding with Python

### Question of the day
If you had the ability to turn annoying people into an animal for a period of time each day which would you pick? What would you do with them?

### Lesson Plan
 1. Set Iniya up with an exercise
 2. Explain while loops to the two boys
 3. After break we all learn for loops and lists together

### Iniya's Exercise
Create a program that determines the average of a collection of numbers. Use a while loop. Let Iniya figure it out and design it herself, but ideally it would look like this:

Ask the user how many numbers are in the collection. Then, given n numbers, ask the user to input the next number n times. Determine the sum of all numbers in this same loop.

After exiting the loop, divide the sum by n to get the average.

### While Loops for Daniel, Alex, Iniya
The three pieces needed for a while loop:
1. start variable
2. condition until stop
3. Step operation
`
	x=0 #start variable
	while x<10: #stop condition 
	    print(x)
	    x=x+1 #step operation`
   
Ask them to write a while loop that iterates from 0 to 50 and goes up by ten so it prints out: 0, 10, 20, 30, 40, 50. Have them identify the start variable, the stop condition, and the step operation.

After they complete that, give them a fun while loop to do together. Maybe they can build a story together. Have Iniya help out so she can explain some of the more complicated aspects.

    user = input("Please input a sentence")
    story = user;
    while user != "stop":
	    print(user)
	    user=input("Continue the story.")
	    story+=user;
	print(story)


If this is too hard, have them construct a while loop that prints out their favorite word 5 times. Like this:

Luna

Luna Luna

Luna Luna Luna

Luna Luna Luna Luna

Luna Luna Luna Luna Luna

### Lists and For Loops
What if I want to hold a collection of data? What if I want a *list* of names, a *list* of numbers, a *list* of my favorite books? We would use a LIST in python! Show some examples of lists. 

    digits = [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]
    opposite = [True, False, True, False, True, False]
    groceries = ["Milk", "Eggs", "Butter", "String cheese"]


Lists are a collection of items. Let's make a list of the items we want to have on a desert island. Have everyone share a repl so we can all look at the same screen.

`desert = [""]`

1. use len(list) to get length
2. show index notation-- starts counting from 0
3. show for i in range() if we get that far!
