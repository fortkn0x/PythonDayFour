# Day 4 Coding with Python

### Question of the day
If you had the ability to turn annoying people into an animal for a period of time each day which would you pick? What would you do with them?

### Lesson Plan
 1. Set Iniya up with an exercise
 2. Explain while loops to the two boys
 3. After break we all learn for loops and lists together

### Iniya's Exercise
Create a question-and-answer quiz game. Determine 3-5 questions (trivia, lore about your favorite TV show, etc). Make sure some questions are multiple choice while some are short answer. Use what you have learned thus far to create a fun little quiz game.
Example:

    userName = input("What is your name?")
    
    print("Hello there, " + userName + ". Welcome to Allison's 
    quiz. Today, you will be quizzed on your knowledge
    of Adventure Time.")
   
    answer1= input("What is the name of Finn the Human's 
    trusty companion?")
    
Try to consider the best way to design it. Where is there room for user error? Is it best to use multiple chioce or short answer, and why?

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
