# zoom-auto-join-meeting
This repository contains the tools and steps needed to automate zoom to automatically join a zoom meetings using the browser with crontab as its scheduler
(If you want to directly join meetings without the browser involved, scroll to the bottom)

I'm new to python and shell, so if there are way I can learn to make the script any smaller or efficient, please do let me know.

Important note: Make sure to edit "usr" with your username.

The instructions are unix based so, few tweaks should be implemented to make it work on windows.

------------------------------------------------------------------------------

If you hate the idea of opening your webbrowser to join a zoom meeting then use this link: https://www.youtube.com/watch?v=V3IOfvGmqxs
    
When i ran that code, my cpu usage skyrocketed because python interpreter kept running in the back. If you use crontab, you can reduce cpu usage as python interpreter only ran when crontab told it to. By making some minor tweaks to the program that he shows, you can reap better results. 
    
I would recommend watching the youtube video and using crontab for best results. I didn't have time to make a simplified version of his code with crontab so decided to leave it as a suggestion.
