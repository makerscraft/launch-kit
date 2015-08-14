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

### General overview

- Module #1, Ruby and coding basics: learn the coding basics shared by all programming languages. Variables, methods, loops, conditional statement, iterators, file parsing and regular expression. Learn the fundamentals of programming on cool challenge with your pair, also practice on real-life examples (playing with APIs, scraping HTML, storing in CSV files etc..).

- Module #2, Software architecture: learn the basics of OOP, Object-Oriented programming. OK so you know how to build cool little programs in ruby making smart stuff, congratz !! What about if you want to build a more advanced software to handle bookings in a restaurant, car rental, etc... Can you make it with a 10 000 ruby files and a bunch of methods ? No, of course, for that you need to stucture your software into different classes, each one having a precise responsability (UI, database connection, app logic, etc..). Learn how to structure your programs with objects and build your first software respecting the MVC design pattern ! That's one of the most important module of the program. If you get it, then Rails will be easy as pie.


- Module #3, Database and SQL: OK, at this stage you're a software engineer. Not only you know how to write smart algorithms but you can structure more advanced program using OOP ans start building softwares. But how do you store your data. The software you can build are smart no doubt about it! But they lack **persistence**. Let's discover relational databases, learn to get data from the DB using **SQL queries**. Grrrr, configuring the connection to the DB, writing raw SQL to extract data and reformating this data into cool ruby, this is so annoying... Is there a ruby library with classes that does the job for us ? Yeah, here comes Active Record, an [ORM](https://en.wikipedia.org/wiki/Object-relational_mapping) which is one of the core pieces of Rails.


- Module #4, Front-end: you really know a lot of stuff at this point and you can code well-structured, persistent & smart softwares. But the problem is ... the interface. It's still our good old shell. Wouldn't it be great to play with a nicer interface such as a HTML file with cool CSS design and JS animations ? Let's learn about HTML, CSS, & get the best practices in web-design (i.e. learning positioning & layout techniques + very cool recent stuff like flexbox & CSS animations). Then, let's grasp [Bootstrap](http://getbootstrap.com/), a nice CSS/JS prototyping library to save time and prototype apps very quickly. Le Wagon frontend module is very intense, and you'll quickly jump to more advanced stuff using ERB templates, SASS language and playing with the Middleman frontend framework. Very professional learnings here !

- Module #5, Javascipt: Let's learn the basics of javascript and jQuery to play with our DOM and bind events to our web pages. Then let's move to AJAX, this cool technology to make HTTP requests in Javascript. Thanks to that we will make a lot of cool stuff playing with Trello and Slack APIs, defining webhooks, playing with Facebook to get your personal data in javascript, etc, etc..

- Module #6, Rails: Time to put all our skills together and move to Rails. No big deal here, we already know most of it. We know DB and ActiveRecord, we are ruby killers and we've plaid with dozens of gems. We are frontend killers and we've already learned templating and SASS. The 1st Rails week is designed to teach you all the best practices in Rails for all the core parts of the frameworks (routing, controllers, models, views). During the 2nd week, **you'll code Airbnb in 5 days in teams** collaborating on Github ! A cool program here, you'll learn so much.

- Module #7, Projects: Time to code your own startup projects during the 2 last week and build an awesome product.



