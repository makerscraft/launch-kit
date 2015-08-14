## 1 Batch = 1 Trello board

**A batch** is one session of the fullstack program which means one city and one period of time. Example: **batch #3 Paris, July-August 2014**.

- Each batch has a dedicated Trello board linked to the website apply form.
- This Trello board respects a canvas with pre-defined lists.
- Every list has a precise role to play, don't change it.

## First contact

When a candidate applies for a precise batch, a card is created in the **INBOX** list of the associated board, i.e. the first list. You can open the candidate's card to check his age, motivation, phone number, mail, etc...

![inbox list](images/inbox.png)
![card](images/card.png)

_Tip:_ if you're using Chrome please install the [CardCounter extension](https://chrome.google.com/webstore/detail/cardcounter-for-trello/miejdnaildjcmahbhmfngfdoficmkdhi?hl=en), very useful to see how many candidates you have in every list of the application funnel.

## Process

Here is the detailed onboarding process.

- **INBOX:** new applications.

  - **_From_ INBOX _to_ FIRST CONTACT:** check the card's content. If it's a serious candidate, **drag & drop** his card in the FIRST CONTACT list. This will **automatically** send an email to the candidate. He'll be able to book an interview directly on your agenda using [Acuity Scheduling](https://acuityscheduling.com/).

- **FIRST CONTACT:** the candidate stays in this list until he books an interview. When he does, the card **automatically** moves to the INTERVIEW list (no need to drag & drop it).

- **INTERVIEW:** in this list you'll find all your future interviewees.

  - **_From_ INTERVIEW _to_ CODECADEMY:** after the interview, if you feel that the candidate is a good fit, ask him to complete the Ruby track on Codecademy in 9/10 hours (max!). **Drag & drop** his card in the CODECADEMY list. This will **automatically** send him an email with all the instructions. This email asks for his Codecademy username. Then, our home-made bot can automatically check his score every day and detect when the candidate is done with the ruby track.

  - **_From_ INTERVIEW _to_ NO GO:** If the candidate doesn't fit, move the card to NO GO.

  - **_From_ INTERVIEW _to_ LEAD FUTUR:** If the candidate fits and wants, but can't (too short notice, family troubles ...) move the card to LEAD FUTUR.

