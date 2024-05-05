# streaming-01-getting-started

> Get started with Python for streaming analytics

We assume no prior programming experience and that you want to 
get productive as quickly as possible.

This project uses only content from the Python Standard Library. 
No project virtual environment is required. 

These are popular industry tools - we'll practice with them a lot. 
Getting good at them helps you build better analytics projects more efficiently. 

## Prerequisites

You should have these downloaded and installed on your machine:

1. Python 3.10 or higher
1. VS Code
1. VS Code Extension: Python
1. Git (configured with user.name and user.email - the same email you use for GitHub)

Remember:

- **Spacing, Spelling, Capitalization**: When programming, these are critical. Always double-check!

---

## Open Project Folder in VS Code

In VS Code, open just your project repository folder, e.g. Documents/streaming-01-getting-started.

## Verify Installations / Update Default Python

In VS Code, open a terminal window (View / Terminal) and verify your software is installed and configured.

- If Windows, be sure you're using a PowerShell terminal (rather than cmd).

Important: 

- In Windows, you might try `py` instead of `python`.
- Type each command rather than copy & paste for best results. 
- Wait for each command to complete before running the next command.

```shell
git --version
git config user.name
git config user.email
python --version
python -m pip install --upgrade pip wheel
```
✔️ Make sure all commands complete successfully. 

## Execute Utility Script (Diagnostics)

With your repo folder open in VS Code:

1. Click util_about.py.
1. If VS Code prompts, install the recommended Python extension.
1. Check the Python Interpreter: On the bottom-left status bar, you might see a version of Python indicated (e.g., Python 3.12.x).
1. If not, click on the bottom status bar where it should show the Python version or might say "Select Python Interpreter".
1. From the dropdown, choose your default Python version.

Use the terminal and the python command to execute the Python script. 

1. Use your VS Code terminal window from above or open a new terminal window (View / Terminal) in VS Code.

Important: 

- In Windows, you might try `py` instead of `python`.

```shell
python util_about.py
```
✔️ Make sure your script runs successfully. 
---


## Explore & Execute Project Scripts

With our project repository folder open in VS Code, and having confirmed that we can execute a Python script successfully, it's time to explore. 

Open, read, and run each project script (each file will have a .py extension) in order.

When you finish, you'll have an idea of some things possible using just the Python standard library. 
You'll have generated several new data files.
The streaming process will run continuously for quite a while. 
Read the comments in the file to learn how to stop the process.

Important: 

- In Windows, you might try `py` instead of `python`.

```shell
python process_batch_A.py
```

```shell
python process_batch_B.py
```

```shell
python process_batch_C.py
```

```shell
python process_streaming_0.py
```
✔️ Make sure your scripts complete successfully. 
---

## Update Edit README

## Sync to GitHub

Now it's time to get the local work you did on your machine, 
back up to your cloud repo in GitHub.

### Option A: Use VS Code (Easy!)

1. On the VS Code side panel, click the source control icon (look for a blue bubble with an number in it).
1. Important! Above the Commit button, it will say "Message". 
1. You MUST include a commit message. 
1. In the commit message input box, type "initial results".
1. Click the down arrow on the blue "Commit" button to "Commit and Push" to your GitHub repo. 


### Option B: Use Git Bash or Terminal Commands (Easy as well):

Open a new `Git Bash` or Terminal window. Run the following commands one at a time.
They will first add all the files (add "dot"). 
Then they will commit the changes with a message. 
Finally, they will push the changes up to GitHub.

```
git add .
git commit -m "initial results"
git push origin main
```

Open a browser and view your GitHub repository. 
Verify your new files have been successfully pushed to GitHub. 

✔️ Make sure your git add / commit / push completes successfully. 
 
---

## General Recommendations and Troubleshooting

The following are general recommendations and troubleshooting tips.

### Issue: VS Code - No Source Control Icon

Suggestion: If you're in VS Code, and you don't see the Source Control icon with a blue bubble, right-click on the sidebar icons, and make sure "Source Control" is checked.  

### Issue: VS Code wants to install an extension

If VS Code suggests an extension, it's often good to go ahead and try it. 
Do a search on the extension to learn more. VS Code suggestions are usually helpful. 

## Additional Resources

1. For more information about Git in VS Code, see [Using Git source control in VS Code](https://code.visualstudio.com/docs/sourcecontrol/overview).
1. For more information about editing Markdown in VS Code, see [Markdown and Visual Studio Code](https://code.visualstudio.com/docs/languages/markdown).
