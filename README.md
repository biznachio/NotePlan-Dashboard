# NotePlan-Tools

[NotePlan](https://noteplan.co) is great! It's a iOS and macOS app to plan your day, take notes, and keep track of everything in your calendar. The developer describes NotePlan as a digital [Bullet Journal](https://www.bulletjournal.com). 

I use NotePlan every day and in doing so discovered I was much more productive when I wasn't continually opening the app to focus on my next task. I envisioned having all the information available in NotePlan visible on the desktop. And since NotePlan keeps your information as plain text files in iCloud, we can use GeekTool script modules to create a dynamic dashboard.

The geeklets I've provided add three modules to your desktop. I call these modules NotePlan Dashboard. The three modules are: Calendar, Recent, and Tasks.

**Calendar** displays current and next month calendars and a productivity "meter" to visualize your productivity over the past week.

**Recent** displays your active, waiting, or delayed work based on time. This geeklet keeps all your notes in mind and lets you get caught up on projects you've forgotten about.

**Tasks** shows you whats due today.

Users will need to modified their NotePlan directory in the geeklet command palette. In each geeklet find the line "cd /Users/**XXX**/Library/Mobile\ Documents/iCloud\~co\~noteplan\~NotePlan/Documents/(Calendar or Notes)" and change the XXX to your user name. Make sure you check out the other prerequisites below for all the functionality.

You will need a install the following apps to get the NotePlan Dashboard geeklets to work.
1. [GeekTool](https://www.tynsoe.org/v2/geektool/)
2. [iCalBuddy](https://hasseg.org/icalBuddy/)

I hope you enjoy! Feel free to make changes to meet your needs!
