## Welcome to the (in)complete collection of resources and documentation for livestreaming sports and other events at Bloomington High School South (BHSS)
# Table of Contents
- [Editing Documentation](#editing-documentation)
- [Overall Workflow](#overall-workflow)
- [Hardware Documentation](#hardware-documentation)
- [Software Documentation](#software-documentation)
- [Event-Specific Documentation](#event-specific-documentation)

# Editing Documentation
0. learn markdown
    - [Interactive Markdown Tutorial](https://www.markdowntutorial.com/)
    - [Github Flavored Markdown (GFM) Documentation](https://github.github.com/gfm/)
    - [GFM Cheat Sheet](https://gist.github.com/Myndex/5140d6fe98519bb15c503c490e713233)
    - [Standard Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)
1. create github codespace
    - if one is already open, ignore it or consult with your team before removing it
    - otherwise, create a new codespace by:

        ![image displaying the steps listed below](<open codespace.png>)
    <!-- no, i dont in fact like that i have to space the image this way but it doesnt render correctly if i dont -->
    1. clicking the green "Code" button
    2. clicking the "Codespaces" tab within the "Code" dialog
    3. clicking the plus button under codespaces tab
2. edit markdown (`.md`) files
3. save and commit changes
    1. run `git add .` in the terminal
    2. run `git commit` in the terminal
    3. under the newly created "COMMIT_EDITMSG" tab, describe the changes you made
    4. click the checkmark to confirm changes and their description
    ![image of the location of the checkmark](<commit checkmark.png>)
4. run `git push` to sync your changes with the main documentation
5. delete your codespace when you are finished editing
![image displaying the steps listed below](<delete codespace.png>)
    1. click the green "Code" button
    2. click the "Codespaces" tab within the "Code" dialog
    3. click the 3 horizontal dots next to your workspace
    4. click the "Delete" button to delete the workspace
    5. click "Delete" in the "Are you sure?" popup window to confirm the codespace deletion 
        ![image of the location of the delete button](confirmation.png)
        
# Overall Workflow
BHSS Video primarily utilizes networked cameras for nearly all its productions. This networking capability enables cameras to be placed anywhere an Ethernet connection is available. Consequently, setting up and tearing down productions is a quick, simple process. Networked cameras also allow quick switching between preset angles.

NDI serves as the main protocol we use for streaming audio and video over the network because it allows for high-quality, low-latency streams. Additionally, NDI has extensive online documentation and is relatively straightforward to configure and operate.

# Hardware Documentation

# Software Documentation

# Event-Specific Documentation

## Sports
#### [Baseball](events/sports/baseball.md) 
#### [Basketball](events/sports/basketball.md)
#### [Football](events/sports/football.md)
#### [Soccer](events/sports/soccer.md)

## Events <!-- i dont like calling this events within the events category but i cant think of anything else to call it -->
#### [Graduation](events/events/graduation.md)
#### [Night of the Stars](events/events/night%20of%20the%20stars.md)