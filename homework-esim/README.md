# Home/Work eSIM
Allows to disable and enable a secondary eSIM when arriving at/leaving a specified (work?) location.

Created [per request](https://www.reddit.com/r/shortcuts/s/fvK6DEuofb) for u/throwingawayonedalo

# Installation
1. You need to download two shortcuts.
     - [Download "Enable work eSIM"](<Enable work eSIM.shortcut?raw=1>)
     - [Download "Disable work eSIM"](<Disable work eSIM.shortcut?raw=1>)

2. Set your eSIM in the shortcut
     - [Edit "Enable work eSIM"](https://doggopwn.github.io/redirect?loc=shortcuts://open-shortcut?name=Enable%20%work%eSIM)
       - In the first block, set your work eSIM.
       - In the following blocks, set your home eSIM.
     -   [Edit "Disable work eSIM"](https://doggopwn.github.io/redirect?loc=shortcuts://open-shortcut?name=Disable%20%work%eSIM)
       - Do the exact same

 3. Create automations to trigger automatically
     1. Open the [automations tab](https://doggopwn.github.io/redirect?loc=shortcuts://automations)
     2. Create a "When I Arrive" automation, and make it run "Enable work eSIM"
     3. Create a "When I Leave" automation, and make it run "Disable work eSIM"
   
 4. You're done!
