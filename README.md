# HelloSally
**Purpose:** A program to help users find an activity to do when they are bored!

### Inspiration
In high school, I participated in girls who code and took my first programming class with AP Computer Science! In these classroom settings, I learned my first programming language: Java. This class and extracurricular taught me that programming is truly a versatile skill and it can create the most complex or simplest programs. In order to help my senior-high-schooler-self understand it better, I did a small programming exercise in my freetime to tackle a problem in my life and try to solve it. I found myself bored oftentimes and decided to create a program that helped users figure out what to do when they are bored. Even though it is relatively a simple program with simple logic, I found it to be a lot of fun and really introduce me to the idea of coming up with my own solutions!

### What I learned
In this program, I implemented an ArrayList for the first time and practiced taking input from the user using Scanner objects. I practiced handling input errors and implemented a logic that allowed the user to keep retrying until they inputted a statement that can be correctly handled. I also practiced creating a randomized output by making the program select a random activity from the list using an instant of the Random class:

                 Random random = new Random();
                 int rand = random.nextInt(activities.size()-1);
                 
                 String chosenAct = activities.get(rand);
                 activities.remove(rand);
                 
The activity gets removed from the list so if the user chooses to restart, they won't get the same activity suggested to them twice.

### What I would differently today
If I could redesign this program, I would want to implement the activities by organizing them into sub-categories. I would want to make the beginning input section to be more complex by allowing the user to select from categories of activities or to picking a random actvitiy across all categories to better fit the needs of the user. I also would want to correct input handling better and handle what happens if they run out of activities to pick from as I realized I didn't add a handling to account for if all activities get removed from the list. 
