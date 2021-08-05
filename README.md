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

### While Loops for Daniel and Alex
Ask Alex if he wants to work with Daniel again. Show them this simple while loop that iterates from 0 to 10.

    x=0
    while x<10:
	    print(x)
	    x=x+1
Ask them to write a while loop that iterates from 0 to 50 and goes up by ten so it prints out: 0, 10, 20, 30, 40, 50.

After they complete that, give them a fun while loop to do together. Maybe they can build a story together.

    user = input("Please input a sentence")
    story = user;
    while user != "stop":
	    print(user)
	    user=input("Continue the story.")
	    story+=user;
	print(story)
