# NotePlan-Dashboard

[NotePlan](https://noteplan.co) is great! It's an iOS and macOS app to plan your day, take notes, and keep track of everything in your calendar. The developer describes NotePlan as a digital [Bullet Journal](https://www.bulletjournal.com). 

I use NotePlan daily and in doing so discovered I was much more productive when I wasn't continually opening the app to focus on my next task. I envisioned having all the information available in NotePlan visible on my desktop. And since NotePlan keeps your information as plain text files in iCloud, we can use GeekTool script modules to create a dynamic dashboard.

The geeklets I've provided add three modules to your desktop. I collectivley refer to these modules as NotePlan Dashboard. The modules are: Calendar, Recent, and Tasks.

**Calendar** displays current and next month calendars and a productivity "meter" to visualize your productivity over the past week.

**Recent** displays your active, waiting, or delayed work based on time. This geeklet help you keeps all your notes in mind which lets you get caught up on projects you've forgotten about.

**Tasks** shows you whats due today and iCal events and reminders.

## Set Up

Download and double-click each geeklet to install (don't forget you need [GeekTool](https://www.tynsoe.org/v2/geektool/) installed).

You'll need to modify your NotePlan directory in each geeklet. Simply open GeekTool and select each module one at a time. In the Properties window, select the **...** next to Command. Underneath the Changelog you'll find the custom options. Replace the *XXX* in the **userDir** value to your user name.

**Calendar**
/Users/XXX/Library/Mobile\ Documents/iCloud\~co\~noteplan\~NotePlan/Documents/Calendar

**Recent**
/Users/XXX/Library/Mobile\ Documents/iCloud\~co\~noteplan\~NotePlan/Documents/Notes

**Tasks**
/Users/XXX/Library/Mobile\ Documents/iCloud\~co\~noteplan\~NotePlan/Documents/Calendar

*See here for [help locating the NotePlan directory](https://github.com/biznachio/NotePlan-Dashboard/blob/master/How%20to%20locate%20NotePlan%20directory.md)on your Mac.*

Finally, download and install [iCalBuddy](https://hasseg.org/icalBuddy/) in its default installation location.

## Customization Options

NotePlan Dashboard module have limited customization options.

### Change the Default Todo/List Mark

NotePlan Dashboard's default todo mark is *- [ ]*. Some users prefer NotePlan to recognize * or - as tasks without the brackets. If you want the NotePlan Dashboard Tasks module to recognize * or - you'll need to update the custom options in the Tasks geeklet.

Simply open GeekTool and select the Tasks module. In the Properties window, select the **...** next to Command. Underneath the Changelog you'll find the custom options. Set **todoMark** value to your preferred mark. 

The options are: 
- Default (''): todoMark=''
- Asterik ('\*'): todoMark='\*'
- Dash ('\-'): todoMark='\-'

### Hide Calendars 

You can hide certain calendars so they don't appear in Events.

Simply open GeekTool and select the Tasks module. In the Properties window, select the **...** next to Command. Underneath the Changelog you'll find the custom options. Set **excludedCals** value to the name or names of the calendars you wish to hide. Separate each calendar with a comma (,) and no space.

- excludedCals='Family,Personal'

I hope you enjoy! Feel free to make changes to meet your needs!
