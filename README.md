# Backtimer Alexa Skill
Alexa skill for backtiming a number of related activities

Will offer two modes:

1. Backtime a task 
2. Backtime a meal

The process is essentially the same for both modes; just the terminology changes

## User Interaction

1.  "Alexa, ask backtimer to plan a task/meal"
2.       "Ok. What is your first activity/ingredient?"
3.  "xyz"
4.       "And how long will xyz take to complete/cook?"
5.  "nn minutes"
6.       "Ok. Would you like to add another activity/ingredient?"
7.  "yes" 
8.       "What is your next activity/ingredient?"
9.  "abc"
10.       "And how long will xyz take to complete/cook?"
11.  "mm minutes"
12.       "Ok. Would you like to add another activity/ingredient?"
13.  "no"
14.       "Ok. The longest activity to complete/ingredient to cook is xyz that will take nn minutes."
          "After starting xyz you should wait nn minutes and then start abc"
          "If you follow these instructions then everything should be completed at the same time."
          "Would you like me to set reminders for the start of each activity?"
15.  "yes"
16.       "Ok. I will set r reminders for you"
          "xyz, in nn minutes"
          "abc, in nn-mm minutes"
          "Is that ok?"
17.  "yes" 
18.       "Ok. I have saved this meal plan for you. When you are ready to start, say Alexa ask backtimer to start xyz"
...
19.  "Alexa, ask backtimer to start xyz"
20.       "Ok. I have set r reminders for you"
          "xyz, in nn minutes"
          "abc, in nn-mm minutes"
          "Good luck! And thanks for using Backtimer."
 

