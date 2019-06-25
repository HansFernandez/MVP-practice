_created & maintained by [@HansFernandez](https://www.linkedin.com/in/hansfernandez/)

## Exploring Product Ownership through exercises

Using [Protobot](http://molly.is/experimenting/protobot/#)  (a random generator for product ideas) I will attempt to create User Stories, MVP and Epics for generated topic. 
The goal is to apply concepts learned for Product Owner responsbilities, build creative energy and recieve any feedback or coaching oppurtunities that exist.


### Contents
- [How you can help](#how-you-can-help)
- [Exercises](#Exercises)
  - [Number 1](#Number-1)
  - [Number 2](#Number-2)


### How you can help

* Get a [GitHub account](http://github.com).
* Watch or Star this repo. This may help me achieve some visibility.
* You can interact with the text and the rest directly from here via commits
* Create your own version: once forked, you can use git 
  - (check out this manual http://wiki.freegeek.org/index.php/Git_for_dummies ) to
  branch and evolve the story in whichever way you want.
* If you think there is a worthwhile addition do a Pull Request.
  
  

### Current Approach (Open to Suggestions/Recommendations)


**Task**: 
Use [Protobot](http://molly.is/experimenting/protobot/#) to generate idea 

**Suggested Approach** / (Open to recommendations)


   Step 1: Write down all the user stories which your product may end up having. Each user story must end with the user capturing value from the product.

   Step 2: Prioritize the user stories according to value and difficulty of execution. Apply and explain Prioritization Model.

   Step 3: According to the user story selected (or stories) drill down to understand which features you MUST develop. That is going to be the MVP.
   
## Exercises 

### Number 1:    

       Protobot Generation: Design a mop that will help you find a date 


#### Step 1 Build User Stories:
       As a < type of user >, I want < some goal > so that < some reason >.
       
       As a user I want to mop floors 
       As a user I want to wax floors
       As a user I want different mop head attachments 
       As a user I want to upload shift schedule so that date is arranged [before/after] work.
       As a user I want to interface with largest dating site today (We'll assume eHarmony)
       As a user I want to interface with existing dating sites
       As a user I want search for popular events in my area
       As a user I want to schedule date for nearby bar/club
       As a user I want to be geo-verified and matched with people around 20 miles
       As a user I want voice activated appointment setting
       As a user I want to date other mop members and non-mop members
       As a user I want vibrating notifications to alert me of matches 
       As a user I want settings to elevate my seriousness in dating (one time hookups to marriage)
       As a user I want settings to control straight, LGBTQ etc
       As a user I want to take and upload photos from my mop
       As a user I want to confirm or deny date suggested.




#### Step 2 Priortize 
1. As a user I want to mop floors 
2. As a user I want to interface with existing dating sites
3. As a user I want to be geo-verified and matched with people around 20 miles
4. As a user I want to confirm or deny date suggested.
5. As a user I want vibrating notifications to alert me of matches 
6. As a user I want settings to elevate my seriousness in dating (one time hookups to marriage)
7. As a user I want settings to control straight, LGBTQ etc
8. As a user I want to upload shift schedule so that date is arranged [before/after] work.
9. As a user I want to schedule date for nearby bar/club
10. As a user I want search for popular events in my area
11. As a user I want voice activated appointment setting
12. As a user I want to wax floors
13. As a user I want different mop head attachments 
14. As a user I want to take and upload photos from my mop
15. As a user I want to date other mop members and non-mop members
16. As a user I want to interface with largest dating site today (We'll assume eHarmony)



#### Step 3 Create 

MVP will have first 3 items as a MVP

1. As a user I want to mop floors 
2. As a user I want to interface with existing dating sites
3. As a user I want to be geo-verified and matched with people around 20 miles

The mop will have standard stick and cotton bottom to mop floors. It will interface with the simplest API for a nearby dating site we can find and will use the location of mop use for deciding matches. Most of the match making will defer to local dating site's algorithm.

### Number 2:

Took different approach in this workout to explore persona
 approach.
 
       Protobot Generation: Create bank ATM backlog 




#### Identify Personas:
* 29 – Male – IT – Median Income—Parent on the go
* 29 – Female—Spouse—Parent on the go

#### User Stories and Acceptance Criteria: 

1.	As a bank customer I want to use my debit card to withdraw money
 * System correctly interprets debit card magnet stripe
 * System rejects incorrectly formatted or other cards (other bank, credit card, library card)
 * System displays an error message when it rejects a card
 * System executes money dispense command from machine to physical withdrawal area
 * System logs out
2.	As a bank customer I want to withdraw from my checking account
 * System accesses only checking account
 * System alerts customer transactions will only occur on checking account
3.	Given that a spouse has authorization to withdraw from joint account when a spouse uses their debit card then they should have ability to withdraw money
 * System correctly alternative card as provided by bank for account access
 * System rejects incorrectly formatted or other cards (other bank, credit card, library card)
 * System displays an error message when it rejects a card
4.	In order to understand options I want to see my starting balance
 * After login system will display total prior to any transaction
5.	As a bank customer I want to secure my transaction with a numeric pin code
 * System accepts correct 4 digit pin
 * System rejects incorrect 4 digit pin
 * System displays confirmation of correct pin
 * System displays rejection notification of incorrect pin


6.	Given that a withdrawal was made and account balance has changed then I should have a display of the new total
 * System subtracts withdrawal amount from beginning total
 * System displays new total
7.	Given that a withdrawal was made when transaction is complete then the customer should receive a hard copy receipt
 * When system recognizes withdrawal it will ask customer if transaction is complete
 * System will allow user to reply with yes or no
 * If yes, system will execute print receipt command 
 * If no, program will allow for more withdrawals
8.	As a user I want to be prompted for paper or email receipt so that we can be environmentally conscious 
 * When system recognizes withdrawal it will ask customer if transaction is complete
 * System will allow user to reply with yes or no
 * System will then ask if email or print is desired
 * If email, system will request email address
 * If yes, system will execute print receipt command 
 
9.	In order to feel secure  I want to swipe my debit card through machine so that I retain my physical card (card not inside machine)
 * System will use magstripe swipe technology
 * System will tell customer to swipe and remove card quickly
 * System will confirm swipe was effective
 * If swipe was too fast system will display message
 * If swipe fails system will display message

10.	As a bank customer I want to select amount to be withdrawn from balance
 * SPIKE: Take one day to research most frequently used denominations
 * System will display 6 denominations in intervals based on spike results
 * 	When selected interval denomination will be subtracted from balance

 #### MVP

 1. As a bank customer I want to use my debit card to withdraw money
    * System correctly interprets debit card magnet stripe
    * System rejects incorrectly formatted or other cards (other bank, credit card, library card)
    * System displays an error message when it rejects a card
    * If valid swipe, System executes money dispense command from machine to physical withdrawal area for $20
    * System logs out
