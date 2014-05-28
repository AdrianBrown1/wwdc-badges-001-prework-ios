---
  tags: arrays, iteration, methods
  languages: objc
---

# Badges and Schedules

### Skills: blocks, loops?

## Instructions

In this lab you'll be learning how to iterate through an array and output the results in different ways. Your code will go in the "conference_badges.rb" file and you can run the test suite using the `rspec` command.

You're hosting a conference and need to print badges for the speakers. Each badge should say: "Hello, my name is _____."

1. Write a badge_maker method that will create and return this message, given a person's name.
ex:

    ```bash
    badge_maker("Arel")
    => "Hello, my name is Arel."
    ```

2. The list of speakers for your conference has been finalized. Your conference speakers are: `Edsger, Ada, Charles, Alan, Grace, Linus and Matz.` How you scored these luminaries is beyond me, but way to go! Now you'll want to get their badges printed. 
  
  a. Store the list of speaker names outside your method so you can send it to the printer. 
  
  b. Write a batch_badge_creator method that takes a list of names as an argument and return a list of badge messages. Hint: Use the variable you created in part a.

3. You just realized that you also need to give each speaker a room assignment. Write a method called assign_rooms that takes the list of speakers that will assign each speaker to a room. Make sure that each room only has one speaker.
  * You have rooms 1-7. 
  * return a list of room assignments in the form of: "Hello, _____! You'll be assigned to room _____!"

4. Now you have to tell the printer what to print. Create a method called printer that will output the results of the badge_creator method and the assign_rooms method to the screen.


## Resources
* [Programming Ruby 1.9](http://books.flatironschool.com/books/11) - [2.2 Some Basic Ruby](http://books.flatironschool.com/books/11), page 33
* [Programming Ruby 1.9](http://books.flatironschool.com/books/11) - [2.3 Arrays and Hashes](http://books.flatironschool.com/books/11), page 36
* [Programming Ruby 1.9](http://books.flatironschool.com/books/11) - [2.7 Blocks and Iterators](http://books.flatironschool.com/books/11), page 41
