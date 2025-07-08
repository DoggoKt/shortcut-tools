# Home/Work eSIM
Allows to disable and enable a secondary eSIM when arriving at/leaving a specified (work?) location.

Created [per request](https://www.reddit.com/r/shortcuts/s/fvK6DEuofb) for u/throwingawayonedalo

# Installation
1. You need to download two shortcuts.
     - [Download "Enable work eSIM"](https://doggopwn.github.io/redirect?loc=shortcuts://shortcuts/6aa696d37199457cb39d2d1d7e4b718e)
     - [Download "Disable work eSIM"](https://doggopwn.github.io/redirect?loc=shortcuts://shortcuts/7cbe5823ebe543e284398d818f9f597b)

2. Set your eSIM in the shortcut
     - [Edit "Enable work eSIM"](https://doggopwn.github.io/redirect?loc=shortcuts://open-shortcut?name=Enable%20work%20eSIM)
       - In the first block, set your work eSIM.
       - In the following blocks, set your home eSIM.
     -   [Edit "Disable work eSIM"](https://doggopwn.github.io/redirect?loc=shortcuts://open-shortcut?name=Disable%20work%20eSIM)
       - Do the exact same

 3. Create automations to trigger automatically
     1. Open the [automations tab](https://doggopwn.github.io/redirect?loc=shortcuts://automations)
     2. Create a "When I Arrive" automation, and make it run "Enable work eSIM"
     3. Create a "When I Leave" automation, and make it run "Disable work eSIM"
   
 4. You're done!
