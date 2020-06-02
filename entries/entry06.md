# Entry 6
##### 6/2/20

First thing I did was make sure that I **accomplished an MVP**. I did this by choosing to go a more simple route. Before doing my mvp I was trying to be fancy and make a calendar from complete scratch. What was worse is that I was following tutorials without understanding what I actually had to do. I picked the wrong project to initialize (many tutorials did not use swiftUI which is why my code kept getting errors in the first few days of the project).

I managed to find an easier option and that easy option started with [this video](https://youtu.be/5Jwlet8L84w).

The work seemed simple and I did not need to update the dates in a complicated way. The calendar was given to you and now all that is needed is personal customization and features. They had a reference sheet at: [FSCalendar Cocoapods](https://cocoapods.org/pods/FSCalendar).

Once I finished setting up the calendar I began to vigorously search how to add events and save them on the calendar.
After doing some research I realized that I needed an MVP and stopped trying to get fancy. My MVP is a working calendar with accurate dates that allows you to see the months per year. Of course I also made sure that the user was capable of making an event. The only problem was keeping the event stored and displayed on the calendar.

---
#### How did I manage to add the “add event” feature?

What I did was add another viewcontroller.

![viewcontroller](images/viewcontroller.png)

Once I added the new view controller I added buttons that take you to that page.

Swift has easy and simple controls if you take the time to learn them. In order to make sure that the buttons go to the second page and back, we click option and drag to the mouse to the second page. This tells the program that the button should open/lead to the page that it got connected to.

After making the buttons and setting up the event page, this was the final product:
![storyboard](images/Storyboard.png)

---

During these past few days my main focus was trying to figure out how to save an event to the calendar itself. I did not manage to accomplish this, but knowing that I do have an MVP is reassuring.

I would go on side tangents learning other things that can help my app be better. I learned how to get the keyboard to disappear when the user presses return or when the user presses another place on the screen.
I followed this [tutorial](https://youtu.be/l-Uup2lKw1Y).

I accidentally learned how to connect the calendar app with the main calendar that the iphone has pre-installed.  It was definitely interesting to learn.
You need to get permission from the user in order to access the calendar. When learning this I was thinking maybe instead of saving the events on the calendar app itself, perhaps it is better to save the event in the main calendar app. It would have been a temporary solution. However when I continued my research I figured that I should not take that approach. The whole point of the calendar is to make an event and save it in that calendar, on the calendar that Apple pre-installed for us. It would make the point of the app pointless.

I followed this [tutorial](https://youtu.be/sSFzcvvs4Oc).

In the end I did not manage to achieve my goal, but I did learn other useful programming tips for swift specifically. Even if I did not manage to do so in the time frame of this project I will definitely learn to do so in the future. This was honestly a fun project to do, and it is what we learn that stays with us more than what we accomplish.

**Final Project**

![calendar01](images/calendar01.png)

![calendar02](images/calendar02.png)

![code](images/code.png)

![Storyboard](images/Storyboard.png)

![viewcontroller](images/viewcontroller.png)

[Previous](entry05.md) | [Next](entry07.md)

[Home](../README.md)