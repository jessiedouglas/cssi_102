# Intro to Cloud Shell + Firebase

1. [Objectives](#objectives)
2. [What We're Building](#what-were-building)
3. [Starting Code](#starting-code)
4. [Stepped Solution](#stepped-solution)
5. [Finished Code](#finished-code)
6. [Extensions for Independent Practice](#extensions-for-independent-practice)

## Objectives

- Students will use the `ls`, `cd`, `pwd`, `mkdir`, and `touch` commands to create an navigate file structures from the command line. 
- Students will acces their Firebase consoles.
- Students will start a new Firebase project that uses Realtime Database
- Students will manually add records to the Realtime Database using the console.

**Key vocabulary: Terminal, Console, Database, IDE (Integrated Development Environment)**

## What We're Building

This day is a little different, in that we're setting the stage for a multi-day project with some foundational knowledge. We won't actually be building anything today; just orienting students to two new systems. They'll learn to use the Cloud Shell terminal, and they'll also learn what Firebase is, what the Realtime Database is, and how to interact with a database for a project they create.

With that said, unless students know where we're going, it might be important to name for them where we are headed. You may wish to show them the completed week 2 projects from Thursday, or the exemplars from Friday, just so they have some sense of where this is all headed. 

## Starting Code

Note: There is no starting code today! Enjoy orienting students to Cloud Shell and to Firebase.

## Stepped Solution

### PART 1: Intro to Cloud Shell and Command Line

1. Explain where we're headed for this week. Most cohorts will be switching from Glitch (or another very easy-to-use environment) to Cloud Shell, and switching to something more difficult without rationale is never great. 

2. Share out the link to Cloud Shell. The best and fastest way to get students there is with [bit.ly/cloudshell](http://bit.ly/cloudshell) - this also circumvents the CC screen; even though GCP has paid products, Cloud Shell is free to use, and students may not be comfortable entering a credit card, or may not have one available. 

3. Point to each part of the Cloud Shell IDE and make sure students know the names of each. You will end up saying "terminal" a lot in this lesson, and you'll want students to know what that is. 

4. Discuss the importance of the terminal. One way to do this is to show a computer the early days of home computing and ask students to identify what is missing - without a mouse or a trackpad, how could one interact with a computer? 

5. One optional step to demonstrate the power of the terminal is to challenge students to a file-making race - ask them to create as many files as possible in 60 seconds (perhaps named `1.txt`, `2.txt`, etc.) to see who can use their Cloud Shell the fastest. 
    * You can probably outperform all students using the GUI with just a single touch command like `touch 1.txt 2.txt ...` or using the up arrow to repeat commands, or you can also absolutely floor them with a more sophisticated command like `touch {1..100}.txt `

6. Introduce `pwd` first, and have all students practice that first command. Discuss what it's doing, but only in brief - it will make more sense when combined with `cd` later. 

7. Introduce `ls` and `touch`, and alternate between to add a new file, then confirm that it was created. Repeat this a few times. Since the terminal doesn't feel real to students at first, you may want to show in the file explorer on the left that we've created real files. 

8. Have students practice these two commands by touching files for 5-10 songs they like. 
    * NOTE: the most common error you'll see at this point is a student who tries to add a space to a file name and inadvertently creates two files. Celebrate that error and ask them what they've learned. 

9. Demonstrate that we're getting a little disorganized, and we're probably going to need folders (or **directories**) here too. Introduce `mkdir` with something like a genre of music or an artist that students like. Then practice `cd` and `pwd` to navigate to that folder and confirm the navigation was successful. Use `touch` to create a file or two here, and use `ls` to confirm. 
    * You will likely use tab to autocomplete directories. Name this and encourage students to practice it whenever you can. 

10. Touch a file or two inside that directory, and then demonstrate `cd ..` to navigate up one level to the current directory's parent directory. Repeat this for at least one more directory, talking aloud as you perform each step. 

11. Students need time to practice these commands, especially the navigation pieces. Consider one of the below options to make space for that.
    * Have students create a set of directories that represents where they live. They might start with their country, then put their state inside that, etc. Then have them add a neighbor, a cousin, or someone else. It might even be more enjoyable for students to do this with famous places they'd like to go, or fictional places like Westeros, or The Land of Ooo.
    * Have students create a full-fledged media library. 
    * Have students play MIT's [Terminus](https://web.mit.edu/mprat/Public/web/Terminus/Web/main.html) and discuss the connections between that game and the real terminal.  

12. Close out the exploration of the terminal by giving students a chance to vent. What do they like about using the terminal? What do they dislike? What would they still like to learn?

NOTE: It's possible that some students might ask about, look up, or even already know the `mv` command. Offer them high fives if they figure it out or are willing to show it to other people, but do not focus on it for now since the joint functionality of moving and renaming can have some pretty surprising consequences. 

### PART 2: Intro to Firebase and Realtime Database


## Extensions for Independent Practice

### Mild

- At least two mild challenges
- At least two mild challenges

### Medium

- At least one medium challenge

### Spicy

- At least one spicy challenge