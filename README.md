## Welcome to the (in)complete collection of resources and documentation for livestreaming sports and other events at BHSS
### Structure
This will be structured in the following way:
<!-- this needs clarified, i have no idea what this means or how to structure the documentation given these bullet points -->
- Overall Workflow
- Hardware Documentation
- Software Documentation
- Event Specific Documentation
# Editing documentation
0. learn markdown
    - [Interactive Markdown Tutorial](https://www.markdowntutorial.com/)
    - [Github Flavored Markdown (GFM) Documentation](https://github.github.com/gfm/)
    - [GFM Cheat Sheet](https://gist.github.com/Myndex/5140d6fe98519bb15c503c490e713233)
    - [Standard Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)
1. create github codespace
    - if one is already open, ignore it or consult with your team before removing it
    - otherwise, create a new codespace by:

        ![image displaying the steps listed below](<open codespace.png>)

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
<!-- i despise some of the phrasing in this section, ill rewrite it soon enough-->
BHSS video creates almost every production through the use of networked cameras. By using networked cameras as opposed to traditional options we are able to place cameras anywhere there is an ethernet connection. This allows for easy setup and teardown of productions, as well as the ability to quickly switch between different angles and perspectives, without the need for lengthy cable runs back to our streaming computer.

In almost all cases we use NDI to stream video and audio over the network as it allow for low latency and high quality streams and is also simple to set up and use.