- **CODECADEMY:** the card stays in this list until the candidate has finished the Ruby track. When he does, thanks to the bot, a green label appears on his card. If it's green, it's ready to go! You can **drag & drop** the candidate card from the CODECADEMY to the CONTRACT list and send him the contract. We use [HelloSign](https://www.hellosign.com/) for e-signatures in Paris. For your first batch, it's a bit overkill to plug HelloSign so you will have to send the contract manually by mail. We'll plug HelloSign starting with batch #2.

![codecademy list](images/codecademy.png)

- **CONTRACT:** the card stays in this list until the contract is signed.

  - **_From_ CONTRACT _to_ DEPOSIT:** When the contract is signed, click on the blue label inside the card (signed contract) and  **drag & drop** the card from CONTRACT to DEPOSIT. You can now send your IBAN and ask for the deposit (1/3 in Paris but it depends on local legislation).

- **DEPOSIT:** the card stays in this list until you receive the deposit.

  - **_From_ DEPOSIT _to_ GO:** when you receive the payment you can **drag & drop** the card in the GO list.

- **GO:** Well, this is it!

- **LEAD FUTUR:** people you should recontact later.

- **NO GO:** people you shouldn't recontact later...

_Important_: our billing solution is [Zoho Books](https://books.zoho.com). It's great and you should use it, but as for HelloSign, we will plug it to improve the automation starting with batch #2.

## Running the interview

- **Expectations**: Le Wagon is a hard and challenging program. Students will start by learning the basics of code, OOP and software architecture during the 3 first weeks. Very interesting for sure, but potentially disappointing for people with wrong expectations.. Don't accept students who just want to "build their project but don't care about code", or people who heard  that code is a hot topic and want to "know more about it". You need 300%-involved candidates, who want to learn programming because they know they'll use it in their everyday-life, to find a cool job or build tech products. People with wrong expectations will give up quickly because they'll find the program too hard and not "rewarding enough". People with strong motivations will surpass themselves every day.

- **Smartness & Passion**: Le Wagon is not reserved to Mathematics PhD. However, the program is intense and candidates should be able to grasp new concepts quickly. It's 50% about fighting-spirit & motivation, 50% about brain skills.

- **Sociability**: a lot of Le Wagon's magic comes from team spirit in each batch. For that you need sociable people, asking questions during morning talks when they don't get it, re-explaining and sharing things with their buddies. Don't neglect this part during the interview.

## Presenting the program

### Week-by-week overview

- **Module #1, Ruby and coding basics**: learn fundamental concepts shared by all programming languages: variables, methods, loops, conditional statements, iterators, regular expressions,  file parsing,... Work on cool challenges with your buddies, practice on real-life examples (playing with APIs, scraping HTML, storing data in CSV files etc..).

- **Module #2, Software architecture**: learn the basics of [OOP](https://en.wikipedia.org/wiki/Object-oriented_programming) (Object-Oriented programming). OK, you know how to build smart little programs in ruby, congrats! But wait, what if you want to build more advanced softwares like a restaurant booking platform, a car rental system, a social network, etc... Can you handle it with a 10000-lines ruby file and dozens of methods? No, of course not, for that you need to **structure your program into different objects**, each one having a precise role to play (UI, database connection, controller logic, etc..). Learn how to structure your program with objects and build your first MVC apps ! That's one of the most important modules of the program. If you embrace it, then Rails will be easy as pie.


- **Module #3, Database, SQL**: At this stage you're a software engineer. Not only you know how to write smart algorithms in ruby but you can structure your code to build more advanced programs using OOP patterns. But how do you store your data? The softwares you can build are amazing (no doubt about it) but they lack **persistence** and can't store data. Let's speak about relational databases, learn to ask data to the DB using **SQL queries**.


- **Module #4, Active Record**: Grrrr, configuring a connection to the database, writing raw SQL queries, re-formating data into cool ruby objects, all these steps are so annoying... Why can't we use a ruby library with objects doing the job for us? Here comes Active Record, an [ORM](https://en.wikipedia.org/wiki/Object-relational_mapping) to plug our ruby objects to the database. Active Record will be one of the core blocks in Rails.


- **Module #5, Front-end**: you really know a lot of stuff at this point and you can code well-structured, persistent & smart softwares. But the problem is... the interface. It's still our good old shell. Wouldn't it be great to play with a nicer interface such as a HTML file with cool CSS design and JS animations? Let's learn about HTML, CSS & get the best practices in web-design (e.g. learning positioning & layout techniques in CSS + very cool recent stuff like flexbox & CSS animations). Then, we'll teach you how to use [Bootstrap](http://getbootstrap.com/), a nice CSS/JS prototyping library to save time when prototyping web-apps. Le Wagon frontend module is very dense, and you'll quickly jump to more advanced stuff using ERB templates, SASS code and playing with Middleman, a cool frontend framework. Very professional learnings here!

- **Module #6, Javascipt**: After that, you'll learn the basics of javascript and jQuery to play with the [DOM](https://en.wikipedia.org/wiki/Document_Object_Model) and listen to events on our web pages. After that, we'll move to AJAX, this cool technology to make HTTP requests in Javascript. Thanks to that, we will work on a lot of cool challenges playing with APIs (Trello, Slack, Facebook, etc..) and defining webhooks to automate tasks.

- **Module #7, Rails**: Time to put all our skills together and move to Rails. No big deal here, we already know most of it. We know DB and ActiveRecord, we are ruby killers and we've played with dozens of gems. We already have good practices in frontend development and we've seen templating and SASS. The 1st Rails week will teach you all the best practices of the frameworks (routing, controllers, models, views). During the 2nd week, **you'll code Airbnb from scratch in 5 days**. You'll work in teams of 3 persons and you'll learn to collaborate on Github using pull requests! You'll learn a lot from this experience.

- **Module #8, Projects**: Let's code your own startup project during the 2 last week and build an awesome product.


### Typical day

- **9h00-10h30**: morning lecture by the lead teacher with lots of practical live-code to understand the concepts on real-life example.
- **10h30-12h30**: pair-programming on challenges of our home-made platform, pushing your solution to get automatic correction.
- **14h00-17h30**: End of the challenges on the platform.
-  **17h30-19h00**: "live-code session". Either a teacher or a student will pick one of the challenges of the day (or invent a new one with the teacher) and will code his own solution from scratch in front of the class on the giant projector. When doing so he has to explain at loud what he is doing and explain his methodology and the way he thinks about his program.

Every day, there's 5 to 10 different challenges with their test suite, and additional optional exercises for the most rapid students. Overall more than 300 challenges and 45 lectures of 1h30 on fundamental topics of web-development.



