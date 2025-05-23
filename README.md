## Welcome to the incomplete collection of resources for livestreaming videos at BHSS
### Structure
This will be structured in the following way:
- Overall Workflow
- Hardware Documentation
- Software Documentation
- Event Specific Documentation
<!-- this needs clarified, i have no idea what this means or how to structure the documentation given these bullet points -->
# Editing documentation
0. learn markdown
    - [Interactive Markdown Tutorial](https://www.markdowntutorial.com/)
    - [Github Flavored Markdown (GFM) Documentation](https://github.github.com/gfm/)
    - [GFM Cheat Sheet](https://gist.github.com/Myndex/5140d6fe98519bb15c503c490e713233)
    - [Standard Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/)
1. create github codespace
    - add image
2. edit README.md or add files
3. in the terminal run `git add .` then `git commit`
3. describe the changes you made
5. click check mark
    - add image
4. finally run `git push` to sync your changes with the main documentation branch

# Overall Workflow
BHSS video creates almost every production through the use of networked cameras. By using networked cameras as opposed to traditional options we are able to place cameras anywhere there is an ethernet connection. This allows for easy setup and teardown of productions, as well as the ability to quickly switch between different angles and perspectives, without the need for lengthy cable runs back to our streaming computer.

In almost all cases we use NDI to stream video and audio over the network as it allow for low latency and high quality streams and is also simple to set up and use.