## Welcome to the (in)complete collection of resources and documentation for livestreaming sports and other events at BHSS
### Structure
This will be structured in the following way:
<!-- this needs clarified, i have no idea what this means or how to structure the documentation given these bullet points -->
- [Editing Documentation](#editing-documentation)
- [Overall Workflow](#overall-workflow)
- Hardware Documentation
- Software Documentation
- Event Specific Documentation
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

# Overall Workflow
BHSS Video primarily utilizes networked cameras for nearly all its productions. This networking capability enables cameras to be placed anywhere an Ethernet connection is available. Consequently, setting up and tearing down productions is a quick, simple process. Networked cameras also allow quick switching between preset angles.

NDI serves as the main protocol we use for streaming audio and video over the network because it allows for high-quality, low-latency streams. Additionally, NDI has extensive online documentation and is relatively straightforward to configure and operate.