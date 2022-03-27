# Work-Day-Scheduler

Our assignment this week was to create a daily planner / work day scheduler, using the given html and css files provided for us. The main function of the daily planner was to be able to type in the event and be able to save it into the allotted time. When the user refreshes the planner, the events that they have previously saved should still be present unless deleted by the user.

Our initial task was to display the current day and date when the page is opened. I tried adding the time when the page is opened, but I couldn't figure out how to have a running clock.

![Website-Date](https://user-images.githubusercontent.com/98381243/160270416-ebba6b20-6536-44ae-9afd-f25d182e6676.png)

![VSC-Date](https://user-images.githubusercontent.com/98381243/160270426-a919d0d0-2e89-4979-9251-46bba0ca285b.png)

The next task was to create timeblocks for standard business hours (9am - 5pm) and to colorise the blocks based on the current time. The current hours block would be red, hours that have past would be grey and hours that haven't arrived yet would be green.

![Website-Timeblocks](https://user-images.githubusercontent.com/98381243/160270589-f6503c94-799e-4efb-9f2a-477e0fc7325c.png)



![VSC-ColorTimeBlocks](https://user-images.githubusercontent.com/98381243/160271010-140dd461-0c2c-4706-a622-2544ad64f77b.png)

![VSC-Timeblocks](https://user-images.githubusercontent.com/98381243/160270596-1d6f6fc9-1e5f-439a-9130-4bcf05a7a761.png)

The next task was to enable the user to enter an event into the timeblock of their choosing. In the above image, this was done by creating a text area that we've named description and choose the appropriate size for the text area. 

To allow the user to save their task into the daily planner, a save button is created and when clicked, the text for that event is saved into the local storage. By doing this, when the user refreshes the page, the saved event will persist. In the above image, we've created the floppy disk save icon by using the code <i class="fas fa-save">

![VSC-SaveBtn](https://user-images.githubusercontent.com/98381243/160270890-b400f52a-f829-443f-862a-72b6373d90a8.png)
  
![VSC-LocalStorage](https://user-images.githubusercontent.com/98381243/160270905-33dab44b-4e8a-4a8e-9727-6517aa11095d.png)
  
In regards to the local storage coding, I believe there's a simplier code that we can be used to target each hour as a whole but I wasn't able to figure out how to do that. Instead, I've had to target each hour individually so the coding isn't as clean as it can be. 
  
Link to the finished product: https://androneus14.github.io/Work-Day-Scheduler/
