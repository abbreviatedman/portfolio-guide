# Getting Started And Getting Deployed

Here are some steps to get you started with Git and GitHub, and to get your first page deployed.

### Creating The Repository

In your browser:

- Create `[username].github.io` on GitHub

### Getting The Repository On Your Machine

In VS Code:

- Command/Ctrl Shift P and choose "git clone" in VS Code
- Log in if you're not already
- Choose the repo `[username].github.io` and where to put it.

### Getting Content Into The Repo

Still in VS Code:

- Create an `index.html` file.
- Type `!` to get the boilerplate HTML.
- Add some test content.
- Save the file. (You should turn on auto-save in the File menu if you don't already have it!)
- Go to the Source Control tab on the left.
- Type a commit message and click the checkmark to commit.
- Click the three dots and choose "Push" to push the commit to GitHub.

### Deploying Your Repo

Back in your browser:

- Reload the repository page. You should see your `index.html` file.
- Click on the Settings tab.
- Look for the "Pages" section, currently a link on the left sidebar.
- Choose the `main` branch and the root folder, then click Save. This may already be done!
- Wait a few seconds and refresh the page. You should see "Your site is live at `https://[username].github.io/`".

### The General Workflow

Back in VS Code:

- Make a change to your `index.html` file. Recommended: create an about.html page and add a link to it in your index.html.
- In the Source Control tab, stage the changes by pressing the plus button.
- Commit and push the change. Recommended way to do this: add a commit message, then there's currently a drop-down next to the commit button with a push option.
- Refresh your browser to see the change. It will hit your repository before it hits the page itself--check the repository page and, assuming it's updated there, give GitHub some time to re-deploy your page.
